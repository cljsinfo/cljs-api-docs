## set!



 <table border="1">
<tr>
<td>special form</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/set!</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/set!)
</td>
</tr>
</table>


 <samp>
(__set!__ js-var val)<br>
</samp>

---

Sets `js-var` to `val` using the JavaScript `=` operator.



---


###### See Also:

[`cljs.core/aset`](../cljs.core/aset.md)<br>
[`cljs.core/reset!`](../cljs.core/resetBANG.md)<br>

---




Parser code @ [github](https://github.com/clojure/clojurescript/blob/r993/src/clj/cljs/compiler.clj#L825-L843):

```clj
(defmethod parse 'set!
  [_ env [_ target val] _]
  (disallowing-recur
   (let [enve (assoc env :context :expr)
         targetexpr (if (symbol? target)
                      (do
                        (let [local (-> env :locals target)]
                          (assert (or (nil? local)
                                      (and (:field local)
                                           (:mutable local)))
                                  "Can't set! local var or non-mutable field"))
                        (analyze-symbol enve target))
                      (when (seq? target)
                        (let [targetexpr (analyze-seq enve target nil)]
                          (when (:field targetexpr)
                            targetexpr))))
         valexpr (analyze enve val)]
     (assert targetexpr "set! target must be a field or a symbol naming a var")
     {:env env :op :set! :target targetexpr :val valexpr :children [targetexpr valexpr]})))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r993
└── src
    └── clj
        └── cljs
            └── <ins>[compiler.clj:825-843](https://github.com/clojure/clojurescript/blob/r993/src/clj/cljs/compiler.clj#L825-L843)</ins>
</pre>

-->

---



###### External doc links:

[`clojure.core/set!` @ clojuredocs](http://clojuredocs.org/clojure.core/set!)<br>
[`clojure.core/set!` @ grimoire](http://conj.io/store/v1/org.clojure/clojure/1.7.0-beta3/clj/clojure.core/set%21/)<br>
[`clojure.core/set!` @ crossclj](http://crossclj.info/fun/clojure.core/set%21.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/special/setBANG.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:description "Sets `js-var` to `val` using the JavaScript `=` operator.",
 :ns "special",
 :name "set!",
 :signature ["[js-var val]"],
 :history [["+" "0.0-927"]],
 :type "special form",
 :related ["cljs.core/aset" "cljs.core/reset!"],
 :full-name-encode "special/setBANG",
 :source {:code "(defmethod parse 'set!\n  [_ env [_ target val] _]\n  (disallowing-recur\n   (let [enve (assoc env :context :expr)\n         targetexpr (if (symbol? target)\n                      (do\n                        (let [local (-> env :locals target)]\n                          (assert (or (nil? local)\n                                      (and (:field local)\n                                           (:mutable local)))\n                                  \"Can't set! local var or non-mutable field\"))\n                        (analyze-symbol enve target))\n                      (when (seq? target)\n                        (let [targetexpr (analyze-seq enve target nil)]\n                          (when (:field targetexpr)\n                            targetexpr))))\n         valexpr (analyze enve val)]\n     (assert targetexpr \"set! target must be a field or a symbol naming a var\")\n     {:env env :op :set! :target targetexpr :val valexpr :children [targetexpr valexpr]})))",
          :title "Parser code",
          :repo "clojurescript",
          :tag "r993",
          :filename "src/clj/cljs/compiler.clj",
          :lines [825 843]},
 :full-name "special/set!",
 :clj-symbol "clojure.core/set!"}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "special/set!"]))
```

-->
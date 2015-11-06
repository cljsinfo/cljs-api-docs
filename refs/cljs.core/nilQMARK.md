## cljs.core/nil?



 <table border="1">
<tr>
<td>function/macro</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/nil?</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nil?)
</td>
</tr>
</table>


 <samp>
(__nil?__ x)<br>
</samp>

---

Returns true if `x` is nil, false otherwise.



---


###### See Also:

[`cljs.core/true?`](../cljs.core/trueQMARK.md)<br>
[`cljs.core/false?`](../cljs.core/falseQMARK.md)<br>
[`cljs.core/identity`](../cljs.core/identity.md)<br>

---


Source docstring:

```
Returns true if x is nil, false otherwise.
```


Function code @ [github](https://github.com/clojure/clojurescript/blob/r993/src/cljs/cljs/core.cljs#L214-L217):

```clj
(defn nil?
  [x]
  (identical? x nil))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r993
└── src
    └── cljs
        └── cljs
            └── <ins>[core.cljs:214-217](https://github.com/clojure/clojurescript/blob/r993/src/cljs/cljs/core.cljs#L214-L217)</ins>
</pre>

-->

---

Macro code @ [github](https://github.com/clojure/clojurescript/blob/r993/src/clj/cljs/core.clj#L45-L46):

```clj
(defmacro nil? [x]
  `(identical? ~x nil))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r993
└── src
    └── clj
        └── cljs
            └── <ins>[core.clj:45-46](https://github.com/clojure/clojurescript/blob/r993/src/clj/cljs/core.clj#L45-L46)</ins>
</pre>
-->

---


###### External doc links:

[`clojure.core/nil?` @ clojuredocs](http://clojuredocs.org/clojure.core/nil_q)<br>
[`clojure.core/nil?` @ grimoire](http://conj.io/store/v1/org.clojure/clojure/1.7.0-beta3/clj/clojure.core/nil%3F/)<br>
[`clojure.core/nil?` @ crossclj](http://crossclj.info/fun/clojure.core/nil%3F.html)<br>
[`cljs.core/nil?` @ crossclj](http://crossclj.info/fun/cljs.core.cljs/nil%3F.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/cljs.core/nilQMARK.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:description "Returns true if `x` is nil, false otherwise.",
 :ns "cljs.core",
 :name "nil?",
 :signature ["[x]"],
 :history [["+" "0.0-927"]],
 :type "function/macro",
 :related ["cljs.core/true?" "cljs.core/false?" "cljs.core/identity"],
 :full-name-encode "cljs.core/nilQMARK",
 :source {:code "(defn nil?\n  [x]\n  (identical? x nil))",
          :title "Function code",
          :repo "clojurescript",
          :tag "r993",
          :filename "src/cljs/cljs/core.cljs",
          :lines [214 217]},
 :extra-sources [{:code "(defmacro nil? [x]\n  `(identical? ~x nil))",
                  :title "Macro code",
                  :repo "clojurescript",
                  :tag "r993",
                  :filename "src/clj/cljs/core.clj",
                  :lines [45 46]}],
 :full-name "cljs.core/nil?",
 :clj-symbol "clojure.core/nil?",
 :docstring "Returns true if x is nil, false otherwise."}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "cljs.core/nil?"]))
```

-->
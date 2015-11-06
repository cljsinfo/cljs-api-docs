## clojure.core.reducers/foldcat



 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1236"><img valign="middle" alt="[+] 0.0-1236" title="Added in 0.0-1236" src="https://img.shields.io/badge/+-0.0--1236-lightgrey.svg"></a> </td>
</tr>
</table>


 <samp>
(__foldcat__ coll)<br>
</samp>

---





Source docstring:

```
Equivalent to (fold cat append! coll)
```


Source code @ [github](https://github.com/clojure/clojurescript/blob/r1513/src/cljs/clojure/core/reducers.cljs#L228-L231):

```clj
(defn foldcat
  [coll]
  (fold cat append! coll))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r1513
└── src
    └── cljs
        └── clojure
            └── core
                └── <ins>[reducers.cljs:228-231](https://github.com/clojure/clojurescript/blob/r1513/src/cljs/clojure/core/reducers.cljs#L228-L231)</ins>
</pre>

-->

---



###### External doc links:

[`clojure.core.reducers/foldcat` @ crossclj](http://crossclj.info/fun/clojure.core.reducers.cljs/foldcat.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/clojure.core.reducers/foldcat.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:ns "clojure.core.reducers",
 :name "foldcat",
 :signature ["[coll]"],
 :history [["+" "0.0-1236"]],
 :type "function",
 :full-name-encode "clojure.core.reducers/foldcat",
 :source {:code "(defn foldcat\n  [coll]\n  (fold cat append! coll))",
          :title "Source code",
          :repo "clojurescript",
          :tag "r1513",
          :filename "src/cljs/clojure/core/reducers.cljs",
          :lines [228 231]},
 :full-name "clojure.core.reducers/foldcat",
 :docstring "Equivalent to (fold cat append! coll)"}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "clojure.core.reducers/foldcat"]))
```

-->
## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> clojure.string/triml

 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.string/triml</samp>](http://clojure.github.io/clojure/branch-master/clojure.string-api.html#clojure.string/triml)
</td>
</tr>
</table>

 <samp>
(__triml__ s)<br>
</samp>

```
Removes whitespace from the left side of string.
```

---

 <pre>
clojurescript @ r1450
└── src
    └── cljs
        └── clojure
            └── <ins>[string.cljs:111-114](https://github.com/clojure/clojurescript/blob/r1450/src/cljs/clojure/string.cljs#L111-L114)</ins>
</pre>

```clj
(defn triml
    [s]
    (gstring/trimLeft s))
```


---

```clj
{:ns "clojure.string",
 :name "triml",
 :signature ["[s]"],
 :history [["+" "0.0-927"]],
 :type "function",
 :full-name-encode "clojure.string_triml",
 :source {:code "(defn triml\n    [s]\n    (gstring/trimLeft s))",
          :filename "clojurescript/src/cljs/clojure/string.cljs",
          :lines [111 114],
          :link "https://github.com/clojure/clojurescript/blob/r1450/src/cljs/clojure/string.cljs#L111-L114"},
 :full-name "clojure.string/triml",
 :clj-symbol "clojure.string/triml",
 :docstring "Removes whitespace from the left side of string."}

```
## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> cljs.core/Reduced

 <table border="1">
<tr>
<td>type</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
</table>

 <samp>
(__Reduced.__ val)<br>
</samp>

```
(no docstring)
```

---

 <pre>
clojurescript @ r1450
└── src
    └── cljs
        └── cljs
            └── <ins>[core.cljs:1165-1167](https://github.com/clojure/clojurescript/blob/r1450/src/cljs/cljs/core.cljs#L1165-L1167)</ins>
</pre>

```clj
(deftype Reduced [val]
  IDeref
  (-deref [o] val))
```


---

```clj
{:full-name "cljs.core/Reduced",
 :ns "cljs.core",
 :name "Reduced",
 :type "type",
 :signature ["[val]"],
 :source {:code "(deftype Reduced [val]\n  IDeref\n  (-deref [o] val))",
          :filename "clojurescript/src/cljs/cljs/core.cljs",
          :lines [1165 1167],
          :link "https://github.com/clojure/clojurescript/blob/r1450/src/cljs/cljs/core.cljs#L1165-L1167"},
 :full-name-encode "cljs.core_Reduced",
 :history [["+" "0.0-1211"]]}

```
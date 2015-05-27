## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> cljs.core/IStack

 <table border="1">
<tr>
<td>protocol</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
</table>

 <samp>
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
            └── <ins>[core.cljs:186-188](https://github.com/clojure/clojurescript/blob/r1450/src/cljs/cljs/core.cljs#L186-L188)</ins>
</pre>

```clj
(defprotocol IStack
  (-peek [coll])
  (-pop [coll]))
```


---

```clj
{:ns "cljs.core",
 :name "IStack",
 :type "protocol",
 :full-name-encode "cljs.core_IStack",
 :source {:code "(defprotocol IStack\n  (-peek [coll])\n  (-pop [coll]))",
          :filename "clojurescript/src/cljs/cljs/core.cljs",
          :lines [186 188],
          :link "https://github.com/clojure/clojurescript/blob/r1450/src/cljs/cljs/core.cljs#L186-L188"},
 :methods [{:name "-peek", :signature ["[coll]"], :docstring nil}
           {:name "-pop", :signature ["[coll]"], :docstring nil}],
 :full-name "cljs.core/IStack",
 :history [["+" "0.0-927"]]}

```
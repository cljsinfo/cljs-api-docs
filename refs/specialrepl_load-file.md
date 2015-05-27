## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> specialrepl/load-file

 <table border="1">
<tr>
<td>special form (repl)</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/load-file</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/load-file)
</td>
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
    └── clj
        └── cljs
            └── <ins>[repl.clj:141-150](https://github.com/clojure/clojurescript/blob/r1450/src/clj/cljs/repl.clj#L141-L150)</ins>
</pre>

```clj
(def default-special-fns
  (let [load-file-fn (fn [repl-env file] (load-file repl-env file))]
    {'in-ns (fn [_ quoted-ns]
              (let [ns-name (second quoted-ns)]
                (when-not (ana/get-namespace ns-name)
                  (ana/set-namespace ns-name {:name ns-name}))
                (set! ana/*cljs-ns* ns-name)))
     'load-file load-file-fn
     'clojure.core/load-file load-file-fn
     'load-namespace (fn [repl-env ns] (load-namespace repl-env ns))}))
```


---

```clj
{:full-name "specialrepl/load-file",
 :ns "specialrepl",
 :name "load-file",
 :type "special form (repl)",
 :source {:code "(def default-special-fns\n  (let [load-file-fn (fn [repl-env file] (load-file repl-env file))]\n    {'in-ns (fn [_ quoted-ns]\n              (let [ns-name (second quoted-ns)]\n                (when-not (ana/get-namespace ns-name)\n                  (ana/set-namespace ns-name {:name ns-name}))\n                (set! ana/*cljs-ns* ns-name)))\n     'load-file load-file-fn\n     'clojure.core/load-file load-file-fn\n     'load-namespace (fn [repl-env ns] (load-namespace repl-env ns))}))",
          :filename "clojurescript/src/clj/cljs/repl.clj",
          :lines [141 150],
          :link "https://github.com/clojure/clojurescript/blob/r1450/src/clj/cljs/repl.clj#L141-L150"},
 :full-name-encode "specialrepl_load-file",
 :clj-symbol "clojure.core/load-file",
 :history [["+" "0.0-927"]]}

```
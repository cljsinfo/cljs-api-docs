## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> ~~cljs.reader/read-unicode-char~~

 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/api-refs/tree/0.0-1424"><img valign="middle" alt="[×] 0.0-1424" src="https://img.shields.io/badge/×-0.0--1424-red.svg"></a> </td>
</tr>
</table>

 <samp>
(__read-unicode-char__ reader initch)<br>
</samp>

```
(no docstring)
```

---

 <pre>
clojurescript @ r1236
└── src
    └── cljs
        └── cljs
            └── <ins>[reader.cljs:171-173](https://github.com/clojure/clojurescript/blob/r1236/src/cljs/cljs/reader.cljs#L171-L173)</ins>
</pre>

```clj
(defn read-unicode-char
  [reader initch]
  (reader-error reader "Unicode characters not supported by reader (yet)"))
```


---

```clj
{:full-name "cljs.reader/read-unicode-char",
 :ns "cljs.reader",
 :name "read-unicode-char",
 :type "function",
 :signature ["[reader initch]"],
 :source {:code "(defn read-unicode-char\n  [reader initch]\n  (reader-error reader \"Unicode characters not supported by reader (yet)\"))",
          :filename "clojurescript/src/cljs/cljs/reader.cljs",
          :lines [171 173],
          :link "https://github.com/clojure/clojurescript/blob/r1236/src/cljs/cljs/reader.cljs#L171-L173"},
 :full-name-encode "cljs.reader_read-unicode-char",
 :history [["+" "0.0-927"] ["-" "0.0-1424"]],
 :removed {:in "0.0-1424", :last-seen "0.0-1236"}}

```
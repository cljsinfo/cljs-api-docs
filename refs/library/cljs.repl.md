## cljs.repl

 <table border="1">
<tr>
<td>namespace</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.repl</samp>](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html)
</td>
</tr>
</table>

In addition to the [REPL's special forms][doc:library/specialrepl], this
namespace mainly provides reflection capabilities to assist you in exploring
code in a REPL.  It comes with macros that are automatically imported into your
REPL environment, but you can use them outside of one as well.

These macros allow you to explore code by listing/searching available vars in a
namespace and viewing a var's documentation or source.

[doc:library/specialrepl]:../library/specialrepl

---


###### Public Symbols:

 <table>
<thead><tr>
<th>=</th>
<th>Name</th>
<th>Type</th>
<th>History</th>
</tr></thead>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html#clojure.repl/apropos)</td>
<td><samp>[apropos](../cljs.repl/apropos.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2985"><img valign="middle" alt="[+] 0.0-2985" title="Added in 0.0-2985" src="https://img.shields.io/badge/+-0.0--2985-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html#clojure.repl/dir)</td>
<td><samp>[dir](../cljs.repl/dir.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2985"><img valign="middle" alt="[+] 0.0-2985" title="Added in 0.0-2985" src="https://img.shields.io/badge/+-0.0--2985-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html#clojure.repl/doc)</td>
<td><samp>[doc](../cljs.repl/doc.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[err-out](../cljs.repl/err-out.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-3148"><img valign="middle" alt="[+] 0.0-3148" title="Added in 0.0-3148" src="https://img.shields.io/badge/+-0.0--3148-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html#clojure.repl/find-doc)</td>
<td><samp>[find-doc](../cljs.repl/find-doc.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2985"><img valign="middle" alt="[+] 0.0-2985" title="Added in 0.0-2985" src="https://img.shields.io/badge/+-0.0--2985-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[print-doc](../cljs.repl/print-doc.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html#clojure.repl/pst)</td>
<td><samp>[pst](../cljs.repl/pst.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2985"><img valign="middle" alt="[+] 0.0-2985" title="Added in 0.0-2985" src="https://img.shields.io/badge/+-0.0--2985-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.repl-api.html#clojure.repl/source)</td>
<td><samp>[source](../cljs.repl/source.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2985"><img valign="middle" alt="[+] 0.0-2985" title="Added in 0.0-2985" src="https://img.shields.io/badge/+-0.0--2985-lightgrey.svg"></a> </td>
</tr>
</table>

---

###### Symbols removed or no longer public:

 <table>
<thead><tr>
<th>=</th>
<th>Name</th>
<th>Type</th>
<th>History</th>
</tr></thead>
<tr>
<td></td>
<td><samp>[~~with-read-known~~](../cljs.repl/with-read-known.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2719"><img valign="middle" alt="[+] 0.0-2719" title="Added in 0.0-2719" src="https://img.shields.io/badge/+-0.0--2719-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2911"><img valign="middle" alt="[×] 0.0-2911" title="Removed in 0.0-2911" src="https://img.shields.io/badge/×-0.0--2911-red.svg"></a> </td>
</tr>
</table>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/cljs.repl.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files
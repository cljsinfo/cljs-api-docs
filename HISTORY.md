# ClojureScript API History

 <table>
<tr>
<th rowspan=2>Version</th>
<th rowspan=2>Date</th>
<th colspan=3>Dependencies</th>
<th colspan=3>Changes</th>
</tr>
<tr>
<th>Clojure</th>
<th>Reader</th>
<th>Closure Lib</th>
<th>syn</th>
<th>lib</th>
<th>comp</th>
</tr>
<tr>
<td>__[0.0-993](https://github.com/cljsinfo/cljs-api-docs/tree/0.0-993)__</td>
<td>2012-02-27</td>
<td><kbd>1.3.0</kbd></td>
<td></td>
<td><kbd>20110323-r790</kbd></td>
<td>
<a href="#user-content-00993syntax">
 
</a>
</td>
<td>
<a href="#user-content-00993library">
 
</a>
</td>
<td>
<a href="#user-content-00993compiler">
+1 
</a>
</td>
</tr>

<tr>
<td>__[0.0-971](https://github.com/cljsinfo/cljs-api-docs/tree/0.0-971)__</td>
<td>2012-01-27</td>
<td><kbd>1.3.0</kbd></td>
<td></td>
<td><kbd>20110323-r790</kbd></td>
<td>
<a href="#user-content-00971syntax">
 
</a>
</td>
<td>
<a href="#user-content-00971library">
+2 
</a>
</td>
<td>
<a href="#user-content-00971compiler">
 
</a>
</td>
</tr>

<tr>
<td>__[0.0-927](https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927)__</td>
<td>2012-01-20</td>
<td><kbd>1.3.0</kbd></td>
<td></td>
<td><kbd>20110323-r790</kbd></td>
<td>
<a href="#user-content-00927syntax">
+42 
</a>
</td>
<td>
<a href="#user-content-00927library">
+509 
</a>
</td>
<td>
<a href="#user-content-00927compiler">
+45 
</a>
</td>
</tr>

</table>

### 0.0-993

<a name="00993syntax"></a> __Syntax Changes__
 <table>
<tr><td>_no syntax forms were added or removed in this version_</td></tr>
</table>

<a name="00993library"></a> __Library API Changes__
 <table>
<tr><td>_no symbols were added or removed in this version_</td></tr>
</table>

<a name="00993compiler"></a> __Compiler API Changes__
 <table>

<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl/default-special-fns](refs/cljs.repl/default-special-fns.md)</samp></td>
</tr>
</table>

### 0.0-971

<a name="00971syntax"></a> __Syntax Changes__
 <table>
<tr><td>_no syntax forms were added or removed in this version_</td></tr>
</table>

<a name="00971library"></a> __Library API Changes__
 <table>

<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IFn](refs/cljs.core/IFn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/type](refs/cljs.core/type.md)</samp></td>
</tr>
</table>

<a name="00971compiler"></a> __Compiler API Changes__
 <table>
<tr><td>_no symbols were added or removed in this version_</td></tr>
</table>

### 0.0-927

<a name="00927syntax"></a> __Syntax Changes__
 <table>

<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>["" string](refs/syntax/string.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[\\ character](refs/syntax/character.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[: keyword](refs/syntax/keyword.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[:: keyword](refs/syntax/keyword-qualify.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[symbol literal](refs/syntax/symbol.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[number literal](refs/syntax/number.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[; comment](refs/syntax/comment.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[() list](refs/syntax/list.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[\[\] vector](refs/syntax/vector.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[{} map](refs/syntax/map.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[@ deref](refs/syntax/deref.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[^ meta](refs/syntax/meta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[' quote](refs/syntax/quote.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[` syntax quote](refs/syntax/syntax-quote.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[~ unquote](refs/syntax/unquote.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[~@ unquote splicing](refs/syntax/unquote-splicing.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[% arg](refs/syntax/arg.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[# dispatch](refs/syntax/dispatch.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#"" regex](refs/syntax/regex.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#{} set](refs/syntax/set.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#() function](refs/syntax/function.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#' var](refs/syntax/var.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#_ ignore](refs/syntax/ignore.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#= eval](refs/syntax/eval.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#<> unreadable](refs/syntax/unreadable.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-syntax-brightgreen.svg">
</td>
<td><samp>[#! shebang](refs/syntax/shebang.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special symbol-brightgreen.svg">
</td>
<td><samp>[boolean literal](refs/syntax/boolean.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special symbol-brightgreen.svg">
</td>
<td><samp>[nil](refs/syntax/nil.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-binding-brightgreen.svg">
</td>
<td><samp>[destructure \[\]](refs/syntax/destructure-vector.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-binding-brightgreen.svg">
</td>
<td><samp>[destructure {}](refs/syntax/destructure-map.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special namespace-brightgreen.svg">
</td>
<td><samp>[js/ namespace](refs/syntax/js-namespace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special namespace-brightgreen.svg">
</td>
<td><samp>[Math/ namespace](refs/syntax/Math-namespace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-convention-brightgreen.svg">
</td>
<td><samp>[? predicate](refs/syntax/predicate.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-convention-brightgreen.svg">
</td>
<td><samp>[! impure](refs/syntax/impure.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-convention-brightgreen.svg">
</td>
<td><samp>[\*earmuffs\*](refs/syntax/earmuffs.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-convention-brightgreen.svg">
</td>
<td><samp>[_ unused](refs/syntax/unused.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special character-brightgreen.svg">
</td>
<td><samp>[, comma](refs/syntax/comma.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special character-brightgreen.svg">
</td>
<td><samp>[/ namespace slash](refs/syntax/namespace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special character-brightgreen.svg">
</td>
<td><samp>[# auto-gensym](refs/syntax/auto-gensym.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special character-brightgreen.svg">
</td>
<td><samp>[. dot](refs/syntax/dot.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special character-brightgreen.svg">
</td>
<td><samp>[& rest](refs/syntax/rest.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special character-brightgreen.svg">
</td>
<td><samp>[whitespace](refs/syntax/whitespace.md)</samp></td>
</tr>
</table>

<a name="00927library"></a> __Library API Changes__
 <table>

<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[.](refs/special/DOT.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[catch](refs/special/catch.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[def](refs/special/def.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[defrecord\*](refs/special/defrecordSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[deftype\*](refs/special/deftypeSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[do](refs/special/do.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[finally](refs/special/finally.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[fn\*](refs/special/fnSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[if](refs/special/if.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[js\*](refs/special/jsSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[let\*](refs/special/letSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[loop\*](refs/special/loopSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[new](refs/special/new.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[ns](refs/special/ns.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[quote](refs/special/quote.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[recur](refs/special/recur.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[set!](refs/special/setBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[throw](refs/special/throw.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form-brightgreen.svg">
</td>
<td><samp>[try\*](refs/special/trySTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form (repl)-brightgreen.svg">
</td>
<td><samp>[in-ns (repl)](refs/specialrepl/in-ns.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form (repl)-brightgreen.svg">
</td>
<td><samp>[load-file (repl)](refs/specialrepl/load-file.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-special form (repl)-brightgreen.svg">
</td>
<td><samp>[load-namespace (repl)](refs/specialrepl/load-namespace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*](refs/cljs.core/STAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*1](refs/cljs.core/STAR1.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*2](refs/cljs.core/STAR2.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*3](refs/cljs.core/STAR3.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*flush-on-newline\*](refs/cljs.core/STARflush-on-newlineSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*main-cli-fn\*](refs/cljs.core/STARmain-cli-fnSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*print-dup\*](refs/cljs.core/STARprint-dupSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*print-fn\*](refs/cljs.core/STARprint-fnSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*print-meta\*](refs/cljs.core/STARprint-metaSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/\*print-readably\*](refs/cljs.core/STARprint-readablySTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/+](refs/cljs.core/PLUS.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/-](refs/cljs.core/-.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/->](refs/cljs.core/-GT.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/->>](refs/cljs.core/-GTGT.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/..](refs/cljs.core/DOTDOT.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core//](refs/cljs.core/SLASH.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/<](refs/cljs.core/LT.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/<=](refs/cljs.core/LTEQ.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/=](refs/cljs.core/EQ.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/==](refs/cljs.core/EQEQ.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/>](refs/cljs.core/GT.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/>=](refs/cljs.core/GTEQ.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Atom](refs/cljs.core/Atom.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Cons](refs/cljs.core/Cons.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Delay](refs/cljs.core/Delay.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/EmptyList](refs/cljs.core/EmptyList.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/HashMap](refs/cljs.core/HashMap.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/HashMap.EMPTY](refs/cljs.core/HashMapDOTEMPTY.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/HashMap.fromArrays](refs/cljs.core/HashMapDOTfromArrays.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IAssociative](refs/cljs.core/IAssociative.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ICollection](refs/cljs.core/ICollection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ICounted](refs/cljs.core/ICounted.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IDeref](refs/cljs.core/IDeref.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IDerefWithTimeout](refs/cljs.core/IDerefWithTimeout.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IEmptyableCollection](refs/cljs.core/IEmptyableCollection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IEquiv](refs/cljs.core/IEquiv.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IHash](refs/cljs.core/IHash.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IIndexed](refs/cljs.core/IIndexed.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ILookup](refs/cljs.core/ILookup.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IMap](refs/cljs.core/IMap.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IMeta](refs/cljs.core/IMeta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IMultiFn](refs/cljs.core/IMultiFn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IPending](refs/cljs.core/IPending.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IPrintable](refs/cljs.core/IPrintable.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IRecord](refs/cljs.core/IRecord.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IReduce](refs/cljs.core/IReduce.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ISeq](refs/cljs.core/ISeq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ISeqable](refs/cljs.core/ISeqable.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ISequential](refs/cljs.core/ISequential.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/ISet](refs/cljs.core/ISet.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IStack](refs/cljs.core/IStack.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IVector](refs/cljs.core/IVector.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IWatchable](refs/cljs.core/IWatchable.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.core/IWithMeta](refs/cljs.core/IWithMeta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/IndexedSeq](refs/cljs.core/IndexedSeq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/LazySeq](refs/cljs.core/LazySeq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/List](refs/cljs.core/List.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/List.EMPTY](refs/cljs.core/ListDOTEMPTY.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/MultiFn](refs/cljs.core/MultiFn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/NeverEquiv](refs/cljs.core/NeverEquiv.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/ObjMap](refs/cljs.core/ObjMap.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/ObjMap.EMPTY](refs/cljs.core/ObjMapDOTEMPTY.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/ObjMap.fromObject](refs/cljs.core/ObjMapDOTfromObject.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/PersistentQueue](refs/cljs.core/PersistentQueue.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/PersistentQueue.EMPTY](refs/cljs.core/PersistentQueueDOTEMPTY.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/PersistentQueueSeq](refs/cljs.core/PersistentQueueSeq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Range](refs/cljs.core/Range.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Set](refs/cljs.core/Set.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/Set.EMPTY](refs/cljs.core/SetDOTEMPTY.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Subvec](refs/cljs.core/Subvec.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.core/Vector](refs/cljs.core/Vector.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.core/Vector.EMPTY](refs/cljs.core/VectorDOTEMPTY.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/Vector.fromArray](refs/cljs.core/VectorDOTfromArray.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/aclone](refs/cljs.core/aclone.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/add-watch](refs/cljs.core/add-watch.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/aget](refs/cljs.core/aget.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/alength](refs/cljs.core/alength.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/alter-meta!](refs/cljs.core/alter-metaBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/amap](refs/cljs.core/amap.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/ancestors](refs/cljs.core/ancestors.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/and](refs/cljs.core/and.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/apply](refs/cljs.core/apply.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/areduce](refs/cljs.core/areduce.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/array](refs/cljs.core/array.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/array-seq](refs/cljs.core/array-seq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/aset](refs/cljs.core/aset.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/assert](refs/cljs.core/assert.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/assoc](refs/cljs.core/assoc.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/assoc-in](refs/cljs.core/assoc-in.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/associative?](refs/cljs.core/associativeQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/atom](refs/cljs.core/atom.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/binding](refs/cljs.core/binding.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-and](refs/cljs.core/bit-and.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-and-not](refs/cljs.core/bit-and-not.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-clear](refs/cljs.core/bit-clear.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-flip](refs/cljs.core/bit-flip.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-not](refs/cljs.core/bit-not.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-or](refs/cljs.core/bit-or.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-set](refs/cljs.core/bit-set.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-shift-left](refs/cljs.core/bit-shift-left.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-shift-right](refs/cljs.core/bit-shift-right.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-test](refs/cljs.core/bit-test.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/bit-xor](refs/cljs.core/bit-xor.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/boolean](refs/cljs.core/boolean.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/butlast](refs/cljs.core/butlast.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/coll?](refs/cljs.core/collQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/comment](refs/cljs.core/comment.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/comp](refs/cljs.core/comp.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/compare](refs/cljs.core/compare.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/compare-and-set!](refs/cljs.core/compare-and-setBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/complement](refs/cljs.core/complement.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/concat](refs/cljs.core/concat.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/cond](refs/cljs.core/cond.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/condp](refs/cljs.core/condp.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/conj](refs/cljs.core/conj.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/cons](refs/cljs.core/cons.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/constantly](refs/cljs.core/constantly.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/contains?](refs/cljs.core/containsQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/count](refs/cljs.core/count.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/counted?](refs/cljs.core/countedQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/cycle](refs/cljs.core/cycle.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/dec](refs/cljs.core/dec.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/declare](refs/cljs.core/declare.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defmacro](refs/cljs.core/defmacro.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defmethod](refs/cljs.core/defmethod.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defmulti](refs/cljs.core/defmulti.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defn](refs/cljs.core/defn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defn-](refs/cljs.core/defn-.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defprotocol](refs/cljs.core/defprotocol.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/defrecord](refs/cljs.core/defrecord.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/deftype](refs/cljs.core/deftype.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/delay](refs/cljs.core/delay.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/delay?](refs/cljs.core/delayQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/deref](refs/cljs.core/deref.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/derive](refs/cljs.core/derive.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/descendants](refs/cljs.core/descendants.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/disj](refs/cljs.core/disj.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/dissoc](refs/cljs.core/dissoc.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/distinct](refs/cljs.core/distinct.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/distinct?](refs/cljs.core/distinctQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/doall](refs/cljs.core/doall.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/dorun](refs/cljs.core/dorun.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/doseq](refs/cljs.core/doseq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/dotimes](refs/cljs.core/dotimes.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/doto](refs/cljs.core/doto.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/drop](refs/cljs.core/drop.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/drop-last](refs/cljs.core/drop-last.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/drop-while](refs/cljs.core/drop-while.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/empty](refs/cljs.core/empty.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/empty?](refs/cljs.core/emptyQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/even?](refs/cljs.core/evenQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/every-pred](refs/cljs.core/every-pred.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/every?](refs/cljs.core/everyQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/extend-protocol](refs/cljs.core/extend-protocol.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/extend-type](refs/cljs.core/extend-type.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/false?](refs/cljs.core/falseQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/ffirst](refs/cljs.core/ffirst.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/filter](refs/cljs.core/filter.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/find](refs/cljs.core/find.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/first](refs/cljs.core/first.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/flatten](refs/cljs.core/flatten.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/flush](refs/cljs.core/flush.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/fn](refs/cljs.core/fn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/fn?](refs/cljs.core/fnQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/fnext](refs/cljs.core/fnext.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/fnil](refs/cljs.core/fnil.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/for](refs/cljs.core/for.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/force](refs/cljs.core/force.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/frequencies](refs/cljs.core/frequencies.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/gensym](refs/cljs.core/gensym.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/get](refs/cljs.core/get.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/get-in](refs/cljs.core/get-in.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/get-method](refs/cljs.core/get-method.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/get-validator](refs/cljs.core/get-validator.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/group-by](refs/cljs.core/group-by.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/hash](refs/cljs.core/hash.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/hash-combine](refs/cljs.core/hash-combine.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/hash-map](refs/cljs.core/hash-map.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/identical?](refs/cljs.core/identicalQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/identity](refs/cljs.core/identity.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/if-let](refs/cljs.core/if-let.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/if-not](refs/cljs.core/if-not.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/import-macros](refs/cljs.core/import-macros.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/inc](refs/cljs.core/inc.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/instance?](refs/cljs.core/instanceQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/integer?](refs/cljs.core/integerQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/interleave](refs/cljs.core/interleave.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/interpose](refs/cljs.core/interpose.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/into](refs/cljs.core/into.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/is_proto_](refs/cljs.core/is_proto_.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/isa?](refs/cljs.core/isaQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/iterate](refs/cljs.core/iterate.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/js->clj](refs/cljs.core/js-GTclj.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/js-delete](refs/cljs.core/js-delete.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/js-keys](refs/cljs.core/js-keys.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/js-obj](refs/cljs.core/js-obj.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/juxt](refs/cljs.core/juxt.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/keep](refs/cljs.core/keep.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/keep-indexed](refs/cljs.core/keep-indexed.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/keys](refs/cljs.core/keys.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/keyword](refs/cljs.core/keyword.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/keyword?](refs/cljs.core/keywordQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/last](refs/cljs.core/last.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/lazy-seq](refs/cljs.core/lazy-seq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/let](refs/cljs.core/let.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/letfn](refs/cljs.core/letfn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/list](refs/cljs.core/list.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/list\*](refs/cljs.core/listSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/loop](refs/cljs.core/loop.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/make-hierarchy](refs/cljs.core/make-hierarchy.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/map](refs/cljs.core/map.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/map-indexed](refs/cljs.core/map-indexed.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/map?](refs/cljs.core/mapQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/mapcat](refs/cljs.core/mapcat.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/max](refs/cljs.core/max.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/max-key](refs/cljs.core/max-key.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/memoize](refs/cljs.core/memoize.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/merge](refs/cljs.core/merge.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/merge-with](refs/cljs.core/merge-with.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/meta](refs/cljs.core/meta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/methods](refs/cljs.core/methods.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/min](refs/cljs.core/min.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/min-key](refs/cljs.core/min-key.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/missing-protocol](refs/cljs.core/missing-protocol.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/mod](refs/cljs.core/mod.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/name](refs/cljs.core/name.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/namespace](refs/cljs.core/namespace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/neg?](refs/cljs.core/negQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/newline](refs/cljs.core/newline.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/next](refs/cljs.core/next.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/nfirst](refs/cljs.core/nfirst.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/nil?](refs/cljs.core/nilQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/nnext](refs/cljs.core/nnext.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/not](refs/cljs.core/not.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/not-any?](refs/cljs.core/not-anyQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/not-empty](refs/cljs.core/not-empty.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/not-every?](refs/cljs.core/not-everyQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/not=](refs/cljs.core/notEQ.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/nth](refs/cljs.core/nth.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/nthnext](refs/cljs.core/nthnext.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/number?](refs/cljs.core/numberQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/odd?](refs/cljs.core/oddQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/or](refs/cljs.core/or.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/parents](refs/cljs.core/parents.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/partial](refs/cljs.core/partial.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/partition](refs/cljs.core/partition.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/partition-all](refs/cljs.core/partition-all.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/partition-by](refs/cljs.core/partition-by.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/peek](refs/cljs.core/peek.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/pop](refs/cljs.core/pop.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/pos?](refs/cljs.core/posQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/pr](refs/cljs.core/pr.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/pr-sequential](refs/cljs.core/pr-sequential.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/pr-str](refs/cljs.core/pr-str.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/pr-str-with-opts](refs/cljs.core/pr-str-with-opts.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/pr-with-opts](refs/cljs.core/pr-with-opts.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/prefer-method](refs/cljs.core/prefer-method.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/prefers](refs/cljs.core/prefers.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/prim-seq](refs/cljs.core/prim-seq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/print](refs/cljs.core/print.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/println](refs/cljs.core/println.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/prn](refs/cljs.core/prn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/quot](refs/cljs.core/quot.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/rand](refs/cljs.core/rand.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/rand-int](refs/cljs.core/rand-int.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/rand-nth](refs/cljs.core/rand-nth.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/range](refs/cljs.core/range.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/re-find](refs/cljs.core/re-find.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/re-matches](refs/cljs.core/re-matches.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/re-pattern](refs/cljs.core/re-pattern.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/re-seq](refs/cljs.core/re-seq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/realized?](refs/cljs.core/realizedQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/reduce](refs/cljs.core/reduce.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/reductions](refs/cljs.core/reductions.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/reify](refs/cljs.core/reify.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/rem](refs/cljs.core/rem.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/remove](refs/cljs.core/remove.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/remove-all-methods](refs/cljs.core/remove-all-methods.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/remove-method](refs/cljs.core/remove-method.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/remove-watch](refs/cljs.core/remove-watch.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/repeat](refs/cljs.core/repeat.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/repeatedly](refs/cljs.core/repeatedly.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/replace](refs/cljs.core/replace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/replicate](refs/cljs.core/replicate.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/reset!](refs/cljs.core/resetBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/reset-meta!](refs/cljs.core/reset-metaBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/rest](refs/cljs.core/rest.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/reverse](refs/cljs.core/reverse.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/satisfies?](refs/cljs.core/satisfiesQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/second](refs/cljs.core/second.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/select-keys](refs/cljs.core/select-keys.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/seq](refs/cljs.core/seq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/seq?](refs/cljs.core/seqQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/sequential?](refs/cljs.core/sequentialQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/set](refs/cljs.core/set.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/set-validator!](refs/cljs.core/set-validatorBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/set?](refs/cljs.core/setQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/some](refs/cljs.core/some.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/some-fn](refs/cljs.core/some-fn.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/sort](refs/cljs.core/sort.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/sort-by](refs/cljs.core/sort-by.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/split-at](refs/cljs.core/split-at.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/split-with](refs/cljs.core/split-with.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/spread](refs/cljs.core/spread.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/str](refs/cljs.core/str.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/string-print](refs/cljs.core/string-print.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/string?](refs/cljs.core/stringQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/subs](refs/cljs.core/subs.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/subvec](refs/cljs.core/subvec.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/swap!](refs/cljs.core/swapBANG.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/symbol](refs/cljs.core/symbol.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/symbol?](refs/cljs.core/symbolQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/take](refs/cljs.core/take.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/take-last](refs/cljs.core/take-last.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/take-nth](refs/cljs.core/take-nth.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/take-while](refs/cljs.core/take-while.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/this-as](refs/cljs.core/this-as.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/time](refs/cljs.core/time.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/to-array](refs/cljs.core/to-array.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/trampoline](refs/cljs.core/trampoline.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/tree-seq](refs/cljs.core/tree-seq.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/true?](refs/cljs.core/trueQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/try](refs/cljs.core/try.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/undefined?](refs/cljs.core/undefinedQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/underive](refs/cljs.core/underive.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/update-in](refs/cljs.core/update-in.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/vals](refs/cljs.core/vals.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/vary-meta](refs/cljs.core/vary-meta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/vec](refs/cljs.core/vec.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/vector](refs/cljs.core/vector.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/vector?](refs/cljs.core/vectorQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/when](refs/cljs.core/when.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/when-first](refs/cljs.core/when-first.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/when-let](refs/cljs.core/when-let.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/when-not](refs/cljs.core/when-not.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/while](refs/cljs.core/while.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/with-meta](refs/cljs.core/with-meta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function/macro-brightgreen.svg">
</td>
<td><samp>[cljs.core/zero?](refs/cljs.core/zeroQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.core/zipmap](refs/cljs.core/zipmap.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.nodejs/process](refs/cljs.nodejs/process.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.nodejs/require](refs/cljs.nodejs/require.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.reader/PushbackReader](refs/cljs.reader/PushbackReader.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-type-brightgreen.svg">
</td>
<td><samp>[cljs.reader/StringPushbackReader](refs/cljs.reader/StringPushbackReader.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/desugar-meta](refs/cljs.reader/desugar-meta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/dispatch-macros](refs/cljs.reader/dispatch-macros.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/escape-char](refs/cljs.reader/escape-char.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/escape-char-map](refs/cljs.reader/escape-char-map.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/float-pattern](refs/cljs.reader/float-pattern.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/int-pattern](refs/cljs.reader/int-pattern.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/macro-terminating?](refs/cljs.reader/macro-terminatingQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/macros](refs/cljs.reader/macros.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/not-implemented](refs/cljs.reader/not-implemented.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/push-back-reader](refs/cljs.reader/push-back-reader.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/ratio-pattern](refs/cljs.reader/ratio-pattern.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read](refs/cljs.reader/read.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-comment](refs/cljs.reader/read-comment.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-delimited-list](refs/cljs.reader/read-delimited-list.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-discard](refs/cljs.reader/read-discard.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-dispatch](refs/cljs.reader/read-dispatch.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-keyword](refs/cljs.reader/read-keyword.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-list](refs/cljs.reader/read-list.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-map](refs/cljs.reader/read-map.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-meta](refs/cljs.reader/read-meta.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-number](refs/cljs.reader/read-number.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-past](refs/cljs.reader/read-past.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-regex](refs/cljs.reader/read-regex.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-set](refs/cljs.reader/read-set.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-string](refs/cljs.reader/read-string.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-symbol](refs/cljs.reader/read-symbol.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-token](refs/cljs.reader/read-token.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-unicode-char](refs/cljs.reader/read-unicode-char.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-unmatched-delimiter](refs/cljs.reader/read-unmatched-delimiter.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/read-vector](refs/cljs.reader/read-vector.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/reader-error](refs/cljs.reader/reader-error.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/skip-line](refs/cljs.reader/skip-line.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/special-symbols](refs/cljs.reader/special-symbols.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.reader/symbol-pattern](refs/cljs.reader/symbol-pattern.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/throwing-reader](refs/cljs.reader/throwing-reader.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.reader/wrapping-reader](refs/cljs.reader/wrapping-reader.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/DOMBuilder](refs/clojure.browser.dom/DOMBuilder.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/append](refs/clojure.browser.dom/append.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/click-element](refs/clojure.browser.dom/click-element.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/element](refs/clojure.browser.dom/element.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/ensure-element](refs/clojure.browser.dom/ensure-element.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/get-element](refs/clojure.browser.dom/get-element.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/get-value](refs/clojure.browser.dom/get-value.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/html->dom](refs/clojure.browser.dom/html-GTdom.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/insert-at](refs/clojure.browser.dom/insert-at.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/log](refs/clojure.browser.dom/log.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/log-obj](refs/clojure.browser.dom/log-obj.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/remove-children](refs/clojure.browser.dom/remove-children.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/replace-node](refs/clojure.browser.dom/replace-node.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/set-properties](refs/clojure.browser.dom/set-properties.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/set-text](refs/clojure.browser.dom/set-text.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.dom/set-value](refs/clojure.browser.dom/set-value.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/EventType](refs/clojure.browser.event/EventType.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/all-listeners](refs/clojure.browser.event/all-listeners.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/dispatch-event](refs/clojure.browser.event/dispatch-event.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/expose](refs/clojure.browser.event/expose.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/fire-listeners](refs/clojure.browser.event/fire-listeners.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/get-listener](refs/clojure.browser.event/get-listener.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/has-listener](refs/clojure.browser.event/has-listener.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/listen](refs/clojure.browser.event/listen.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/listen-once](refs/clojure.browser.event/listen-once.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/remove-all](refs/clojure.browser.event/remove-all.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/total-listener-count](refs/clojure.browser.event/total-listener-count.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/unique-event-id](refs/clojure.browser.event/unique-event-id.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/unlisten](refs/clojure.browser.event/unlisten.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.event/unlisten-by-key](refs/clojure.browser.event/unlisten-by-key.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/\*timeout\*](refs/clojure.browser.net/STARtimeoutSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/IConnection](refs/clojure.browser.net/IConnection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/ICrossPageChannel](refs/clojure.browser.net/ICrossPageChannel.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/event-types](refs/clojure.browser.net/event-types.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/xhr-connection](refs/clojure.browser.net/xhr-connection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/xpc-config-fields](refs/clojure.browser.net/xpc-config-fields.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.net/xpc-connection](refs/clojure.browser.net/xpc-connection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/connect](refs/clojure.browser.repl/connect.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/evaluate-javascript](refs/clojure.browser.repl/evaluate-javascript.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/order](refs/clojure.browser.repl/order.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/repl-print](refs/clojure.browser.repl/repl-print.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/send-print](refs/clojure.browser.repl/send-print.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/send-result](refs/clojure.browser.repl/send-result.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/start-evaluator](refs/clojure.browser.repl/start-evaluator.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/wrap-message](refs/clojure.browser.repl/wrap-message.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[clojure.browser.repl/xpc-connection](refs/clojure.browser.repl/xpc-connection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/difference](refs/clojure.set/difference.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/index](refs/clojure.set/index.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/intersection](refs/clojure.set/intersection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/join](refs/clojure.set/join.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/map-invert](refs/clojure.set/map-invert.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/project](refs/clojure.set/project.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/rename](refs/clojure.set/rename.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/rename-keys](refs/clojure.set/rename-keys.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/select](refs/clojure.set/select.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/subset?](refs/clojure.set/subsetQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/superset?](refs/clojure.set/supersetQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.set/union](refs/clojure.set/union.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/blank?](refs/clojure.string/blankQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/capitalize](refs/clojure.string/capitalize.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/escape](refs/clojure.string/escape.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/join](refs/clojure.string/join.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/lower-case](refs/clojure.string/lower-case.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/replace](refs/clojure.string/replace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/replace-first](refs/clojure.string/replace-first.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/reverse](refs/clojure.string/reverse.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/split](refs/clojure.string/split.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/split-lines](refs/clojure.string/split-lines.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/trim](refs/clojure.string/trim.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/trim-newline](refs/clojure.string/trim-newline.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/triml](refs/clojure.string/triml.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/trimr](refs/clojure.string/trimr.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.string/upper-case](refs/clojure.string/upper-case.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/keywordize-keys](refs/clojure.walk/keywordize-keys.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/postwalk](refs/clojure.walk/postwalk.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/postwalk-replace](refs/clojure.walk/postwalk-replace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/prewalk](refs/clojure.walk/prewalk.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/prewalk-replace](refs/clojure.walk/prewalk-replace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/stringify-keys](refs/clojure.walk/stringify-keys.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.walk/walk](refs/clojure.walk/walk.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/append-child](refs/clojure.zip/append-child.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/branch?](refs/clojure.zip/branchQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/children](refs/clojure.zip/children.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/down](refs/clojure.zip/down.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/edit](refs/clojure.zip/edit.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/end?](refs/clojure.zip/endQMARK.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/insert-child](refs/clojure.zip/insert-child.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/insert-left](refs/clojure.zip/insert-left.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/insert-right](refs/clojure.zip/insert-right.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/left](refs/clojure.zip/left.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/leftmost](refs/clojure.zip/leftmost.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/lefts](refs/clojure.zip/lefts.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/make-node](refs/clojure.zip/make-node.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/next](refs/clojure.zip/next.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/node](refs/clojure.zip/node.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/path](refs/clojure.zip/path.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/prev](refs/clojure.zip/prev.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/remove](refs/clojure.zip/remove.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/replace](refs/clojure.zip/replace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/right](refs/clojure.zip/right.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/rightmost](refs/clojure.zip/rightmost.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/rights](refs/clojure.zip/rights.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/root](refs/clojure.zip/root.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/seq-zip](refs/clojure.zip/seq-zip.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/up](refs/clojure.zip/up.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/vector-zip](refs/clojure.zip/vector-zip.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/xml-zip](refs/clojure.zip/xml-zip.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[clojure.zip/zipper](refs/clojure.zip/zipper.md)</samp></td>
</tr>
</table>

<a name="00927compiler"></a> __Compiler API Changes__
 <table>

<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-dynamic var-brightgreen.svg">
</td>
<td><samp>[cljs.repl/\*cljs-verbose\*](refs/cljs.repl/STARcljs-verboseSTAR.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.repl/IJavaScriptEnv](refs/cljs.repl/IJavaScriptEnv.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl/evaluate-form](refs/cljs.repl/evaluate-form.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl/load-file](refs/cljs.repl/load-file.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl/load-namespace](refs/cljs.repl/load-namespace.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl/load-stream](refs/cljs.repl/load-stream.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl/repl](refs/cljs.repl/repl.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/add-in-order](refs/cljs.repl.browser/add-in-order.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/browser-eval](refs/cljs.repl.browser/browser-eval.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/compile-client-js](refs/cljs.repl.browser/compile-client-js.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/constrain-order](refs/cljs.repl.browser/constrain-order.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/create-client-js-file](refs/cljs.repl.browser/create-client-js-file.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/handle-connection](refs/cljs.repl.browser/handle-connection.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/handle-get](refs/cljs.repl.browser/handle-get.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-multimethod-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/handle-post](refs/cljs.repl.browser/handle-post.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/load-javascript](refs/cljs.repl.browser/load-javascript.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/loaded-libs](refs/cljs.repl.browser/loaded-libs.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/ordering](refs/cljs.repl.browser/ordering.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/parse-headers](refs/cljs.repl.browser/parse-headers.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/read-get](refs/cljs.repl.browser/read-get.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/read-headers](refs/cljs.repl.browser/read-headers.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/read-post](refs/cljs.repl.browser/read-post.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/read-request](refs/cljs.repl.browser/read-request.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/repl-client-js](refs/cljs.repl.browser/repl-client-js.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/repl-env](refs/cljs.repl.browser/repl-env.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/run-in-order](refs/cljs.repl.browser/run-in-order.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/send-404](refs/cljs.repl.browser/send-404.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/send-and-close](refs/cljs.repl.browser/send-and-close.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/send-for-eval](refs/cljs.repl.browser/send-for-eval.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/send-repl-client-page](refs/cljs.repl.browser/send-repl-client-page.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/server-loop](refs/cljs.repl.browser/server-loop.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/server-state](refs/cljs.repl.browser/server-state.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/start-server](refs/cljs.repl.browser/start-server.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.browser/stop-server](refs/cljs.repl.browser/stop-server.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-protocol-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/IEval](refs/cljs.repl.rhino/IEval.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/bootjs](refs/cljs.repl.rhino/bootjs.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/current-repl-env](refs/cljs.repl.rhino/current-repl-env.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-multimethod-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/eval-result](refs/cljs.repl.rhino/eval-result.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/goog-require](refs/cljs.repl.rhino/goog-require.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/load-javascript](refs/cljs.repl.rhino/load-javascript.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-var-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/loaded-libs](refs/cljs.repl.rhino/loaded-libs.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/repl-env](refs/cljs.repl.rhino/repl-env.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/rhino-eval](refs/cljs.repl.rhino/rhino-eval.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-function-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/rhino-setup](refs/cljs.repl.rhino/rhino-setup.md)</samp></td>
</tr>
<tr>
<td>
<img valign="middle" src="https://img.shields.io/badge/+-multimethod-brightgreen.svg">
</td>
<td><samp>[cljs.repl.rhino/stacktrace](refs/cljs.repl.rhino/stacktrace.md)</samp></td>
</tr>
</table>

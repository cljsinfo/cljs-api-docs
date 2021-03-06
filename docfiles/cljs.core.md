---
name: cljs.core
---

## Summary

core library

## Details

This is the core library of ClojureScript, providing core operations for
managing state, creating/manipulating/querying data structures, interop with
JS, many predicates, etc.

###### Some side notes:

- All of the core library can be referenced without the `cljs.core/` qualification.
- Operations listed as `function/macro` are flexible and can be used as macros
  or functions when appropriate.  [details here](https://github.com/clojure/clojurescript/wiki/Differences-from-Clojure#macros)
- You can use this reference to explore the core types and protocols used to
  implement many of the operations in this core library.
- We are currently only listing the "ClojureScript JVM" implementations here.
  The "ClojureScript JS" macro implementations are not listed here, but their
  API is identical of course.

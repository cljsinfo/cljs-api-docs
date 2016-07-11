---
name: syntax/namespace
display: "/ namespace slash"
see also:
  - syntax/dot
---

## Summary

## Details

`/` can appear once inside a symbol. The left side of `/` must always be a namespace.
The right side completes the reference to the symbol.

It should be noted that this __differs from Clojure__.  For example,
notice `/` appearing before `PersistentVector` in Clojure:

- Clojure: `clojure.lang.PersistentVector/EMPTY`
- ClojureScript: `cljs.core/PersistentVector.EMPTY`

[doc:cljs.core//] is the division function if it is by itself.

See [doc:syntax/dot] for usage of dots on either side of `/`

## Examples

## Usage
foo/baz
foo.bar/baz
---
name: cljs.core/nth
see also:
  - cljs.core/first
  - cljs.core/second
  - cljs.core/nthnext
  - cljs.core/get
---

## Summary

## Details

Returns the value at index `n` or `not-found` if the index is out of bounds.

`nth` will throw an exception if `n` is out of bounds and `not-found` is not
supplied.

`nth` works for Strings, Arrays, Regex Matchers, Lists, and Sequences. For
Sequences, `nth` takes O(n) time.

## Examples

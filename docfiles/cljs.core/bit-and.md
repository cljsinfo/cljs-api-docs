---
name: cljs.core/bit-and
see also:
  - cljs.core/bit-or
---

## Summary

## Details

Bitwise "and".  Same as `x & y` in JavaScript.

## Examples

Bits can be entered using radix notation:

```clj
(bit-and 2r1100 2r1010)
;;=> 8
;; 8 = 2r1000
```

Same numbers in decimal:

```clj
(bit-and 12 10)
;;=> 8
```

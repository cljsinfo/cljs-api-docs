---
name: cljs.core//
see also:
  - cljs.core/*
  - cljs.core/quot
---

## Summary

## Details

If no denominators are supplied, returns 1/numerator, else returns numerator
divided by all of the denominators.

## Examples

```clj
(/ 6 3)
;;=> 2

(/ 6 3 2)
;;=> 1

(/ 10)
;;=> 0.1

(/ 1 3)
;;=> 0.3333333333333333
```

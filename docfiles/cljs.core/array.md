---
name: cljs.core/array
see also:
  - cljs.core/aclone
  - cljs.core/make-array
  - cljs.core/clj->js
---

## Summary

`(array 1 2 3 ...)`

Creates a JavaScript array containing the given args.

## Details

The tagged literal `#js [1 2 3]` is equivalent to `(array 1 2 3)`

## Examples

```clj
(array 1 2 3)
;;=> #js [1 2 3]

(apply array [1 2 3])
;;=> #js [1 2 3]

#js [1 2 3]
;;=> #js [1 2 3]
```

When creating nested JavaScript arrays, you can opt to use `clj->js` instead:

```clj
(array 1 2 (array 3 4))
;;=> #js [1 2 #js [3 4]]

(clj->js [1 2 [3 4]])
;;=> #js [1 2 #js [3 4]]
```

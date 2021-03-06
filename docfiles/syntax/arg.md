---
name: syntax/arg
display as: "% arg"
clojure doc: http://clojure.org/reference/reader#_dispatch
see also:
  - syntax/function
---

## Summary

Use `%` as the implicit argument to a [doc:syntax/function], or use the following
if there are more than one:

- `%1` - first arg
- `%2` - second arg
- `%3` - third arg
- `%&` - rest of the args

## Details

## Examples

```clj
(map #(* 2 %) [1 2 3])
;;=> (2 4 6)

(def f #(println %1 %2 %&))
(f 1 2 3 4 5)
;; prints: 1 2 (3 4 5)
```

<!-- AUTO-GENERATED docfile links for github -->
[doc:syntax/function]:https://github.com/cljs/api/blob/master/docfiles/syntax/function.md

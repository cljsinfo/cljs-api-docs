---
name: cljs.core/js-invoke
see also:
---

## Summary

## Details

Invoke JavaScript object `obj` method via string `s`. Needed when the string is
not a valid unquoted property name.

## Examples

If we have a JavaScript object with an unusual property name:

```js
// JavaScript
var obj = {
  "my sum": function(a,b) { return a+b; }
};
```

We can invoke it from ClojureScript:

```clj
(js-invoke js/obj "my sum" 1 2)
;=> 3
```

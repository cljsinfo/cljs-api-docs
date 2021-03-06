---
name: cljs.core/lazy-cat
see also:
  - cljs.core/lazy-seq
  - cljs.core/concat
---

## Summary

## Details

Expands to code which yields a lazy sequence of the concatenation of the
supplied collections. Each collections expression is not evaluated until it is
needed.

<table class="code-tbl-9bef6">
  <thead>
    <tr>
      <th>Code</th>
      <th>Expands To</th></tr></thead>
  <tbody>
    <tr>
      <td><code>(lazy-cat x y z)</code>
      <td><pre>
(concat (lazy-seq x)
        (lazy-seq y)
        (lazy-seq z))</pre></td></tr></tbody></table>

## Examples

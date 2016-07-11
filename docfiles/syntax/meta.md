---
name: syntax/meta
display: "^ meta"
see also:
  - cljs.core/meta
  - cljs.core/with-meta
  - cljs.core/vary-meta
  - cljs.core/alter-meta!
---

## Summary

## Details

Attaches metadata to the following form.  Metadata can only be attached to a
symbol or collection.

Metadata will assume the following transformations depending on its type:

- keyword `^:foo` => `^{:foo true}`
- string `^"foo"` => `^{:tag "foo"}`
- symbol `^foo` => `^{:tag <value of foo>}`

## Examples

Attach metadata to a collection:

```clj
^:foo [1 2 3]
;;=> [1 2 3]
```

View the resulting metadata:

```clj
(meta ^:foo [1 2 3])
;;=> {:foo true}

(meta ^{:foo "bar"} [1 2 3])
;;=> {:foo "bar"}

(meta ^"foo" [1 2 3])
;;=> {:tag "foo"}

(def foo 1)
(meta ^foo [1 2 3])
;;=> {:tag 1}
```

Chain metadata:

```clj
(meta ^:foo ^"foo" [1 2 3])
;;=> {:foo true, :tag "foo"}
```

## Usage
^{...}
^:foo
^"foo"
^foo
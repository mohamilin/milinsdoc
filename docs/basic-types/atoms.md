---
sidebar_position: 3
---

# Atoms
Belajar `Atom` pada Elixir.

Tipe data `Atom` merupakan sebuah konstanta yang nilainya adalah dirinya sendiri. Biasanya sih klo di bahasa lain, disebut sebagai symbol.

```elixir
iex > :hello                # hello
iex > :amilin               # amilin

iex > :amilin == :amilin    # true
iex > :amilin == :hello     # false

iex > :true                 # true
iex > :true == true         # true

iex > is_atom(true)         # true
iex > is_atom(:hello)       # true
```
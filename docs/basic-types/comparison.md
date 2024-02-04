---
sidebar_position: 6
---

# Comparison
Belajar `Comparison` pada Elixir

Elixir menyediakan opertor sebagai perbandingan yaitu `==, !=, <=, >=, < and >`


```elixir
iex > 1 == 1        # true
iex > 1 == 2        # false
iex > 1 != 2        # true
iex > 1 < 2         # true
iex > 1 >= 2        # false
```

Kalau kita ingin membandingkan secara ketat / sama persis antara bilangan bulat atau decimal, dapat menggunakan `===`
```elixir
iex > 1 === 1       # true
iex > 1 === 1.0     # false
```
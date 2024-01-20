---
sidebar_position: 1
---

# Basic Arithmetic

Sebelum nya berikut ini contoh untuk tipe data :

```elixir
iex > 1             # integer
iex > 0x0f          # integer => output 15
iex > 0x1f          # integer => output 31
iex > 0x2f          # integer => output 47
iex > 2.9           # float
iex > true          # boolean
iex > :atom         # atom / symbol
iex > "hello world" # string
iex > [1, 2, 2]     # list
iex > {1, 2, 8}     # tuple  
```

Untuk operasi sederhana :
```elixir
iex > 1 + 10        # 11
iex > -1 + 10       # 9
iex > 10 - 2        # 8
iex > 2 - 10        # -8
iex > 2 * 10        # 20
iex > 6 * 1         # 6
iex > 6 / 2         # 3.0 (akan selalu menjadi float)
iex > 6 / 8         # 0.75
iex > div(10, 2)    # 5
iex > div 10,2      #
iex > div (10, 2)   # akan muncul error (invalid syntax)
iex > rem 10,3      # 1  => rem digunakan untuk mencari sisa bagi. 
```

Elixir juga support kalau kita menggunakan binary, oktal, heksadesimal, 
```elixir
iex > 0b1010        # 10
iex > 0o777         # 511
iex > 0x1F          # 31
```

Untuk tipe data `float` setidaknya terdiri dari satu digit dibelakang koma, menariknya Elixir mendukung notasi untuk perhitungan `scientific` dan  memiliki `presisi 64-bit` yang artinya kemampuan untuk melakukan operasi matematika memiliki tingkat akurasi yang tinggi sehingga pengolahan yang dilakukan dapat menjadi sangat baik. 


---
sidebar_position: 4
---

# String
Belajar `String` pada Elixir.


Kalau di Elixir , string adalah tipe data yang paling sering digunakan.  Dalam bahasa ini, kita dapat membuat sebuah string dengan `double " "` dan dikodekan dalam `UTF-8`

```elixir
iex > "hello"                   # hello

# kalau kita inginkan menggabungkan 2 string bisa menggunakan <>
iex > "hello " <> " world"      # hello world

# String pada elixir support `interpolation` juga.
iex > name = "amilin"
iex > "hello #{name}!"          # hello amilin

iex > age = 20
iex > "i'm #{age} years old"    # i'm 20 years old


# String juga dapat handle line break
iex > "moh
... > amilin"                   # moh\namilin
iex > "moh\namilin"              # moh\namilin

# kalau kita ingin melakukan print, dapat menggukana IO.puts
iex  > IO.puts("hello\nworld")
# akan menghasilkan :
    hello
    world
    :ok

# kalau kita ingin mengecek suatu data merupakan binary atau tidak, bisa menggunakan is_binary
iex> is_binary("hello")        # true
iex > is_binar(1223232)        # false

# Kalau kita ingin mengetahui banyak byte dalam suatu sting, dapat menggunakan byte_size / String.length
iex > byte_size("hello")        # 5
iex > Stirng.length("hello")    # 5

# Kalau kita ingin membuat suatu string menjadi haruf kapital, dapat menggunakan upcase
iex > String.upcase("Hello World")     # HELLO WORLD
```
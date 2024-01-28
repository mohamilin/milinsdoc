---
sidebar_position: 2
---

# Boolean dan Nil

Belajar `Boolean dan Nil` pada Elixir.
<br/>

Boolean dan `nil` pada Elixir
```elixir
iex > true          # true
iex > false         # false
iex > nil           # nil
```
Kita bisa melakukan pengecekan untuk menentukan true atau false dengan menggunakan `and, or, not(!)`

****
Perlu diketahui kalau or / and adalah operator singkat yang hanya mengekskusi sisi kanan jika sisi kiri tidak cukup untuk menentukan hasilnya. 

****
```elixir
iex > true or false                 # true
iex > true or is_boolean(false)     # true

iex > true and true                 # true
iex > true and false                # false
iex > false and false               # false
iex > false and is_boolean(false)   # false
iex > 1 and true                    # ** (BadBooleanError) expected a boolean on left-side of "and", got: 1

iex > 1 || true         # 1
iex > true || 1         # true
iex >  nil || true      # true
iex > nil || false      # false
iex > false || nil      # nil
iex > true || nil       # true
iex > nil && 12         # nil
iex > 13 && nil         # nil
iex > true && 12        # 12
iex > true && nil       # nil


iex > !true             # false
iex > !false            # true
iex > !1                # false
iex > !nil              # true
```

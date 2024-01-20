---
sidebar_position: 2
---

# Instalasi

Elixir support pada OS seperti macOS, GNU/Linux, BSD, Windows, Raspberry PI, Docker. 

Namun, kali ini saya ingin mendokumentasikan dengan OS Windows. 

[Detail Installation Elixir](https://elixir-lang.org/install.html)
## [Windows](https://elixir-lang.org/install.html#windows)
### Menggunakan installer
    - Download dan jalankan [_Erlang installer_ ](https://www.erlang.org/downloads.html)
    - Download dan jalankan _Erlang/OTP_ yang sesuai dengan versi Elixir anda.
        - Versi Elixir 1.16.0 untuk Erlang versi 26 [LDOWNNLOADINK](https://github.com/elixir-lang/elixir/releases/download/v1.16.0/elixir-otp-26.exe)
        - Versi Elixir 1.16.0 untuk Erlang versi 25 [DOWNNLOAD](https://github.com/elixir-lang/elixir/releases/download/v1.16.0/elixir-otp-25.exe)
        - Versi Elixir 1.16.0 untuk Erlang versi 24 [DOWNNLOAD](https://github.com/elixir-lang/elixir/releases/download/v1.16.0/elixir-otp-24.exe)
    - Setelah instalasi _restart_ laptop
    - Cek pada terminal (saya menggunakan Git Bash ) dengan mengetikan **elixir --version**. Kalau berhasil akan muncul kalimat kurang lebh seperti ini :
        - `Erlang/OTP 26 [erts-14.2.1] [source] [64-bit] [smp:8:8] [ds:8:8:10] [async-threads:1] [jit:ns]`
        - `Elixir 1.16.0 (compiled with Erlang/OTP 26)`
2
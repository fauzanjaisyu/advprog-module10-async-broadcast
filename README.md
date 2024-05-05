# advprog-module10-async-broadcast

## 2.1 Original code of broadcast chat

Menjalankan 1 server dan 3 client
![alt text](img/1.png)

Untuk menjalankannya, buka 4 terminal terlebih dahulu. Jalankan perintah berikut pada 1 terminal yang akan berperan menjadi server
```rust
cargo run --bin server
```
Kemudian jalankan perintah berikut pada 3 terminal lainnya
```rust
cargo run --bin client 
```

Server berperan sebagai penghubung antara client-client yang terhubung. Setiap client mengirim pesan, server akan menerima pesan dari client tersebut dan mengirimkannya ke tiap client yang terhubung dengan server.
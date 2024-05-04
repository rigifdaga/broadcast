**2.1. Original code of broadcast chat.**  

![](2.1.png)

Setelah server dijalankan dengan perintah `cargo run --bin server` dan setiap klien dijalankan dengan perintah `cargo run --bin client`, dari output di atas dapat dilihat bahwa setiap klien dan juga server menerima siaran obrolan dari setiap klien. Setiap kali seorang klien mengetik pesan pada baris perintah, string tersebut akan dikirim ke server dan server akan terus mengirimkannya ke semua klien yang terhubung padanya.
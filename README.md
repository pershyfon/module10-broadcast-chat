# Nama: Sabrina Aviana Dewi
# NPM: 2206030520

## Reflection
1. Original code of broadcast chat
Execution Result:
![alt text](assets/image.png)
Pada server muncul chat dari 3 client dan pada masing-masing client muncul chat dari client lain sebagai pesan dari server.

2. Modifying the websocket port
Execution Result:
![alt text](assets/image2.png)
Setelah perubahan tersebut, ternyata ketiga client dan server terus berjalan lancar tanpa ada masalah.
Hal ini dikarenakan baik client maupun server menggunakan port yang sama, sehingga tidak ada kesalahan dalam program. Websocket port berubah, namun protocolnya sama.

3. Small changes. Add some information to client
Execution Result:
![alt text](<assets/Screenshot (975).png>)
Dengan dependency `ghostname` menambahkan nama host masing-masing client, seperti `LAPTOP-EEFSS1FF's computer`. Saya memodifikasi pernyataan cetak di src/bin/client.rs dan src/bin/server.rs dengan menambahkan nama host.
---
title: 'Cara Memberi Warna Pada kode Script Terminal dan Termux'
description: 'memberi warna pada terminal, termux, command prompt, cmd python ,bash script, php terminal print warna echo warna di terminal linux'
pubDate: 'Mar 10 2019'
heroImage: '/blog/cara-memberi-warna-pada-kode-script-terminal-dan-termux-command-prompt/hero.png'
---

Terminal atau command promt Merupakan bagian terpenting dari sebuah system computer. Hampir semua komputer memiliki terminal bahkan di android juga sudah banyak aplikasi terminal ini. Terminal mampu menjalankan semua program hardware ataupun software di komputer kita. Karena terminal ini langsung terhubung ke kernel system computer.

kernel ini merupakan program komputer yang menjadi inti dari sebuah system operasi. Sehingga dengan terminal kita bisa melakukan apa saja yang kita mau perintahkan ke computer kita. Mulai dari membuat folder menghapus dsb.

Tak jarang kita membuat aplikasi untuk terminal ini. Karena mudah digunakan dan langsung berjalan sebagaimana yang kita buat menggunakan bahasa program yang kita bisa. Untuk tampilan terminal biasanya kurang bersahabat untuk user permula yang baru mau belajar karena di terminal ini jarang sekali tombol layaknya aplikasi lain yang serba klik.

Maka dari itu agar program yang kita buat lebih sedikit menarik kita bisa memberi warna untuk output program yang dibuat diterminal ini. Untuk membuat output warna di terminal tidak ada yang namanya css seperti kita ngoding untuk website. Dan untuk kali ini saya akan jelaskan bagaimanan memberi warna pada terminal tersebut.

Berikut kode warnanya.
| Kode     | Warna     | 
| -------- | -------- | 
| 33[0;32m | Green|
| 33[32;1m | GreenLight|
| 33[0;36m | Blue|
| 33[36;1m | BlueLight|
| 33[31;1m | Red|
| 33[37;1m | White|
| 33[30;1m | Black|
| 33[33;1m | Yellow|
| 33[1;33m | YellowLight|


Itu kode warnanya dan untuk cara pemasangannya tiap bahasa pemerograman agak beda. Tergantung bagaimana syntak output dari masih-masing bahasa programnya. Disini ada contoh untuk bahasa progam python dan bash. Karena kedua bahasa program ini yang sering dipakai untuk membuat script terminal.

### Output warna di python

Untuk python sendiri itu ada beberapa versi ada versi python , python2, python3. Karena masing-masing versi python tersebut syntak penulisan outputnya berbeda.
### python atau python1
```py
 merah="33[31;1m"
 print (merah+"Output merah")
```

### python2 atau python3
```
 merah="33[31;1m"
 print merah+"Output merah"</code></pre>
```

Disitu saya menambahkan kode warna tersebut ke sebuah variable merah untuk perbedaannya terdapat pada tanda kurung di python 1 kalau tidak pakai kurung maka syntak tersebut akan error.
### Output warna di bash script

Bash ini merupakan perintah biasa di terminal khusunya linux. Namun kadang kita gunakan untuk dijadikan sebuah aplikasi Yang isinya merupakan kumpulan perintah bash yang sudah diatur seperti yang kitainginkan. Penulisan output agar berwarna di bash itu seperti ini.

### Bash
```bash
 biru=`echo "33[0;36m"`
 echo -e"{$biru}==biru output=="
 #atau
 echo -e"$biru"
 #maka output apa aja yang dieluarkan selanjutnya akan biru
 ```
 Jadi itu saja untuk membuat output warna di terminal. Langsung experimen sendiri biar tambah paham. Silahkan berkomentar jika ada pertanyaan.
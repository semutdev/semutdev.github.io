---
title: 'Cara Memberi Warna Pada kode Script Terminal dan Termux'
description: 'memberi warna pada terminal, termux, command prompt, cmd python ,bash script, php terminal print warna echo warna di terminal linux'
pubDate: 'Mar 10 2019'
heroImage: '/blog/cara-memberi-warna-pada-kode-script-terminal-dan-termux-command-prompt/hero.png'
---

<div dir="ltr" style="text-align: left;">
<div style="text-align: justify;">

<b>Terminal atau command promt - </b> Merupakan bagian terpenting dari sebuah system computer. Hampir semua komputer memiliki terminal bahkan di android juga sudah banyak aplikasi terminal ini. Terminal mampu menjalankan semua program hardware ataupun software di komputer kita. Karena terminal ini langsung terhubung ke kernel system computer.

[caption id="attachment_29" align="aligncenter" width="640"]<a href="https://www.kumpul4semut.com/wp-content/uploads/2019/05/20190510_165303.png"><img class="size-large wp-image-29" src="https://www.kumpul4semut.com/wp-content/uploads/2019/05/20190510_165303-1024x576.png" alt="kode warna pada terminal, termux" width="640" height="360" /></a> kode warna pada terminal, termux[/caption]

</div>
<div style="text-align: justify;"></div>
<div style="text-align: justify;">kernel ini merupakan program komputer yang menjadi inti dari sebuah system operasi. Sehingga dengan terminal kita bisa melakukan apa saja yang kita mau perintahkan ke computer kita. Mulai dari membuat folder menghapus dsb.</div>
<div style="text-align: justify;"></div>
<div style="text-align: justify;">Tak jarang kita membuat aplikasi untuk terminal ini. Karena mudah digunakan dan langsung berjalan sebagaimana yang kita buat menggunakan bahasa program yang kita bisa. Untuk tampilan terminal biasanya kurang bersahabat untuk user permula yang baru mau belajar karena di terminal ini jarang sekali tombol layaknya aplikasi lain yang serba klik.</div>
<div style="text-align: justify;"></div>
<div style="text-align: justify;">Maka dari itu agar program yang kita buat lebih sedikit menarik kita bisa memberi warna untuk output program yang dibuat diterminal ini. Untuk membuat output warna di terminal tidak ada yang namanya css seperti kita ngoding untuk website. Dan untuk kali ini saya akan jelaskan bagaimanan memberi warna pada terminal tersebut.</div>
<div style="text-align: justify;"></div>
<div style="text-align: justify;">

Berikut kode warnanya.
<table style="width: 350px;" border="1">
<tbody>
<tr style="background: black; color: white;">
<th>Kode</th>
<th>Warna</th>
</tr>
<tr>
<td>33[0;32m</td>
<td style="background: green;">Green</td>
</tr>
<tr>
<td>33[32;1m</td>
<td style="background: lightgreen;">GreenLight</td>
</tr>
<tr>
<td>33[0;36m</td>
<td style="background: blue;">Blue</td>
</tr>
<tr>
<td>33[36;1m</td>
<td style="background: lightblue;">BlueLight</td>
</tr>
<tr>
<td>33[31;1m</td>
<td style="background: red;">Red</td>
</tr>
<tr>
<td>33[37;1m</td>
<td style="background: white;">White</td>
</tr>
<tr>
<td>33[30;1m</td>
<td style="background: black; color: white;">Black</td>
</tr>
<tr>
<td>33[33;1m</td>
<td style="background: orange;">Yellow</td>
</tr>
<tr>
<td>33[1;33m</td>
<td style="background: yellow;">YellowLight</td>
</tr>
</tbody>
</table>
</div>
<div style="text-align: justify;">

Itu kode warnanya dan untuk cara pemasangannya tiap bahasa pemerograman agak beda. Tergantung bagaimana syntak output dari masih-masing bahasa programnya. Disini ada contoh untuk bahasa progam python dan bash. Karena kedua bahasa program ini yang sering dipakai untuk membuat script terminal.
<h3>Output warna di python</h3>
<div>

Untuk python sendiri itu ada beberapa versi ada versi python , python2, python3. Karena masing-masing versi python tersebut syntak penulisan outputnya berbeda.
<h4>python atau python1</h4>
<pre><code>
 merah="33[31;1m"
 print (merah+"Output merah")
</code></pre>
<h4>python2 atau python3</h4>
<pre><code>
 merah="33[31;1m"
 print merah+"Output merah"</code></pre>
</div>
</div>
<div></div>
Disitu saya menambahkan kode warna tersebut ke sebuah variable merah untuk perbedaannya terdapat pada tanda kurung di python 1 kalau tidak pakai kurung maka syntak tersebut akan error.
<h3>Output warna di bash script</h3>
<div>

Bash ini merupakan perintah biasa di terminal khusunya linux. Namun kadang kita gunakan untuk dijadikan sebuah aplikasi Yang isinya merupakan kumpulan perintah bash yang sudah diatur seperti yang kitainginkan. Penulisan output agar berwarna di bash itu seperti ini.

</div>
<div style="text-align: justify;">
<h4>Bash</h4>
<pre><code>
 biru=`echo "33[0;36m"`
 echo -e"{$biru}==biru output=="
 #atau
 echo -e"$biru"
 #maka output apa aja yang dieluarkan selanjutnya akan biru
</code></pre>
</div>
<div style="text-align: justify;">Jadi itu saja untuk membuat output warna di terminal. Langsung experimen sendiri biar tambah paham. Silahkan berkomentar jika ada pertanyaan.</div>
<div style="text-align: justify;"></div>
</div>
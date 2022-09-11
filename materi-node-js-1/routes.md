# Routes

### Route sederhana untuk menampilkan text

route file **/routes/users.js**

<figure><img src="../.gitbook/assets/image (1) (3).png" alt=""><figcaption></figcaption></figure>

1. import express menggunakan require
2. membuat variable untuk object express.Router()
3. membuat fungsi untuk melakukan get pada path ' / ' dan menampilkan text 'respond with a resource'
4. export router agar bisa modul users.js bisa kita panggil di app.js

### Route sederhana untuk menampilkan file EJS

route file **/routes/index.js**

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

kali ini yang membedakan pada contoh sebelumnya adalah pada bagian res.render

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

res.render memungkinkan kita untuk merender halaman yang terdapat pada folder views yang sudah kita setting sebelumnya ketika melakukan setting template engine

pada res.render parameter pertama merujuk pada file ejs yang terdapat pada folder view

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

pada paramter kedua { title: 'Express' } di gunakan untuk memasukan data pada file ejs

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

hasil dari route index.js&#x20;

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

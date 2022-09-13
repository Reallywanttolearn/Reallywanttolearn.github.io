# Node js arsitektur

## Node JS arsitektur

<figure><img src="../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

V8 memungkinkan kita untuk menulis javascript di luar browser

V8 Mengkonversi javascript yang kita tulis ke kode mesin yang bisa di mengerti oleh komputer

libuv adalah library open source untuk menangani asynchronous input/output

libuv juga memungkinkan node untuk terhubung ke sistem os, file sistem , networking dll

event loop pada libuv di gunakan untuk mengeksekusi tugas yang ringan seperti callback dan network I/O

Thread pool di gunakan untuk mengerjakan tugas yang lebih berat seperti mengakses file dan file compress

libuv di tulis menggunakan bahasa c++



## Event Loop

{% embed url="https://www.youtube.com/watch?t=238s&v=EI7sN1dDwcY" %}

---
cover: >-
  https://images.unsplash.com/photo-1588382472578-8d8b337b277a?crop=entropy&cs=tinysrgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHwxMHx8Y3B1fGVufDB8fHx8MTY1OTM1NzQyNg&ixlib=rb-1.2.1&q=80
coverY: 1350.6167400881056
---

# Synchronous vs Asynchronous

> Saat membuat aplikasi yang concurrent atau parallel, kadang kita sering menemui istilah synchronous dan asynchronous Tidak perlu bingung dengan istilah tersebut, secara sederhana Synchronous adalah ketika kode program kita berjalan secara sequential, dan semua tahapan ditunggu sampai prosesnya selesai baru akan dieksekusi ke tahapan selanjutnya Sedangkan, Asynchronous artinya ketika kode program kita berjalan dan kita tidak perlu menunggu eksekusi kode tersebut selesai, kita bisa lanjutkan ke tahapan kode program selanjutnya

### Diagram Synchronous

![Diagram Synchronous](../.gitbook/assets/sync.png)

### Diagram Asynchronous

![Diagram Asynchronous](../.gitbook/assets/async.png)

### Apa itu Synchronous?

Program dalam JavaScript secara default akan dieksekusi baris per baris Secara default, proses di JavaScript akan dieksekusi secara Synchronous, artinya baris selanjutnya akan dieksekusi setelah baris sebelumnya selesai dikerjakan Proses Synchronous juga biasa disebut Blocking, karena harus menunggu tiap proses selesai, baru proses selanjutnya bisa dilakukan

**Contoh Synchronous**

<figure><img src="https://lh4.googleusercontent.com/hdc_2H5PzI0RvMvL06PUnbE5AovfO5mabiYSXTJn_QM1yzGshZS06aWElqJ_G1JQV7l1a8d6LL2XJDWq-aJ7tm_ZUzysY-n_5nEtg8HLLPgjLqVjxalfvwu_-0NyupC5wm1i1xO64oYoangYjvmINaAzyMVT7DihVvDQTBN2tT8wejotg8TkekrQoiYm" alt=""><figcaption></figcaption></figure>

### **Apa itu Asynchronous?**

Walaupun secara default proses di JavaScript dieksekusi secara Synchronous, namun kita bisa membuatnya menjadi Asynchronous. Berbeda dengan proses Synchronous, pada proses Asynchronous, JavaScript tidak akan <mark style="color:orange;">menunggu proses tersebut selesai</mark>, melainkan JavaScript akan melanjutkan baris selanjutnya, <mark style="color:orange;">tanpa harus menunggu</mark> proses Asynchronous selesai. Proses Asynchronous juga biasa disebut <mark style="color:orange;">Non-Blocking</mark>.

**Contoh Asynchronous**

<figure><img src="https://lh3.googleusercontent.com/wKOn524ftu2HluFfCJTEfA89Oe2e_ewBGbQtRppVI3Zg6rkeH4ok8xjePHE0gFqh9TsJhz7kyvTAjjNRVS-NZOgxSRNniOq0ZO700aaVBVHZ2IsmxrT0cDVX0OaF8Bd1aGThIyHLdC05ov8p2XYL2DfgW2Li76TerhPb2jd3zrTjkEgfGgYy76SOdPgE" alt=""><figcaption></figcaption></figure>


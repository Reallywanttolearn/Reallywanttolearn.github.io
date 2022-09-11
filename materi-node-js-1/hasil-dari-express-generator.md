# Hasil dari express generator

### Struktur folder

<figure><img src="../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

### package.json <a href="#package.json" id="package.json"></a>

<figure><img src="../.gitbook/assets/image (1) (3).png" alt=""><figcaption></figcaption></figure>

pada package.json terdapat keterangan dari aplikasi yang kita buat seperti <mark style="color:yellow;">Name,version,script dan dependencies</mark>



### cara kerja pada pattren express generator

sebenarnya npm start menjalankan file yang bernama <mark style="color:yellow;">www</mark> pada folder <mark style="color:yellow;">bin</mark>

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
yang mana jika kita perhatikan pada file <mark style="color:yellow;">www</mark> itu mengarah pada <mark style="color:yellow;">app.js</mark>&#x20;

<mark style="color:yellow;">app.js</mark> adalah entri point untuk menambahkan modul,middleware,route dll

file <mark style="color:yellow;">app.js</mark> membuat aplikasi express dengan membuat objek bernama <mark style="color:yellow;">app</mark>
{% endhint %}

#### di bawah ini contoh kode ketika kita membuat <mark style="color:red;">object app sekaligus mengexport object app</mark>

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

**maka yang terdapat pada file **<mark style="color:yellow;">**www**</mark>** sebenarnya berasal dari entri point yang sesungguhnya yaitu **<mark style="color:yellow;">**app.js**</mark>

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

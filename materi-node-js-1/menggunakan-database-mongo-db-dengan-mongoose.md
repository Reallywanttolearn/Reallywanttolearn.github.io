# Menggunakan database mongo db (dengan mongoose)

Table relasi yang akan kita gunakan

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

install mongoose

{% hint style="info" %}
```
npm install mongoose
```
{% endhint %}

Membuat koneksi mongodb

```javascript
//Import the mongoose module
const mongoose = require('mongoose');

//Set up default mongoose connection
const mongoDB = 'mongodb://127.0.0.1/my_database';
mongoose.connect(mongoDB, {useNewUrlParser: true, useUnifiedTopology: true});

//Get the default connection
const db = mongoose.connection;

//Bind connection to error event (to get notification of connection errors)
db.on('error', console.error.bind(console, 'MongoDB connection error:'));

```

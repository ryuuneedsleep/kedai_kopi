### Kopi Bintang

### https://ryuuneedsleep.github.io/kedai_kopi/index.html

### 1. Sebutkan satu bagian yang kamu susun dengan Flexbox dan satu bagian dengan Grid. Mengapa pilihan itu cocok untuk kedua bagian tersebut?

Saya menggunakan Flexbox pada bagian header untuk mengatur posisi nama kedai dan navigasi. Flexbox digunakan karena bisa mengatur posisi elemen secara horizontal dan juga vertikal. Jadi, pada layar desktop nama kedai berada di sebelah kiri dan navigasi di sebelah kanan sedangkan di layar smartphone dan tablet tersusun ke bawah.

Saya menggunakan Grid pada bagian daftar menu untuk mengatur card setiap menu. Grid digunakan untuk membagi card menjadi beberapa kolom sesuai ukuran layar. Pada ponsel menggunakan satu kolom, tablet dua kolom, dan desktop menjadi tiga kolom.

### 2. Ceritakan satu aturan CSS yang awalnya tidak berlaku. Apa yang kamu lihat di panel Styles, dan bagaimana kamu memperbaikinya?

Saya mengira bahwa box-sizing: border-box; tidak berfungsi. Awalnya saya pikir fungsinya adalah membuat box dan border secara otomatis. Saya juga sempat berpikir bahwa aturan tersebut harus menggunakan class box terlebih dahulu agar bisa berfungsi.

Ternyata hanya perlu diterapkan pada elemen yang sesuai dengan selectornya. Untuk memperbaikinya, saya memindahkan aturan tersebut ke selector universal menggunakan * { box-sizing: border-box; }. Jadi, aturan tersebut dapat diterapkan ke seluruh elemen HTML tanpa harus menambahkan class satu per satu.


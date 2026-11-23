
# Kopi Senja

Website sederhana kedai kopi yang dibuat menggunakan HTML5.

## Jawaban Praktikum

### 1. Apa yang muncul di address bar setelah form dikirim, dan mengapa data form tampil di sana?

Setelah formulir dikirim, data yang sudah dimasukkan akan muncul pada address bar dalam bentuk parameter URL. Hal ini terjadi karena formulir menggunakan method GET.

Method GET mengirimkan data melalui URL dengan menambahkan tanda tanya dan nama serta nilai dari setiap input. Pada percobaan saya yang muncul adalah "file:///D:/Coolyeah/Bootcamp/KedaiKopi/pesan.html?nama=Bintang&whatsapp=08811205636&menu=Chocolate+Milk&jumlah=2&cara_ambil=Ambil+di+tempat&catatan=Aku+yang+ganteng+ka"

Hal ini sesuai dengan materi HTTP pada Minggu 1, yaitu GET digunakan untuk meminta atau mengambil data melalui URL. Oleh karena itu, data formulir dapat terlihat pada address bar.

### 2. Pilih satu bagian halaman yang memakai element semantic. Mengapa memilih element tersebut dan bukan div?

Saya menggunakan element <main> untuk membungkus konten utama pada setiap halaman. Saya memilih element tersebut karena <main> secara khusus menunjukkan bagian utama dari sebuah halaman website.

Berbeda dengan <div> yang hanya berfungsi sebagai pembungkus umum tanpa makna khusus, <main> memiliki makna semantik sehingga membantu browser, mesin pencari, dan teknologi pembaca layar memahami struktur halaman dengan lebih baik.

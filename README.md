    # Praktikum 1
    Jawab Pertanyaan Berikut
    1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah _error_ ketika terjadi kesalahan penulis tag?
    2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
    3. Apa perbedaan atribut tittle dan alt pada tag <img>, berikan penjelasannya!
    4. Untuk mengatur ukuran gambar, digunakakan atribut width dan height. Agar tampilan gambar proposional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
    5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?

    Jawaban :
    1. Kalau tag ditulis salah (contoh <pp>), browser biasanya tidak protes, tapi tampilannya jadi tidak sesuai. Jadi bukan error merah kayak di codingan Python/Java, melainkan elemen itu diabaikan.
    2. <p> = bikin paragraf baru, ada jarak atas bawah. <br> = hanya ganti baris, tidak bikin paragraf baru.
    3. alt = teks cadangan kalau gambar rusak/gagal dimuat. title = teks info tambahan yang muncul kalau kursor diarahkan ke gambar.
    4. Kalau ingin gambar tetap proporsional Sebaiknya isi salah satu saja (width atau height). Kalau isi dua-duanya tapi tidak sesuai rasio, gambar bisa gepeng atau melebar.
    5. _blank → link dibuka di tab/jendela baru.
    _self → link dibuka di halaman/tab yang sama (default).
    _top → link dibuka di jendela penuh (keluar dari frame).
    _parent → link dibuka di frame induk (jika ada frameset).

    Kode : 
    <!DOCTYPE html>
    <html>
    <head>
    <title>Tag HTML Dasar</title>
    </head>
    <body>

    </body>
    <html>
    <h1>Belajar Dasar HTML</h1>
    <palign="center">Kami sedang belajar <mark>HTML Dasar</mark> dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
    <h2>Paragraf pada HTML</h2>
    <palign="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakana tag dasar html.</p>
    <h3>Menambahkan Gambar</h3>
    <img src="Logo_UPB.png" width="200" "Logo Universitas Pelita Bangsa">
    <nav>
    <a href="lab1_tag_dasar.html">Dasar Html</a>
    <a href="Lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
<img width="1917" height="925" alt="Cuplikan layar 2025-09-22 132549" src="https://github.com/user-attachments/assets/5a08d8c5-708f-4425-aae2-79c8d0c70e5d" />

    Input :
    <!DOCTYPE html>
    <html>
    <head>
    <title>Tag HTML Dasar</title>
    </head>
    <body>

    </body>
    <html>

    Output :
<img width="1060" height="414" alt="Cuplikan layar 2025-09-22 164926" src="https://github.com/user-attachments/assets/3e0fc221-9afd-4fcd-b14e-750568e6b813" />

    Input :
    1. Membuat Paragraf
    <palign="center">Kami sedang belajar HTML Dasar dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
    <palign="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakana tag dasar html.</p>
    Output :
 <img width="1919" height="324" alt="Cuplikan layar 2025-09-22 172409" src="https://github.com/user-attachments/assets/d9e8e8de-f036-4999-8edb-104ce34c247f" />
tml.</p>

    Penjelasan :
    Kode tersebut berfungsi untuk membuat paragraf di HTML. Tag <p> dipakai untuk menulis paragraf, sedangkan atribut align dipakai untuk mengatur posisi teks (tengah atau kanan). Kesalahan pada kode adalah penulisan <palign> yang seharusnya <p align>.

    Input :
    2. Menambahkan Judul 
    <h1>Belajar Dasar HTML</h1>
    <palign="center">Kami sedang belajar HTML Dasar dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
    <h2>Paragraf pada HTML</h2>
    <palign="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakana tag dasar html.</p>
    Output :
<img width="1919" height="466" alt="Cuplikan layar 2025-09-22 172647" src="https://github.com/user-attachments/assets/5ffec824-0541-4c9c-a539-99a6911285dd" />

    Penjelasan :
    Kode tersebut menambahkan judul dengan tag <h1> (judul utama) dan <h2> (subjudul). Untuk isi teks digunakan tag <p> sebagai paragraf. Namun ada kesalahan penulisan <palign> yang seharusnya <p align>. Atribut align berfungsi mengatur posisi teks, misalnya center di tengah dan right di kanan.
    
    Input :
    3. Memformat teks
    <h1>Belajar Dasar HTML</h1>
    <palign="center">Kami sedang belajar <mark>HTML Dasar</mark> dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangkamengenal
    tag-tag dasar HTML.</p>
    <h2>Paragraf pada HTML</h2>
    <palign="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf      dibuat
    dengan menggunakana tag dasar html.</p>
    Output :
<img width="1916" height="479" alt="Cuplikan layar 2025-09-22 173125" src="https://github.com/user-attachments/assets/ca89d4ab-3e2d-4ceb-ae68-cf3e6a3ef72a" />

    Penjelasan :
    Kode tersebut membuat judul dengan <h1> dan <h2>, lalu menampilkan teks dalam bentuk paragraf menggunakan <p>. Ada penggunaan <mark> untuk memberi highlight/penyorotan warna pada teks HTML Dasar. Kesalahan ada pada penulisan <palign>, yang seharusnya <p align> untuk mengatur posisi teks (center dan right).

    Input :
    4. Menyisipkan Gambar
    <h3>Menambahkan Gambar</h3>
    <img src="Logo_UPB.png" width="200" "Logo Universitas Pelita Bangsa">
    Output :
<img width="1919" height="767" alt="Cuplikan layar 2025-09-22 174300" src="https://github.com/user-attachments/assets/55c5f246-6c79-4523-90da-010b3964176e" />

    Penjelasan :
    Kode tersebut menambahkan judul kecil dengan <h3>, lalu menyisipkan gambar menggunakan tag <img>. Atribut src menunjuk ke file gambar (Logo_UPB.png), sedangkan width="200" mengatur ukuran lebar gambar. Namun ada kesalahan, seharusnya teks keterangan ditulis dengan atribut alt, bukan hanya "Logo Universitas Pelita Bangsa".

    Input :
    5. Menambahkan Hyperlink
    <nav>
    <a href="lab1_tag_dasar.html">Dasar Html</a>
    <a href="Lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
    Output :
<img width="1919" height="784" alt="Cuplikan layar 2025-09-22 174549" src="https://github.com/user-attachments/assets/ab18df31-c7bb-4cbd-9355-e3f844c5a492" />

    Penjelasan :
    Kode tersebut membuat menu navigasi dengan link ke halaman lokal dan eksternal menggunakan <a>, dibungkus <nav>, lalu diberi garis pemisah dengan <hr>.

    

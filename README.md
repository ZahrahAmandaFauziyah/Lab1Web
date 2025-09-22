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
    <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
    HTML.</p>
    <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
    tag dasar html.</p>
    Output : 
<img width="1919" height="297" alt="Cuplikan layar 2025-09-22 170203" src="https://github.com/user-attachments/assets/0660d649-2308-40b7-919a-d63634a870a7" />

    Input :
    

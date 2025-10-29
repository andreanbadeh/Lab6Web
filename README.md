# Praktikum 6 - Twitter Bootstrap

NAMA : ANDREAN PUTRA ARYA

NIM : 312410341

KELAS : TI.24.A.4


# Langkah-langkah Praktikum
Settup Bootstrap (Menggunakan CDN)
Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Praktikum 6 Bootstrap</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
        rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
        crossorigin="anonymous">
</head>
<body>
  <div class="container mt-5 text-center">
    <h1>Halo, Bootstrap!</h1>
    <button class="btn btn-primary mt-3">Ini Tombol Bootstrap</button>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
          crossorigin="anonymous"></script>
</body>
</html>
```

# 1. Container
.container: Memberikan lebar maksimum yang tetap yang berubah pada ukuran layar tertentu.

.container-fluid: Memberikan lebar penuh 100%


![gambar](https://github.com/andreanbadeh/Lab6Web/blob/058e49ce21220003bf65a190bf98404d1c6e0639/image/Screenshot%20from%202025-10-29%2018-39-44.png)

# 2. Grid System (Sistem Grid)
Membuat 3 kolom sama lebar yang di layout Praktikum4 11 harus menggunakan float: left12. Di Bootstrap.

Outputnya:

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/2f3e1bf4cdfd51ae7dc3e8962947ab9990b29d6d/image/Screenshot%20from%202025-10-29%2018-42-57.png)

Itu adalah Layout Praktikum4 yang sudah saya ubah ke Bootstrap.

# 3. Komponen: Button (Tombol)
Bootstrap menyediakan berbagai style tombol.

Code:
```
      <button class="btn btn-primary">Primary</button>
      <button class="btn btn-secondary">Secondary</button>
      <button class="btn btn-success">Success</button>
      <button class="btn btn-danger">Danger</button>
```

Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/770ba1f98ee3f9f6d9cb2c150a8ce44aeb890f18/image/Screenshot%20from%202025-10-29%2018-45-14.png)

# 4. Komponen: Navbar (Navigasi)
Membuat Navigasi responsive

Code:
```
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark mt-4">
    <div class="container">
      <a class="navbar-brand" href="#">Praktikum 6</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Artikel</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
```

Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/080a69fa41bee66cde18c9c282430d6d85e4467c/image/Screenshot%20from%202025-10-29%2018-48-29.png)

# 5. Komponen: Card (Kartu)
Card adalah container konten yang fleksibel.

Code:
```
<div class="container">
    <div class="card" style="width: 18rem;">
      <img src="image/andre.jpg"
           class="card-img-top" alt="Andre Logo">
      <div class="card-body">
        <h5 class="card-title">Judul Card</h5>
        <p class="card-text">Ini adalah deskripsi singkat di dalam card.</p>
        <a href="#" class="btn btn-primary">Lihat Detail</a>
      </div>
    </div>
  </div>
```
Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/824607d3567b7f9f5b00ce475d9dd54762157c52/image/Screenshot%20from%202025-10-29%2018-58-22.png)

# 6. Komponen: Form (Formulir)
Bootstrap men-style elemen form agar terlihat rapi dan konsisten.

Code:
```
<div class="container my-5">
    <h3>Hubungi Saya</h3>
    <form>
      <div class="mb-3">
        <label for="emailInput" class="form-label">Alamat Email</label>
        <input type="email" class="form-control" id="emailInput" placeholder="nama@contoh.com">
      </div>

      <div class="mb-3">
        <label for="pesanText" class="form-label">Pesan</label>
        <textarea class="form-control" id="pesanText" rows="3" placeholder="Tulis pesan kamu di sini..."></textarea>
      </div>

      <button type="submit" class="btn btn-primary">Kirim</button>
    </form>
  </div>
```

Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/cbcf40018b565ec0e68afb1327423eb9f1394856/image/Screenshot%20from%202025-10-29%2019-01-38.png)

# Pertanyaan dan Tugas
# 1. Refactor Layout Praktikum 4
Ambil layout web sederhana dari Praktikum4. Buat ulang layout tersebut menggunakan Bootstrap Grid System.

Gunakan <nav> Bootstrap untuk bagian navigasi:
```
    <nav class="navbar navbar-expand-lg navbar-light bg-light rounded mb-4">
      <div class="container-fluid">
        <a class="navbar-brand fw-bold" href="#">MySite</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link active" href="home.html">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="artikel.html">Artikel</a></li>
            <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
            <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>
```

Gunakan class .row dan .col-md-8 untuk _main content_ dan .col-md-4 untuk sidebar:
```
<section id="main" class="col-md-8"
```
```
      <aside class="col-lg-4">
        <div class="card mb-4">
          <div class="card-header bg-primary text-white">Widget Header</div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
          </ul>
        </div>

        <div class="card">
          <div class="card-header bg-success text-white">Widget Text</div>
          <div class="card-body">
            <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis.</p>
          </div>
        </div>
      </aside>
```

Gunakan komponen .card Bootstrap:
```
<section class="col-lg-8">
        <div class="row text-center mb-4">
          <div class="col-md-4">
            <div class="card h-100">
              <img src="https://dummyimage.com/120/db7d25/fff.png" class="card-img-top rounded-circle mx-auto mt-3" style="width:120px;">
              <div class="card-body">
                <h5 class="card-title">Heading</h5>
                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-outline-primary">View detail</a>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card h-100">
              <img src="https://dummyimage.com/120/3e73e6/fff.png" class="card-img-top rounded-circle mx-auto mt-3" style="width:120px;">
              <div class="card-body">
                <h5 class="card-title">Heading</h5>
                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-outline-primary">View detail</a>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card h-100">
              <img src="https://dummyimage.com/120/71e6d4/fff.png" class="card-img-top rounded-circle mx-auto mt-3" style="width:120px;">
              <div class="card-body">
                <h5 class="card-title">Heading</h5>
                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-outline-primary">View detail</a>
              </div>
            </div>
          </div>
        </div>
```

Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/aed4b08fa28b2d23da20ab23d5fbabe630ca5621/image/Screenshot%20from%202025-10-29%2019-14-10.png)

# 2. Refactor Form Praktikum 5
Ambil salah satu form dari Praktikum5 (misalnya Form Input 23 atau Form Button 24).

Buat ulang form tersebut agar terlihat rapi menggunakan class-class form Bootstrap (.form-control, .form-label, .btn).

Disini saya menggunakan Form Input :

Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Genap Ganjil - Bootstrap</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <script>
    function test() {
      var val1 = document.getElementById("bilangan").value;
      var hasil = (val1 % 2 == 0) ? "Bilangan Genap" : "Bilangan Ganjil";
      document.getElementById("hasil").value = hasil;
    }
  </script>
</head>
<body class="bg-light">

  <div class="container mt-5">
    <div class="card shadow-sm mx-auto" style="max-width: 500px;">
      <div class="card-header bg-primary text-white text-center">
        <h4>Cek Bilangan Genap atau Ganjil</h4>
      </div>
      <div class="card-body">
        <form name="kirim" onsubmit="return false;">
          
          <div class="mb-3">
            <label for="bilangan" class="form-label">Masukkan Bilangan</label>
            <input type="number" class="form-control" id="bilangan" name="T1" placeholder="Contoh: 12">
          </div>

          <div class="mb-3">
            <label for="hasil" class="form-label">Hasil</label>
            <input type="text" class="form-control" id="hasil" name="T2" readonly>
          </div>

          <div class="text-center">
            <button type="button" class="btn btn-success px-4" onclick="test()">Tebak</button>
          </div>
        </form>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/23af1566a90e22101124d229be0450813a468d1c/image/Screenshot%20from%202025-10-29%2019-16-29.png)

# 3. Tugas: Buat Halaman Portofolio Sederhana
Buat satu halaman HTML baru (portofolio.html) menggunakan Bootstrap yang berisi:

a. Sebuah Navbar di bagian atas:
```
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand" href="#">Portfolio Saya</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#tentang">Tentang Saya</a></li>
          <li class="nav-item"><a class="nav-link" href="#keahlian">Keahlian Saya</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>
```

b. Sebuah section "Tentang Saya" di dalam .container dengan 1 baris (.row) dan 3 kolom (.col-md-4):
```
<section id="tentang" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Tentang Saya</h2>
      <div class="row align-items-center">
```

kolom kiri (.col-md-4) berisi foto Anda (gunakan <img> dengan class .img-fluid).
```
<div class="col-md-4 text-center">
          <img src="image/fotoandre.jpg" class="img-fluid rounded-circle shadow-sm" alt="Foto Saya">
        </div>
```

Kolom kanan (.col-md-8) berisi nama dan deskripsi diri Anda.
```
<div class="col-md-8">
          <h3>ANDREAN PUTRA ARYA</h3>
          <p class="text-muted">
            Saya adalah mahasiswa yang memiliki ketertarikan di bidang teknologi dan pengembangan web. 
            Saya fokus dalam membangun tampilan antarmuka yang menarik dan efisien menggunakan HTML, CSS, Bootstrap, dan JavaScript.
          </p>
          <p>
            Saya juga mempelajari backend development menggunakan PHP dan MySQL agar dapat membuat aplikasi web yang dinamis dan terintegrasi dengan basis data.
          </p>
        </div>
      </div>
    </div>
  </section>
```

c. Sebuah section "Portofolio Saya" di dalam .container dengan 1 baris (.row) dan 3 kolom (.col-md-4):

Setiap kolom berisi satu komponen .card yang merepresentasikan satu proyek (beri gambar dummy dan deskripsi singkat).
```
<section id="keahlian" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">Keahlian Saya</h2>
      <div class="row g-4">
        
        <div class="col-md-4">
          <div class="card h-100 shadow-sm text-center">
            <img src="image/htmlcss.webp" class="card-img-top" alt="HTML & CSS">
            <div class="card-body">
              <h5 class="card-title">HTML & CSS</h5>
              <p class="card-text">Menguasai struktur HTML, styling CSS, dan pembuatan layout responsif dengan Bootstrap.</p>
              <div class="progress" style="height: 15px;">
                <div class="progress-bar bg-primary" style="width: 90%;">90%</div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card h-100 shadow-sm text-center">
            <img src="image/js.png" class="card-img-top" alt="JavaScript">
            <div class="card-body">
              <h5 class="card-title">JavaScript</h5>
              <p class="card-text">Mampu membuat interaksi dinamis dan memanipulasi DOM untuk meningkatkan user experience.</p>
              <div class="progress" style="height: 15px;">
                <div class="progress-bar bg-success" style="width: 80%;">80%</div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card h-100 shadow-sm text-center">
            <img src="image/phpsql.png" class="card-img-top" alt="PHP & MySQL">
            <div class="card-body">
              <h5 class="card-title">PHP & MySQL</h5>
              <p class="card-text">Dapat membuat aplikasi web dinamis dan mengelola database menggunakan PHP & MySQL.</p>
              <div class="progress" style="height: 15px;">
                <div class="progress-bar bg-warning text-dark" style="width: 75%;">75%</div>
              </div>
            </div>
          </div>
        </div>
```

Outputnya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/e91d298e967fc107ff57a6f9dc34e64710fc6d24/image/Screenshot%20from%202025-10-29%2019-40-11.png)

Menu keahlian saya :

![gambar](https://github.com/andreanbadeh/Lab6Web/blob/e91d298e967fc107ff57a6f9dc34e64710fc6d24/image/Screenshot%20from%202025-10-29%2019-40-32.png)

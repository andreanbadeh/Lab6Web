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

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/510de04d5c4290da3e76b39ae0fd030f1841f17f/gambar%203.png)

Outputnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/510de04d5c4290da3e76b39ae0fd030f1841f17f/output%203.png)

# 4. Komponen: Navbar (Navigasi)
Membuat Navigasi responsive

Code:

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/510de04d5c4290da3e76b39ae0fd030f1841f17f/gambar%204.png)

Outputnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/510de04d5c4290da3e76b39ae0fd030f1841f17f/output%204.png)

# 5. Komponen: Card (Kartu)
Card adalah container konten yang fleksibel.

Code:

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/gambar%205.png?raw=true)

Outputnya :

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/output%205.png?raw=true)

# 6. Komponen: Form (Formulir)
Bootstrap men-style elemen form agar terlihat rapi dan konsisten.

Code:

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/gambar%206.png?raw=true)

Outputnya :

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/output%206.png?raw=true)

# Pertanyaan dan Tugas
# 1. Refactor Layout Praktikum 4
Ambil layout web sederhana dari Praktikum4. Buat ulang layout tersebut menggunakan Bootstrap Grid System.

Gunakan <nav> Bootstrap untuk bagian navigasi:

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/tugas%201.png?raw=true)

Gunakan class .row dan .col-md-8 untuk _main content_ dan .col-md-4 untuk sidebar:

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/tugas%201.1.png?raw=true)


![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/tugas%201.2.png?raw=true)

Gunakan komponen .card Bootstrap:

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/tugas%201.3.png?raw=true)

Outputnya :

![gambar](https://github.com/M-Rakha/Lab6Web/blob/main/output%20tugas%201.png?raw=true)

# 2. Refactor Form Praktikum 5
Ambil salah satu form dari Praktikum5 (misalnya Form Input 23 atau Form Button 24).

Buat ulang form tersebut agar terlihat rapi menggunakan class-class form Bootstrap (.form-control, .form-label, .btn).

Disini saya menggunakan Form Input :

Code:

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/tugas%202.png)

Outputnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/output%20tugas%202.png)

# 3. Tugas: Buat Halaman Portofolio Sederhana
Buat satu halaman HTML baru (portofolio.html) menggunakan Bootstrap yang berisi:

a. Sebuah Navbar di bagian atas:

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/tugas%203.png)

b. Sebuah section "Tentang Saya" di dalam .container dengan 1 baris (.row) dan 3 kolom (.col-md-4):

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/tugas%203.1.png)

kolom kiri (.col-md-4) berisi foto Anda (gunakan <img> dengan class .img-fluid).

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/tugas%203.2.png)

Kolom kanan (.col-md-8) berisi nama dan deskripsi diri Anda.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/tugas%203.3.png)

c. Sebuah section "Portofolio Saya" di dalam .container dengan 1 baris (.row) dan 3 kolom (.col-md-4):

Setiap kolom berisi satu komponen .card yang merepresentasikan satu proyek (beri gambar dummy dan deskripsi singkat).

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/tugas%203.4.png)

Outputnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/output%20tugas%203.png)

Menu keahlian saya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab6Web/34707919f8ea75f1c1f428183c90b15e0c118210/output%20tugas%203.1.png)

## 👤 Laporan Praktikum Desain Web
* **Nama**: Adelita Daeli
* **NPM**: 4525210049
* **Program Studi**: Teknik Informatika

# Form Pendaftaran Kursus & Landing Page

Proyek web sederhana berupa **Form Pendaftaran Kursus** yang dibangun menggunakan **HTML5** dan **CSS3** murni. Proyek ini dirancang dengan menerapkan konsep *Box Model*, penggunaan variabel CSS (`:root`), serta desain responsif menggunakan *Media Queries*.

---

## 🚀 Fitur Utama
* **5 Tipe Input**: Text (Nama), Email, Password, Number (Nilai), dan Date (Tanggal Lahir).
* **3 Jenis Button**: Submit (`.btn-primary`), Reset (`.btn-reset`), dan Button Kustom (`.btn-secondary`).
* **Desain Responsif**: Dilengkapi *media query* untuk penyesuaian tata letak otomatis pada perangkat mobile dan desktop.
* **Validasi HTML5**: Menggunakan atribut wajib seperti `required`, `min`, `max`, dan `placeholder`.

---

# Ringkasan Proyek: Form Pendaftaran Mahasiswa Baru

## 1. Latar Belakang & Perubahan
Proyek ini dikembangkan untuk memenuhi kebutuhan prototipe *Form Pendaftaran Mahasiswa Baru* yang dirancang secara profesional agar siap diintegrasikan dengan sistem *backend*. Perubahan utama mencakup penambahan dan penyesuaian elemen input minimum yang meliputi nama, email, password, nilai ujian, serta tanggal lahir. Setiap elemen input telah dilengkapi dengan atribut `id`, `name`, serta label semantik yang terhubung secara akurat.

## 2. Masalah Utama
Pada tahap awal pengembangan, beberapa kendala yang dihadapi meliputi:
* Belum optimalnya keterhubungan elemen *label* dengan atribut input yang memengaruhi aksesibilitas.
* Tampilan antarmuka yang kurang responsif dan berpotensi berantakan ketika diakses melalui perangkat layar kecil atau ponsel.
* Kurangnya validasi sisi klien sebelum data formulir diproses lebih lanjut oleh sistem *backend*.

## 3. Solusi yang Diterapkan
Untuk mengatasi masalah tersebut, solusi yang diimplementasikan meliputi:
* Restrukturisasi kode HTML dengan menyematkan atribut `required`, `id`, dan `name` secara konsisten pada setiap *field*.
* Penerapan desain berbasis *box model* dan variabel global CSS (`:root`) guna menjaga konsistensi estetika.
* Penambahan aturan *media query* (di bawah 600px) agar tata letak tombol dan kontainer formulir dapat menyesuaikan secara otomatis pada perangkat seluler.

---

## 💻 Dokumentasi Tampilan

Berikut adalah dokumentasi antarmuka (UI) dari aplikasi pada berbagai ukuran layar:

### 1. Tampilan Desktop
*Tampilan antarmuka saat diakses melalui layar komputer atau laptop (lebar > 600px/768px):*
![Tampilan Desktop](img/desktop-view.png)

### 2. Tampilan Mobile
*Tampilan antarmuka saat diakses melalui perangkat seluler/smartphone (menyesuaikan secara responsif):*

![Tampilan Mobile](img/mobile-view.png)

---

## 🛠️ Teknologi yang Digunakan
* **HTML5** (Struktur markup semantik)
* **CSS3** (Styling, Flexbox, Box Model, CSS Variables)
* **Visual Studio Code** (Code Editor)
* **Browser** (Google Chrome / Mozilla Firefox)

---

## ⚙️ Cara Menjalankan Proyek
1. Clone repository ini atau unduh folder proyek dalam bentuk ZIP.
2. Pastikan file `index.html` dan `style.css` berada di dalam satu direktori/folder yang sama.
3. Klik dua kali pada file `index.html` atau buka menggunakan browser pilihan Anda.
4. Form siap diuji coba!

---

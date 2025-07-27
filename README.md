# Website Startup Tax Digital

Proyek ini dikembangkan pada Semester 4 sebagai bagian dari program PBL (Project Based Learning), dengan tujuan membangun platform digital perpajakan modern. Website ini membantu pengguna dalam mengakses informasi perpajakan, mengajukan pajak secara online, serta menyediakan layanan konsultasi secara interaktif.

## Fitur Utama
- **Pengajuan Pajak Online**: Pengguna dapat mengisi dan mengirim formulir pengajuan pajak secara mandiri.
- **Informasi Perpajakan**: Artikel dan referensi resmi seputar peraturan pajak terkini.
- **Tentang Kami**: Menampilkan informasi startup, tim pengembang, dan latar belakang proyek.
- **Formulir Konsultasi Interaktif**: Pengguna dapat berkonsultasi langsung melalui formulir dengan notifikasi otomatis ke admin.

## Status Proyek
⏳ **80% selesai** — Pihak kedua menerima hasil PBL *Website Startup Tax Digital* dengan progress 80%.  
Keterlambatan disebabkan oleh:
- Kompleksitas fitur tambahan
- Keterbatasan sumber daya tim
- Uji coba tambahan yang dibutuhkan
- Kendala teknis yang tidak terduga

## Teknologi yang Digunakan
- Laravel (PHP Framework)
- HTML, CSS, JavaScript
- Bootstrap
- MySQL
- AJAX & Validasi Form Dinamis

## Instalasi Lokal
1. Clone repo ini:
   ```bash
   git clone https://github.com/Manase-20/website-tax-digital-startup.git
2. Jalankan:
   cd website-tax-digital-startup
    composer install
    cp .env.example .env
    php artisan key:generate
3. Buat database dan sesuaikan .env
4. Jalankan migrasi:
   php artisan migrate
   php artisan serve
5. Akses website di http://localhost:8000

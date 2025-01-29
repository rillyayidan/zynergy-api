Selamat datang di repositori Zynergy. Proyek ini adalah aplikasi berbasis Laravel yang bertujuan untuk membantu pengguna mengelola kesehatan mereka melalui fitur-fitur seperti pengingat makan, tidur, aktivitas ringan, dan pemeriksaan kesehatan rutin, serta memberikan rekomendasi makanan dan artikel kesehatan sesuai dengan kondisi pengguna.

Fitur Utama
Pengingat Kesehatan:

Pengingat waktu makan dengan menu sehat.
Pengingat kualitas tidur dengan notifikasi waktu tidur dan alarm bangun.
Pengingat aktivitas ringan seperti peregangan, berdiri, dan berjalan.
Pengingat untuk pemeriksaan kesehatan rutin.
Rekomendasi Personalisasi:

Sugesti makanan berdasarkan alergi, penyakit, dan minat pengguna.
Artikel kesehatan yang relevan dengan kondisi dan minat pengguna.
Manajemen Data Pengguna:

Pilihan minat, penyakit, dan alergi.
Verifikasi email saat registrasi.
Teknologi yang Digunakan
Framework: Laravel 10
Database: MySQL
Front-End: Blade Templates
Deployment API: ArenHost
Tools Pengembangan: Laragon, Composer
Instalasi
Persyaratan Minimum
PHP >= 8.1
Composer
MySQL
Langkah Instalasi
Clone repositori ini: bash git clone https://github.com/username/repo-health-care.git cd repo-health-care

Install dependensi Laravel: bash composer install

Salin file .env.example menjadi .env: bash cp .env.example .env

Konfigurasi file .env sesuai dengan environment Anda (database, mail, dll).

Generate application key: bash php artisan key:generate

Migrasi dan seed database: bash php artisan migrate --seed

Jalankan server pengembangan: bash php artisan serve

Penggunaan
API

Endpoint utama dapat diakses melalui api.php. Contoh endpoint login: /api/login
Dokumentasi API akan segera ditambahkan.
Aplikasi Mobile

API siap untuk diintegrasikan dengan aplikasi mobile menggunakan framework seperti Flutter atau React Native.
Struktur Database
Tables:
users: Data pengguna.
interests: Daftar minat yang tersedia.
diseases: Daftar penyakit yang tersedia.
allergies: Daftar alergi yang tersedia.
reminders: Data pengingat yang dibuat pengguna.
Kontribusi
Kontribusi sangat dihargai! Untuk kontribusi:

Fork repositori ini.

Buat branch baru untuk fitur/bugfix: bash git checkout -b fitur-baru

Commit perubahan Anda: bash git commit -m "Menambahkan fitur baru"

Push branch Anda: bash git push origin fitur-baru

Ajukan pull request.

Lisensi
Proyek ini dilisensikan di bawah [Zynergy].

Jika ada pertanyaan atau masalah, silakan buat issue di GitHub atau hubungi kami melalui email di zynergy.app@gmail.com.

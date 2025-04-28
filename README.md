# Bimo CRM

Bimo CRM adalah sistem manajemen hubungan pelanggan (Customer Relationship Management) yang dirancang untuk perusahaan penyedia layanan internet dan telekomunikasi. Aplikasi ini menyediakan fitur lengkap untuk mengelola leads, penawaran, langganan, dan komunikasi dengan pelanggan.

![Bimo CRM Dashboard](https://via.placeholder.com/1200x600/e1e1e1/808080?text=Bimo+CRM+Dashboard)

## Fitur Utama

-   **Manajemen Lead**: Lacak dan kelola semua prospek potensial dengan mudah
-   **Penawaran Produk**: Buat dan kelola penawaran produk untuk leads
-   **Manajemen Langganan**: Kelola siklus hidup langganan dari awal hingga perpanjangan
-   **Produk & Harga**: Kelola katalog produk dengan berbagai paket harga
-   **Pengelolaan Pengguna**: Sistem peran dan izin yang komprehensif
-   **Notifikasi**: Pemberitahuan otomatis untuk aktivitas penting
-   **Activity Logging**: Lacak semua aktivitas untuk audit dan analisis

## Teknologi

-   **Backend**: Laravel 10
-   **Frontend**: React.js dengan Inertia.js
-   **UI Components**: Shadcn UI
-   **Database**: MySQL
-   **Authentication**: Laravel Fortify
-   **Authorization**: Laravel Permissions (Spatie)

## Persyaratan Sistem

-   PHP 8.2 atau lebih tinggi
-   Node.js 18 atau lebih tinggi
-   MySQL 8.0 atau lebih tinggi
-   Composer
-   npm atau yarn

## Instalasi

### Menggunakan Git

1. Clone repositori ini

    ```bash
    git clone https://github.com/Biyuraaa/bimo_crm.git
    cd bimo_crm

    ```

2. Instal dependencies PHP
    ```bash
    composer install
    ```
3. Instal dependencies JavaScript
    ```bash
    npm install
    # atau
    yarn install
    ```
4. Salin file `.env.example` ke `.env` dan sesuaikan konfigurasi database
    ```bash
    cp .env.example .env
    ```
5. Generate kunci aplikasi
    ```bash
    php artisan key:generate
    ```
6. Konfigurasi database di file .env
    ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=bimo_crm
    DB_USERNAME=root
    DB_PASSWORD=
    ```
7. Jalankan database migrations dan seeder
    ```bash
    php artisan migrate --seed
    ```
8. Compile assets
    ```bash
    npm run dev
    # atau untuk production
    npm run build
    ```
9. Jalankan aplikasi
    ```bash
    php artisan serve
    ```
10. Akses aplikasi di `http://localhost:8000`

## Pengguna Default

### Setelah menginstal aplikasi, Anda dapat login dengan pengguna default berikut:

-   **Administrator**
    -   Email: `admin@smart.com'
    -   Password: `password`
-   **Sales**
    -   Email: `sales@smart.com'
    -   Password: `password`
-   **Manager**
    -   Email: `manager@smart.com'
    -   Password: `password`

## Role dan Izin

-   **Administrator**: Akses penuh ke semua fitur
-   **Sales**: Akses terbatas untuk mengelola leads dan penawaran
-   **Manager**: Akses untuk mengelola langganan dan laporan

## Panduan Pengguna

-   **Mengelola Leads**

    -   Navigasi ke menu Leads di sidebar
    -   Gunakan tombol Add Lead untuk menambahkan lead baru
    -   Klik pada lead untuk melihat detail atau mengedit informasi

-   **Membuat Penawaran**

    -   Buka halaman detail lead
    -   Klik tombol Create Offer
    -   Pilih produk dan paket harga yang ingin ditawarkan
    -   Atur detail kontrak seperti durasi dan perpanjangan otomatis
    -   Klik Create Offer untuk menyelesaikan

-   **Mengelola Langganan**
    -   Navigasi ke menu Subscriptions
    -   Lihat semua langganan aktif, menunggu persetujuan, atau berakhir
    -   Klik pada langganan untuk melihat detail atau melakukan tindakan

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan ikuti langkah-langkah berikut:

1. Fork repositori ini
2. Buat branch baru untuk fitur atau perbaikan Anda
3. Lakukan perubahan dan commit
4. Push ke branch Anda
5. Buat pull request

## Lisensi

Proyek ini dilisensikan di bawah MIT License. Silakan lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.

## Kontak

Jika Anda memiliki pertanyaan atau umpan balik, silakan hubungi kami di:

-   Email: m.bimo.bayu.bagaskara-2022@fst.unair.ac.id
-   GitHub: [Biyuraaa](github.com/Biyuraaa)

## Catatan

-   Proyek ini masih dalam tahap pengembangan. Fitur dan fungsionalitas dapat berubah seiring waktu.
-   Untuk laporan bug atau masalah, silakan buka isu di repositori GitHub.

## Terima Kasih

Terima kasih telah menggunakan Bimo CRM. Kami berharap aplikasi ini membantu Anda dalam mengelola hubungan pelanggan dengan lebih baik.

```


```

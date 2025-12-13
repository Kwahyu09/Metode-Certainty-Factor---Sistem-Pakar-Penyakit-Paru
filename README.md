# Metode Certainty Factor - Sistem Pakar Penyakit Paru

## Tech Stack

Project ini menggunakan teknologi berikut:

-   **Laravel 12** - Framework PHP monolite
-   **MySQL** - Database management system

## Tim Pengembang

-   **Krisna Wahyudi** - Fullstack Developer

## Instalasi

Untuk menjalankan proyek ini secara lokal sebagai berikut :

1. **Clone repositor**
    - Clone project dari repository dengan menggunakan perintah berikut:
    ```bash
    git clone https://github.com/Kwahyu09/Metode-Certainty-Factor---Sistem-Pakar-Penyakit-Paru.git
    cd metode-certain.. (nama repositori)~
    ```
2. **Install Composer Dependencies**

    - Jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:
        ```bash
        composer install
        ```

3. **Copy dan Paste File .env**

    - Salin semua data dari file `.env.example` dan tempelkan di file `.env`:
        ```bash
        cp .env.example .env
        ```

4. **Generate Project Key**

    - Jalankan perintah berikut untuk menghasilkan kunci proyek:
        ```bash
        php artisan key:generate
        ```

5. Migrasi database:
    ```bash
    php artisan migrate --seed
    ```
6. Akses aplikasi melalui browser di `http://localhost`.

## Kontribusi

Silakan buat pull request jika ingin berkontribusi atau membuka issue jika menemukan masalah.

## Thank You

and lets build great apps!

# Learn ReactJS & Express

Ini adalah proyek contoh yang menggabungkan ReactJS sebagai front-end dan Express sebagai back-end. Proyek ini dirancang untuk membantu Anda mempelajari cara membangun aplikasi web full-stack menggunakan teknologi-teknologi tersebut.

## Pendahuluan

Proyek ini mencakup dua bagian utama:
1. **ReactJS Front-end**: Dibangun dengan ReactJS, sebuah library JavaScript untuk membangun antarmuka pengguna.
2. **Express Back-end**: Dibangun dengan Express, sebuah framework untuk Node.js yang memudahkan pembuatan aplikasi web dan API.

## Prasyarat

Sebelum memulai, pastikan Anda telah menginstal perangkat-perangkat lunak berikut:
- [Node.js](https://nodejs.org/) (termasuk npm)
- [Git](https://git-scm.com/)

## Instalasi

Ikuti langkah-langkah di bawah ini untuk mengatur proyek di komputer Anda:

1. **Kloning repositori ini**

   ```bash
   git clone https://github.com/username/learn-reactjs-express.git
   cd learn-reactjs-express
2. **Instal dependensi untuk front-end dan back-end**
   ```bash
   # Masuk ke direktori back-end dan instal dependensi
   cd backend
   npm install
   
   # Kembali ke root dan masuk ke direktori front-end, lalu instal dependensi
   cd ../frontend
   npm install
# Menjalankan Aplikasi
Setelah menginstal semua dependensi, Anda bisa menjalankan aplikasi dengan dua perintah berikut di terminal yang terpisah:

##Menjalankan server Express

   ```bash
   #Copy code
   cd backend
   npm start
   # Server Express akan berjalan di http://localhost:5000


**Berikut adalah struktur direktori proyek ini:**
   ```bash
   Copy code
   learn-reactjs-express/
   │
   │── node_modules/ # Direktori untuk dependensi Node.js
   │── src/          # Direktori untuk source code
   │── .env          # File konfigurasi environment
   └── package.json  # File konfigurasi npm
   │
   ├── frontend-react/         # Direktori untuk kode front-end (React)
   │   ├── node_modules/ # Direktori untuk dependensi Node.js
   │   ├── public/       # Direktori untuk file statis
   │   ├── src/          # Direktori untuk source code
   │   └── package.json  # File konfigurasi npm
   │
   └── README.md         # File README ini




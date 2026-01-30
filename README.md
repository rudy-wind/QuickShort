# 🔗 QuickShort – Premium URL Shortener

QuickShort adalah aplikasi web pemendek URL modern dengan antarmuka premium yang memungkinkan pengguna memangkas tautan panjang secara instan menggunakan infrastruktur API Bitly, tanpa perlu registrasi akun oleh pengguna akhir.

## Fitur Utama

- **Premium UI/UX**  
  Desain modern berbasis Tailwind CSS dengan efek glassmorphism dan animasi halus.

- **Tanpa Akun Bitly**  
  Pengguna tidak perlu memiliki akun Bitly sendiri. Aplikasi menggunakan integrasi API sistem yang telah dikonfigurasi.

- **Riwayat Sesi**  
  Menyimpan daftar tautan yang baru saja dipangkas menggunakan `localStorage` browser.

- **Mobile Optimized**  
  Navigasi off-canvas (side drawer) yang responsif untuk pengalaman mobile optimal.

- **Salin Sekali Klik**  
  Fitur copy-to-clipboard untuk berbagi tautan dengan cepat.

- **Keamanan Bitly**  
  Semua tautan diproses melalui infrastruktur Bitly yang aman dan terpercaya.

## Teknologi yang Digunakan

- **Frontend**: HTML5, Tailwind CSS, JavaScript (Vanilla ES6+)  
- **Icons**: Font Awesome 6  
- **Typography**: Plus Jakarta Sans (Google Fonts)  
- **API**: Bitly API v4  
- **Storage**: Browser LocalStorage  

## Instalasi & Persiapan

### 1. Clone repositori
```bash
git clone https://github.com/rudy-wind/QuickShort.git
````

### 2. Jalankan aplikasi

Buka berkas `index.html` langsung di browser, atau gunakan ekstensi **Live Server** di VS Code.

### 3. Konfigurasi API Key

Buka `index.html`, cari variabel berikut, lalu masukkan Bitly Generic Access Token Anda:

```js
const API_TOKEN = 'MASUKKAN_TOKEN_BITLY_ANDA_DI_SINI';
```

##  Cara Penggunaan

1. **Tempel URL**
   Masukkan tautan panjang ke kolom input utama.

2. **Shorten**
   Klik tombol **Persingkat Sekarang** atau tekan `Enter`.

3. **Copy**
   Klik tombol **Salin** untuk menyalin URL pendek.

4. **History**
   Riwayat tautan tersedia di bagian **Riwayat Sesi**.

##  Struktur Proyek

```
├── index.html      # File utama (HTML, CSS, dan JavaScript)
└── README.md       # Dokumentasi proyek
```

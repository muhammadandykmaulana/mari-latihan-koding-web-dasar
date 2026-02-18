# Panduan Instalasi & Pengerjaan Workshop Mari Latihan Koding Web Dasar

## Dokumen ini berisi langkah-langkah persiapan lingkungan dan instruksi pengerjaan untuk latihan dasar HTML, JavaScript, dan Node.js.

## Persiapan Lingkungan

Ikuti langkah-langkah berikut untuk menginisialisasi proyek:

### 1\. Instalasi Node.js

Pastikan Node.js dan npm telah terinstal. Disarankan menggunakan versi 16 atau yang lebih baru (v22 terkonfirmasi stabil).

```
# Cek versi yang terinstal
node -v
npm -v
git -v
```

### 2\. Clone Repository & Install Dependencies

Clone proyek dan instal semua package yang diperlukan:

```
git clone [https://github.com/taufikiqbalr/keamanan-aplikasi-web-tugas-1.git](https://github.com/taufikiqbalr/keamanan-aplikasi-web-tugas-1.git)
cd keamanan-aplikasi-web-tugas-1
npm install
```

### 3\. Install Workshop Tools (Global)

Instal alat bantu latihan secara global untuk menjalankan workshop interaktif di terminal:

```
npm install -g learnyouhtml javascripting learnyounode
```

### 4\. Linting (Opsional)

Gunakan StandardJS untuk memastikan gaya penulisan kode rapi:

```
# Mengecek gaya kode
npm run lint

# Memperbaiki gaya kode secara otomatis
npm run lint-fix
```

## Struktur Proyek

Latihan dikerjakan di dalam direktori `src/` dengan pembagian sebagai berikut:

```
keamanan-aplikasi-web-tugas-1/
├── src/
│   ├── learnyouhtml/     # Latihan dasar HTML (index.html, tags, dll)
│   ├── javascripting/    # Latihan dasar JavaScript (variables, loops, dll)
│   └── learnyounode/     # Latihan backend Node.js (IO, HTTP client, dll)
├── test/                 # File pengujian
├── package.json          # Konfigurasi npm
└── README.md
```

## Instruksi Pengerjaan Latihan

Berikut adalah alur kerja untuk setiap modul latihan.

### 1\. Latihan HTML (`learnyouhtml`)

1.  **Masuk ke direktori:**
    
    ```
    cd src/learnyouhtml
    ```
    
2.  **Mulai workshop:** Jalankan perintah `learnyouhtml` di terminal.
    
3.  **Pilih Tantangan:** Pilih menu latihan (contoh: `HELLO WORLD`, `TAGS`, dll).
    
4.  **Edit File:** Buat/Edit file `.html` (misal: `index.html`) sesuai instruksi soal.
    
5.  **Verifikasi Jawaban:**
    
    ```
    learnyouhtml verify index.html
    ```
    

### 2\. Latihan JavaScript (`javascripting`)

1.  **Masuk ke direktori:**
    
    ```
    cd src/javascripting
    ```
    
2.  **Mulai workshop:** Jalankan perintah `javascripting` di terminal.
    
3.  **Pilih Tantangan:** Pilih menu latihan (contoh: `INTRODUCTION`, `VARIABLES`).
    
4.  **Edit File:** Edit file `.js` sesuai instruksi (misal: `introduction.js`).
    
5.  **Verifikasi Jawaban:**
    
    ```
    javascripting verify introduction.js
    ```
    

### 3\. Latihan Node.js (`learnyounode`)

1.  **Masuk ke direktori:** 
    ```
    cd src/learnyounode
    ``` 
2.  **Mulai workshop:** Jalankan perintah `learnyounode` di terminal.
3.  **Pilih Tantangan:** Pilih menu latihan (contoh: `BABY STEPS`, `MY FIRST I/O!`).
4.  **Edit File:** Edit file `.js` sesuai instruksi (misal: `baby-steps.js`).
5.  **Verifikasi Jawaban:**
    ```
    learnyounode verify baby-steps.js
    ```
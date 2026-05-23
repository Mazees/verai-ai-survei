# VERA AI - Landing Page & Survei Riset UI/UX

Repositori ini berisi kode sumber landing page untuk memperkenalkan produk **VERA AI** yang digunakan dalam survei riset pengguna untuk memenuhi tugas matakuliah **Desain Antarmuka (D081)**.

---

## 👥 Informasi Kelompok

**KELOMPOK 2 (Desain Antarmuka D081):**
*   **Arjuna Sandya Raissa Naryama** - (24081010119)
*   **Muhammad Fakhri Anshary Yusaf** - (24081010124)
*   **Mada Putra Adhadriyanto** - (24081010192)

---

## 💡 Tentang VERA AI
VERA AI adalah sebuah produk SaaS kasir berbasis kecerdasan buatan terintegrasi, di mana pelayanan transaksi dilakukan oleh asisten virtual berwujud karakter 3D (Vtuber-style). Produk ini dirancang khusus untuk disewakan atau dibeli oleh para pelaku UMKM F&B seperti cafe dan restoran guna meningkatkan interaksi pelanggan serta efisiensi operasional.

### Fitur Utama:
1.  **VERA AI (Asisten Kasir Virtual 3D)**: Melayani pemesanan langsung dan terintegrasi kode pembayaran QRIS otomatis.
2.  **Dashboard Realtime**: Dasbor untuk tim dapur memantau pesanan masuk secara instan.
3.  **Kelola Menu**: Pengaturan harga, nama menu, kategori, dan ketersediaan stok.
4.  **Laporan Penjualan**: Laporan omzet dan analisis transaksi bisnis.
5.  **Konfigurasi Agent**: Menyesuaikan kepribadian dan suara asisten virtual kasir.
6.  **Keamanan Dashboard**: Fitur PIN pengaman agar pelanggan tidak keluar dari mode kasir sembarangan.

---

## 🛠️ Tech Stack & Aturan Desain
*   **Framework**: Astro JS & Tailwind CSS V4 (native Vite integration)
*   **Styling Rules**:
    *   Warna Utama: `#E86C1D` (Oranye) & `#9D4300` (Hover)
    *   Style: Solid Rounded (tanpa border, tanpa shadow, tanpa glassmorphism)
    *   Pemisahan elemen murni menggunakan kontras warna (kartu putih `#FFFFFF` di atas body background `#F4F4F6`).

---

## 🚀 Cara Menjalankan Proyek Secara Lokal

1.  **Instalasi Dependensi**:
    ```bash
    npm install
    ```

2.  **Jalankan Server Dev**:
    ```bash
    npm run dev
    ```
    Aplikasi akan berjalan secara lokal di [http://localhost:4321](http://localhost:4321).

3.  **Build Produksi**:
    ```bash
    npm run build
    ```

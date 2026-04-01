# PULSA-GO ![gun](https://img.shields.io/badge/gun-ORIGINAL_PROJECT-003366?style=for-the-badge&logo=appveyor&logoColor=white&labelColor=00529b)


![Versi](https://img.shields.io/badge/version-1.0.0-blueviolet)
![Status](https://img.shields.io/badge/status-online-success)
![Lisensi](https://img.shields.io/badge/license-MIT-green)

**CuanPulsa** adalah platform asisten virtual berbasis web yang dirancang untuk memudahkan pengguna menukarkan (convert) pulsa menjadi saldo E-Wallet atau uang tunai secara otomatis, cepat, dan aman.

---

## ✨ Fitur Utama

* **⚡ Real-time Rate Calculator**: Kalkulator otomatis untuk menghitung estimasi saldo yang diterima berdasarkan rate terbaru (TSEL, XL, ISAT).
* **🤖 Interactive AI Chat Flow**: Pengalaman pengguna yang interaktif dengan simulasi "Admin sedang mengetik" untuk kesan layanan pelanggan yang personal.
* **🎁 Integrated Promo System**: Sistem klaim kode promo (seperti bonus New User atau Jumat Berkah) yang langsung terintegrasi ke form transaksi.
* **📱 WhatsApp Integration**: Transmisi data transaksi langsung ke WhatsApp admin untuk pemrosesan instan.
* **🎨 UI Modern & Futuristik**: Menggunakan *Glassmorphism design*, animasi *smooth*, dan font *Plus Jakarta Sans* yang elegan.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5**: Struktur semantik untuk aplikasi web.
* **CSS3**: Desain kustom dengan *CSS Variables*, *Radial Gradients*, dan *Keyframe Animations*.
* **JavaScript (ES6+)**: Logika kalkulator, manipulasi DOM dinamis, dan sistem *chat sequencer*.
* **Google Fonts & Material Icons**: Untuk tipografi dan elemen visual yang bersih.

---

## 🚀 Cara Instalasi

1.  **Clone atau Download** repositori ini:
    ```bash
    git clone [https://github.com/username/cuanpulsa.git](https://github.com/username/cuanpulsa.git)
    ```
2.  **Konfigurasi WhatsApp**:
    Buka file `index.html` dan cari variabel berikut di bagian `<script>`:
    ```javascript
    const wa = "628123456789"; // Ganti dengan nomor WhatsApp Admin Anda
    ```
3.  **Jalankan**:
    Cukup buka file `index.html` di browser pilihan Anda (Chrome, Edge, atau Safari). Tidak memerlukan server backend (Client-side ready).

---

## 📊 Daftar Rate Saat Ini

| Provider | Rate | Status |
| :--- | :--- | :--- |
| **Telkomsel** | 0.78 | 🟢 Stabil |
| **XL / Axis** | 0.77 | 🟢 Stabil |
| **Indosat** | 0.75 | 🟢 Stabil |

---

## 📸 Tampilan UI

> **Catatan:** Desain menggunakan tema *Dark Mode* dengan aksen warna Emerald (`#10b981`) dan Blue-Slate yang nyaman di mata.

---

## 📝 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Anda bebas menggunakan, memodifikasi, dan mendistribusikannya untuk keperluan pribadi maupun komersial.

---

## 🤝 Kontribusi

Ingin menambahkan fitur baru?
1. Fork repositori ini.
2. Buat branch fitur baru (`git checkout -b fitur/FiturKeren`).
3. Commit perubahan Anda (`git commit -m 'Menambahkan fitur keren'`).
4. Push ke branch (`git push origin fitur/FiturKeren`).
5. Buat Pull Request.

**CuanPulsa - Ubah Pulsamu Jadi Cuan!** 💰

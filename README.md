# [dokumentasi_repository_github.md](https://github.com/user-attachments/files/33903140/dokumentasi_repository_github.md)
# 🏴‍☠️ Captain Reztroid — 3D Interactive Pirate Sea Portfolio

Selamat datang di pelabuhan resmi **Captain Reztroid**! Proyek ini adalah website portfolio, katalog harga (*pricelist*), dan pusat pemesanan interaktif berbasis dunia 3D (*Three.js WebGL*) di mana pengunjung dapat mengemudikan kapal bajak laut **The Black Revenge** melintasi kepulauan samudra.

---

## ✨ Fitur Utama

- **⛵ Navigasi Kapal 3D Interaktif**: Klik permukaan air laut atau pulau tujuan untuk berlayar otomatis (*autopilot*), atau kemudikan kapal secara manual menggunakan tombol `WASD` / `Arrow Keys` (+ `Shift` untuk *Full Sail Boost*).
- **🏝️ 4 Kepulauan Utama**:
  1. **About · Reztroid**: Markas utama, profil layanan, dan keunggulan.
  2. **Pricelist · Katalog**: Daftar paket lengkap dari *Basic Corsair* hingga *Admiral VIP*.
  3. **Testimoni · Review**: Ulasan asli dan bukti transaksi pelanggan.
  4. **Order · Kontak**: Jalur cepat pemesanan via WhatsApp & Instagram.
- **🌅 Mode Siang & Malam (*Sunset / Night Mode*)**: Transisi pencahayaan langit, kabut, dan warna laut secara *real-time*.
- **🎵 Sea Shanty BGM & Efek Suara Sintetis**: Musik latar akustik bajak laut, suara deburan angin laut, dan efek tembakan meriam (*Spacebar*) menggunakan *Web Audio API* tanpa membebani *loading* halaman.
- **📱 Auto-Mobile Turbo Optimization**: Tampilan responsif dan ringan (60 FPS) baik di layar smartphone maupun desktop.

---

## 🎮 Cara Mengemudikan Kapal

| Kontrol | Aksi |
| :--- | :--- |
| **Klik / Tap Pulau atau Pin** | Berlayar otomatis ke dermaga pulau & membuka kartu info |
| **Klik / Tap Air Laut** | Berlayar menuju titik koordinat laut yang dipilih |
| **`W` `A` `S` `D` / Panah** | Mengemudikan kapal secara manual (Desktop) |
| **`Shift`** | Kecepatan penuh (*Full Sail*) |
| **`Spacebar` / Tombol Api** | Menembakkan meriam kanan & kiri (*Broadside Cannons*) |
| **Geser / Drag Layar** | Memutar sudut pandang kamera 360° |

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & Tailwind CSS** — Struktur dan desain antarmuka modern.
- **Three.js (WebGL)** — Mesin grafis 3D untuk air laut, pulau, dan kapal.
- **GSAP (GreenSock)** — Animasi transisi tema dan antarmuka.
- **Web Audio API** — Generator musik *Sea Shanty* dan efek suara prosedural.
- **Lucide Icons** — Ikon antarmuka minimalis.

---

## 🚀 Cara Mengubah Link WhatsApp & Sosial Media

Buka file `index.html` dan cari bagian `REZTROID_CONFIG` di baris awal `<script>`:

```javascript
const REZTROID_CONFIG = {
  customMp3Url: '', // Isi link MP3 jika ingin mengganti musik bawaan
  links: {
    haven: 'https://instagram.com/jifszz',
    vault: 'https://wa.me/6281299961001',
    log: 'https://instagram.com/jifszz',
    signal: 'https://wa.me/6281299961001'
  }
};
```

---

## 📜 Lisensi & Kredit

Dibuat khusus untuk **Captain Reztroid**.

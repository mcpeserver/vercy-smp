# Vercy SMP - Official Landing Page

[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=React&logoColor=61DAFB)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

Landing page resmi dan responsif untuk **Vercy SMP**, server Minecraft Survival Economy premium yang mendukung permainan lintas platform (*cross-play*) antara **Java Edition** dan **Bedrock Edition (PE)**.

---

## 🎨 Deskripsi Proyek

Website ini dibangun menggunakan **React**, **Vite**, **TypeScript**, dan **Tailwind CSS**. Didesain secara khusus menggunakan skema warna ungu gelap royal violet (`--color-brand-deep`, `--color-brand-royal`) dengan aksen lavender glow dan cyan neon untuk memberikan kesan modern, futuristik, dan eksklusif khas dunia gaming/Minecraft RPG.

---

## ⚡ Fitur Utama Website

- **Desain Bento Grid Modern & Responsif**: Menyajikan seluruh fitur unggulan server dengan visual card modern yang interaktif.
- **Copy-to-Clipboard Pintar**: Sistem penyalinan IP Address (Java & Bedrock) sekali klik yang intuitif dilengkapi animasi notifikasi instan.
- **Dinamis Developer Integration**: Menampilkan data developer secara asinkronus menggunakan React Hooks kustom yang terhubung ke Developer API eksternal.
- **Optimalisasi SEO & Metadata Lengkap**: Dilengkapi OpenGraph, Schema JSON-LD kustom untuk GameServer, sitemap, serta robots.txt untuk memaksimalkan indeks mesin pencari.
- **Performa Tinggi**: Animasi halus bertenaga `motion/react` dengan struktur aset yang sangat teroptimasi.

---

## 🛠️ Struktur Direktori Proyek

```bash
├── public/                  # Aset statis publik (sitemap.xml, robots.txt)
├── src/
│   ├── assets/              # Aset gambar yang telah teroptimasi (logo, hero, bg)
│   ├── components/          # Komponen UI modular (Navbar, HeroSection, Baltop, dll)
│   ├── config/              # Konfigurasi data statis (site.ts)
│   ├── hooks/               # Custom hooks React (useDeveloperData.ts)
│   ├── App.tsx              # Entry-point komponen utama
│   ├── index.css            # Desain kustom Tailwind & Google Fonts
│   └── main.tsx             # Entry-point aplikasi
├── vercel.json              # Konfigurasi routing & header untuk Vercel
├── package.json             # Manifest dependensi & script build
└── README.md                # Dokumentasi proyek (Dokumen ini)
```

---

## ⚙️ Cara Menjalankan Secara Lokal

### 1. Prasyarat
Pastikan Anda telah menginstal [Node.js](https://nodejs.org/) (versi 18 ke atas disarankan).

### 2. Instalasi Dependensi
Jalankan perintah berikut di root folder proyek:
```bash
npm install
```

### 3. Menjalankan Server Pengembangan (Dev Mode)
Jalankan server pengembangan lokal:
```bash
npm run dev
```
Aplikasi akan berjalan di `http://localhost:3000/`.

### 4. Melakukan Kompilasi Produksi (Build)
Untuk membuat build produksi yang siap di-deploy:
```bash
npm run build
```
Hasil kompilasi akan berada di direktori `dist/`.

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat berkas [LICENSE](./LICENSE) untuk detail lebih lanjut.

---

## 📞 Kontak & Media Sosial

- **WhatsApp Group**: [Gabung Komunitas](https://chat.whatsapp.com/LhB6M72Tq6H9LpKXnU9vPq)
- **Discord Server**: [Gabung Discord](https://discord.gg/vercysmp)
- **Developer Portfolio**: [Ran Dev Portfolio](https://portfolio.randev.my.id)

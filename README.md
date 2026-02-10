# Info Bukittinggi — Direktori Darurat & Transport (Single Page)

> Proyek latihan front-end (HTML + CSS) sebagai bagian dari progres belajar coding melalui sertifikasi Belajar Dasar Pemrograman Web di **Dicoding Indonesia**.  
> Fokus: **semantic HTML**, **Flexbox layout**, **responsif**, dan **aksesibilitas dasar**.

![Preview](docs/preview.png)

## 🌟 Tentang Proyek
**Info Bukittinggi** adalah halaman satu-lembar (single page) untuk membantu wisatawan domestik mendapatkan info cepat:
- **Quick Dial** nomor darurat (tel:112 / 119 / 110 / 113)
- **Fasilitas kesehatan** terdekat + tautan Google Maps
- **Transportasi & jadwal** sebagai acuan awal
- **Tips cepat** untuk kondisi darurat & perjalanan

> Catatan: data bisa berubah. Tetap konfirmasi ke sumber resmi/operator setempat.

## ✨ Fitur Utama
- ✅ **Quick Dial bar** (sticky) untuk akses cepat nomor darurat
- ✅ Navigasi anchor yang jelas (Darurat / Kesehatan / Transport / Tips)
- ✅ Layout **Flexbox** (tanpa framework)
- ✅ Responsif:
  - Layout kolom → stack di layar kecil
  - Mode perangkat sentuh: Quick Dial menjadi fixed di bawah layar
- ✅ Aksesibilitas dasar:
  - Skip link “Lewati ke konten utama”
  - `aria-label` di elemen interaktif
  - Gambar punya `alt`
  - Dukungan `prefers-reduced-motion`

## 🧰 Tech Stack
- **HTML5** (semantic tags: `header`, `nav`, `main`, `article`, `aside`, `footer`)
- **CSS3** (Flexbox, media query)
- Tanpa library layout (Bootstrap/Tailwind/dll)

## 📁 Struktur Folder

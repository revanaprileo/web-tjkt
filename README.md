# Website Jurusan TJKT - SMK YPT PRINGSEWU

Semua file sudah dalam bentuk flat (tidak ada folder) agar mudah diupload ke GitHub.

## Cara Upload ke GitHub

1. Buat repository baru di GitHub
2. Upload semua file di folder ini (bisa drag & drop semua file sekaligus ke GitHub)
3. Aktifkan GitHub Pages: Settings → Pages → Source: Deploy from branch → main branch → Save

Website akan live di: `https://[username].github.io/[nama-repo]/`

## Daftar File & Link

### Dokumen & Foto (semua di root)
- **index.html** - Halaman utama website
- **logo tjkt.png** - Logo TJKT
- **logo ypt.png** - Logo YPT  
- **profil 1.jpg, profil 2.jpg, profil 3.jpg** - Foto profil jurusan
- **lab tjkt.jpg, lab 2.jpeg** - Foto lab
- **ezgif-frame-001.jpg** sampai **ezgif-frame-240.jpg** - Frame animasi hero
- Foto guru: Pak Wahyu Sapto, Pak Gentri Divya, Pak Alfian Dio, Bu Eva Yanti, Bu Risnawati, wahyu kukuh, ferdiansyah, aziz, ratna, fatholil
- Ilustrasi siswa: revan.png, zahra.png, rihan.png, qeylila.png, rofik.png

### Fitur AI (untuk Vercel)
- **ask-ai.js** - Kode API AI (untuk referensi). Fitur AI **tidak berjalan** di GitHub Pages. Untuk mengaktifkan AI, deploy ke Vercel dan buat folder `api/ask-ai/` dengan file `index.js` (isi dari ask-ai.js).

## Catatan
- GitHub Pages hanya menampilkan konten statis
- Fitur AI Konselor memerlukan Vercel (serverless) untuk berjalan

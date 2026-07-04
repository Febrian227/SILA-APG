# Sistem Layanan Mahasiswa - Form Input & Tabel Data

Project web sederhana untuk memenuhi SUB-CPMK-07-2-8: input data melalui form dan menampilkan data pada tabel, dengan integrasi HTML, CSS, JavaScript, dan Git.

## Struktur File
```
proyek-web/
├── index.html      # Halaman form input data
├── data.html       # Halaman tabel data
├── css/
│   └── style.css   # Styling (tema biru, responsif)
├── js/
│   └── script.js   # Logika input, simpan, tampil, hapus data
└── README.md
```

## Fitur
- Form input: Nama, NIM, Jenis Layanan, Keterangan
- Data diproses dengan JavaScript dan disimpan di `localStorage`
- Data otomatis tampil di halaman tabel (data.html)
- Tombol hapus data per baris
- Layout responsif (mobile & desktop)

## Cara Menjalankan
1. Buka folder `proyek-web` di komputer.
2. Buka file `index.html` langsung di browser (double click), atau gunakan extension "Live Server" di VS Code.
3. Isi form lalu klik **Simpan Data**.
4. Klik menu **Tabel Data** untuk melihat data yang sudah diinput.

## Cara Push ke GitHub (Git)
Jalankan di terminal, di dalam folder project:

```bash
git init
git add .
git commit -m "Initial commit: form input dan tabel data"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

Ganti `USERNAME` dan `NAMA-REPO` dengan akun dan nama repository GitHub kamu.

Setelah berhasil push, salin link repository (misal: `https://github.com/USERNAME/NAMA-REPO`) untuk dilampirkan sebagai Output tugas.

# Slip Gaji PT Ray Mitra Perkasa — GitHub Pages

Versi ini tidak memakai Netlify Functions. Website berjalan sebagai static site di GitHub Pages.

## Deploy
1. Buat repository GitHub baru (misalnya `slip-gaji`).
2. Upload seluruh isi ZIP ini ke branch `main`. File `index.html` harus berada di root repository.
3. Buka **Settings → Pages**. Pada **Build and deployment → Source**, pilih **GitHub Actions**.
4. Buka tab **Actions** dan tunggu workflow `Deploy Slip Gaji to GitHub Pages` selesai.
5. URL biasanya `https://USERNAME.github.io/NAMA-REPOSITORY/`.

## Penyimpanan data
GitHub Pages hanya menyediakan hosting file statis. Data aplikasi pada versi ini disimpan di `localStorage` browser. Artinya data tetap ada setelah browser ditutup pada perangkat yang sama, tetapi **tidak otomatis tersinkron antar-perangkat/browser**. Jangan memasukkan data rahasia ke repository GitHub.

## Google Sheets
Sinkron Google Sheets pada versi ini dicoba langsung dari browser melalui endpoint GViz. Spreadsheet harus dapat diakses sebagai Viewer oleh siapa saja yang memiliki link. Jika browser memblokir akses lintas situs, gunakan fitur input/import yang tersedia pada aplikasi atau backend terpisah.

## Catatan keamanan
Jangan menaruh password, token GitHub, API key, atau kredensial rahasia di `index.html`, karena file GitHub Pages bersifat publik.


## Perbaikan V14
Parser header Google Sheets diperbaiki untuk format kolom seperti `A NO`, `B NAMA`, `C GAJI`, dan seterusnya.

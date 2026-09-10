# Slip Gaji PT Ray Mitra Perkasa — GitHub Pages

Versi GitHub Pages dengan dukungan beberapa link Google Sheets.

## Konsep
- Satu link Google Sheets dapat berisi sheet Januari–Desember.
- Anda dapat menambahkan beberapa link, misalnya berdasarkan lokasi/cakupan.
- Tombol **Sinkron Otomatis** mencoba membaca sheet bulan dari setiap link.
- Data karyawan dikelompokkan berdasarkan **bulan** dan **wilayah/lokasi** yang terbaca dari struktur data sheet.
- Tombol **Tempel Data** tetap tersedia sebagai cadangan jika sebuah sheet tidak dapat dibaca otomatis.

## Syarat Google Sheets
Spreadsheet harus dapat diakses untuk dibaca melalui link. Jika spreadsheet bersifat privat, browser GitHub Pages tidak dapat membaca isinya tanpa backend/API yang memiliki otorisasi.

## Upload ke GitHub
Upload `index.html` dan `.nojekyll` ke root repository, lalu gunakan:
Settings → Pages → Deploy from a branch → `main` → `/(root)`.

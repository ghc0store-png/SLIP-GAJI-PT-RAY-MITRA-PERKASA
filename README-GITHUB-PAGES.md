# Slip Gaji PT Ray Mitra Perkasa — GitHub Pages

Versi statis untuk GitHub Pages.

## Cara upload
1. Upload `index.html` dan `.nojekyll` ke **root** repository.
2. Masuk **Settings → Pages**.
3. Source: **Deploy from a branch**.
4. Branch: **main** dan folder **/(root)**.
5. Klik **Save**.
6. Tunggu sampai deployment selesai.

## Catatan penyimpanan
Versi GitHub Pages ini tidak menggunakan Netlify Functions.
Data aplikasi disimpan di localStorage browser. Fitur impor Google Sheets
tetap tersedia melalui fitur **Tempel Data**.

Untuk penyimpanan yang sama di banyak perangkat/akun, diperlukan backend
eksternal (misalnya Google Apps Script + Google Sheets atau database).

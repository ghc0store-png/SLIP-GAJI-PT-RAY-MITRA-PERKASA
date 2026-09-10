# Slip Gaji PT Ray Mitra Perkasa — GitHub Pages

Versi GitHub Pages dari aplikasi Slip Gaji PT Ray Mitra Perkasa.

## Upload
Upload **isi ZIP ini** ke root repository GitHub:
- `index.html`
- `.nojekyll`

Jangan upload folder pembungkus ZIP.

## GitHub Pages
Repository → **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**
- Save

## Catatan data
Versi ini tidak memakai Netlify Functions. Data aplikasi disimpan di browser
(localStorage), sehingga data tetap ada setelah halaman ditutup pada browser
yang sama.

Fitur impor dari Google Sheets menggunakan alur salin dari Google Sheets lalu
tempel ke aplikasi. GitHub Pages sendiri tidak menyediakan database bersama.

Untuk data yang sama di HP/PC/browser berbeda, aplikasi membutuhkan backend
seperti Google Apps Script + Google Sheets atau database online.

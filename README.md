# SIJAGA BMN — Struktur File

## Isi folder
- `index.html`: struktur halaman website.
- `style.css`: desain dan tampilan.
- `app.js`: logika aplikasi, termasuk fungsi ekspor laporan `exportCSV()`.
- `assets/`: tempat menyimpan logo/gambar tambahan jika diperlukan.

## Cara menjalankan
Buka `index.html` di browser. Untuk menerbitkan di GitHub Pages, unggah isi folder ini ke repository dan aktifkan GitHub Pages dari branch/folder yang sesuai.

## Ekspor laporan
Fungsi `exportCSV()` yang ada pada `app.js` mengekspor data BMN, pemeliharaan, laporan kerusakan, dan pengecekan ke file CSV yang dapat dibuka dengan Microsoft Excel.

Catatan: versi ini mempertahankan perilaku dan kode dari file HTML yang diberikan, hanya memisahkan CSS dan JavaScript ke file terpisah. Penyimpanan browser/localStorage tidak otomatis menyinkronkan data antarperangkat.

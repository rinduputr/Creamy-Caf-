# 🍦 FrostPOS — Ice Cream POS

Aplikasi kasir ice cream modern berbasis **HTML + CSS + JavaScript + JSON** dan siap di-deploy ke **GitHub Pages**.

## Fitur
- Kasir / POS dengan keranjang
- Pencarian produk & filter kategori
- Tambah, edit, hapus produk
- Stok otomatis berkurang setelah pembayaran
- Diskon persentase
- Dine In / Take Away
- Cash / QRIS / Debit
- Perhitungan kembalian
- Riwayat transaksi
- Export transaksi ke JSON
- Dashboard laporan omzet, transaksi, item terjual
- Produk terlaris & penjualan per kategori
- Dark mode
- Pengaturan nama toko & kasir
- LocalStorage — data tetap tersimpan di browser
- Responsive mobile, tablet, desktop
- Tanpa backend / database

## Cara menjalankan
Cukup buka `index.html` di browser.

## Deploy GitHub Pages
1. Buat repository baru di GitHub.
2. Upload `index.html`, `style.css`, `app.js`, dan `data.json`.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/root`.
6. Save, lalu tunggu proses deployment.

## Catatan
Karena ini aplikasi frontend-only, data transaksi tersimpan di LocalStorage browser masing-masing perangkat. Untuk kasir multi-device/sinkronisasi online, aplikasi perlu backend/database.

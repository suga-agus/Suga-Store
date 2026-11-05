# SUGA — Website Toko Online

Website toko online statis, siap dipublikasikan gratis melalui GitHub Pages.

## Cara mengatur
1. Buka `index.html`.
2. Cari bagian `PENGATURAN TOKO` di dalam `<pengaturan>`.
3. Ganti `whatsapp` dengan nomor WhatsApp admin dalam format internasional tanpa `+` (contoh `6287828446729`).
4. Ganti contoh produk pada array `PRODUCTS` dengan produk, harga, deskripsi, kategori, dan foto milik toko.
5. Untuk rekening, isi `bankName`, `bankAccount`, dan `bankOwner`. Tampilan pembayaran saat ini sengaja meminta pelanggan menunggu konfirmasi admin sebelum transfer.
6. Untuk QRIS, buat folder `assets`, lalu letakkan gambar QRIS resmi toko di `assets/qris.png`. (Kode dasar ini belum menampilkan QRIS secara publik; admin dapat mengirimkannya lewat WhatsApp setelah konfirmasi.)

## Publikasi GitHub Pages
1. Buat repository publik baru, misalnya `suga-store`.
2. Upload `index.html` (dan folder `assets` jika digunakan).
3. Masuk ke Settings → Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.
6. Setelah deployment selesai, alamat situs akan muncul di halaman Pages, biasanya `https://USERNAME.github.io/suga-store/`.

## Catatan penting
- Hosting GitHub Pages gratis untuk situs statis, tunduk pada ketentuan dan batas penggunaan GitHub.
- Website ini tidak menyimpan data pelanggan di server, tidak memiliki login admin, stok real-time, ongkir otomatis, atau pembayaran otomatis.
- Pesanan dikirim melalui WhatsApp. Konfirmasi stok, ongkir, rekening, dan pembayaran dilakukan manual oleh admin.
- Jangan memasukkan data rekening atau QRIS palsu. Gunakan hanya informasi pembayaran resmi milik toko.

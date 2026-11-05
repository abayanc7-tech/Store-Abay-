ABAY STORE — WEBSITE KASIR ONLINE

CARA MENJALANKAN
1. Ekstrak file ZIP.
2. Buka folder abay_store_cashier.
3. Klik dua kali index.html, atau buka folder menggunakan VS Code.
4. Untuk pengalaman terbaik, jalankan dengan ekstensi Live Server di VS Code.

FILE
- index.html       : halaman utama
- products.html    : katalog produk
- checkout.html    : keranjang dan checkout
- payment.html     : tampilan QRIS dan konfirmasi WhatsApp
- history.html     : riwayat transaksi di browser
- style.css        : desain dan animasi hover/responsif
- app.js           : logika keranjang, harga, checkout, WhatsApp
- assets/          : gambar referensi kasir dan QRIS milik toko

PENTING
- Nomor WhatsApp owner sudah diatur ke 083840918386.
- QRIS memakai gambar yang diberikan. Ini QRIS statis; nominal mungkin harus dimasukkan manual oleh pembeli.
- Website statis tidak bisa memverifikasi pembayaran QRIS secara otomatis. Owner perlu mengecek pembayaran dari aplikasi merchant/bank.
- Pesanan dikirim ke WhatsApp melalui tombol konfirmasi, bukan dikirim diam-diam di latar belakang.
- Produk dan harga contoh dapat diedit pada array `products` di app.js.
- Website ini belum memakai database/server. Keranjang dan riwayat disimpan pada browser perangkat masing-masing.
- Foto produk mengambil gambar dari Unsplash dan membutuhkan koneksi internet.

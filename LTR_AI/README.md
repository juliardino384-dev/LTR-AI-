# LTR AI — prototipe awal

Website responsif untuk Android dan desktop. Berisi halaman Chat AI, Generator Gambar, Generator Video, Penulis AI, dan Paket Kredit.

## Menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` di browser untuk melihat prototipe.
3. Untuk publikasi, unggah folder ini ke hosting statis seperti Netlify, Vercel, atau hosting web pilihan.

## Yang sudah tersedia
- Tampilan responsif.
- Navigasi antarfitur.
- Saldo kredit demo tersimpan di browser (localStorage).
- Pengurangan kredit demo saat fitur digunakan.
- Paket kredit demo.

## Belum tersedia (wajib sebelum peluncuran sungguhan)
- Backend/API AI untuk chat, gambar, video, dan penulisan.
- Login, akun pengguna, database, dan riwayat.
- Pembayaran sungguhan serta webhook/verifikasi transaksi.
- Pengelolaan saldo kredit di server dan proteksi penyalahgunaan.

PENTING: saldo di localStorage dapat diubah pengguna dan TIDAK aman untuk transaksi. Jangan menerima uang atau menyimpan API key di frontend. Implementasi produksi harus memvalidasi saldo dan pembayaran di backend.

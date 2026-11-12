# SI-KP SPAMS — Sistem Informasi Akuntansi Syariah

Prototype antarmuka web untuk mendukung operasional dan pencatatan akuntansi KP-SPAMS.

## Menjalankan
Buka `index.html` menggunakan browser modern. Tidak memerlukan proses build atau instalasi dependency.

## Modul
- Dashboard operasional dan ringkasan keuangan
- Data pelanggan
- Baca meter dan validasi pemakaian
- Tagihan dengan pemisahan ujrah, dana titipan, dan ta'zir
- Pembayaran dan pratinjau kuitansi
- Jurnal dan Chart of Accounts (COA)
- Dana titipan dan ta'zir/dana sosial
- Laporan dasar
- Gangguan / Work Order
- Audit Trail

## Prinsip desain akuntansi syariah
- Ujrah jasa air ditampilkan sebagai pendapatan jasa.
- Dana titipan pelanggan dipisahkan dari pendapatan dan diperlakukan sebagai kewajiban.
- Ta'zir dipisahkan dari pendapatan operasional dan diarahkan untuk dana sosial sesuai kebijakan syariah yang ditetapkan.
- Transaksi perlu memiliki bukti, otorisasi, dan jejak audit.

## Batasan
Ini adalah prototype front-end, bukan aplikasi produksi. Data yang tampil adalah simulasi. Interaksi hanya mengubah tampilan selama sesi browser dan belum tersimpan ke database permanen. Belum tersedia autentikasi/RBAC nyata, backend, sinkronisasi offline, penyimpanan foto, jurnal otomatis tervalidasi, backup, atau integrasi pembayaran.

## Tahap MVP berikutnya
Pelanggan, tarif, baca meter, tagihan, pembayaran, tunggakan, kas, COA, jurnal, laporan dasar, RBAC, dan audit trail. Payment gateway produksi, GIS lanjutan, dan akuntansi keuangan lengkap berada di luar ruang lingkup MVP awal.

Perlakuan akuntansi dan kepatuhan syariah perlu ditelaah serta disahkan oleh pengelola dan pihak kompeten sebelum penggunaan operasional.

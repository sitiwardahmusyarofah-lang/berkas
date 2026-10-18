# RuangBerkas — Website Arsip Pribadi

Template website pengelolaan kumpulan berkas pribadi dengan Bootstrap 5, desain responsif, dan antarmuka modern.

## Fitur
- Dashboard ringkasan jumlah berkas, favorit, dan kategori.
- Unggah banyak berkas sekaligus.
- Kategori: Identitas, Keuangan, Pendidikan, Pekerjaan, dan Lainnya.
- Pencarian, filter jenis file, serta pengurutan.
- Tandai favorit, unduh, dan hapus berkas.
- Penyimpanan menggunakan IndexedDB pada browser/perangkat yang sedang digunakan.
- Tata letak responsif untuk desktop, tablet, dan ponsel.

## Cara menjalankan
1. Ekstrak folder `arsip-pribadi`.
2. Buka `index.html` di browser modern (Chrome, Edge, Firefox).
3. Untuk pengalaman lokal yang lebih konsisten, jalankan server lokal dari folder proyek, misalnya `python -m http.server 8000`, lalu buka `http://localhost:8000`.
4. Klik **Tambah berkas**, pilih file, tentukan kategori, lalu simpan.

## Catatan keamanan penting
Versi ini adalah prototipe front-end. File disimpan pada penyimpanan browser di perangkat yang digunakan; file tidak dikirim ke server atau disinkronkan ke cloud. Siapa pun yang memiliki akses ke profil browser/perangkat mungkin dapat mengakses data tersebut. Untuk penggunaan dokumen sensitif atau multi-pengguna, tambahkan backend, autentikasi, otorisasi, enkripsi saat transit dan saat tersimpan, validasi upload di server, batas ukuran/jenis file, pencadangan, dan kebijakan retensi. Jangan gunakan prototipe ini sebagai brankas dokumen sensitif tanpa pengamanan tambahan.

## Teknologi
- HTML5
- CSS3
- Bootstrap 5.3.3 dan Bootstrap Icons (CDN)
- JavaScript
- IndexedDB API

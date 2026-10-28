DOMPETKU WEB + MODE OFFLINE

Isi:
- index.html: aplikasi DompetKu
- manifest.json: metadata agar dapat dipasang sebagai aplikasi web
- sw.js: service worker untuk menyimpan file aplikasi agar bisa dibuka offline setelah kunjungan online pertama

CARA PUBLISH TANPA NETLIFY (GitHub Pages):
1. Buat/login akun GitHub.
2. Buat repository baru, misalnya dompetku.
3. Ekstrak ZIP ini.
4. Unggah ketiga file/folder di root repository: index.html, manifest.json, sw.js.
5. Buka Settings > Pages.
6. Di bagian Build and deployment pilih Deploy from a branch, pilih branch main dan folder /(root), lalu Save.
7. Tunggu URL Pages muncul. Buka URL itu sekali saat internet aktif agar aplikasi dan service worker terpasang.
8. Di Chrome Android, buka menu ⋮ lalu pilih Tambahkan ke layar utama / Install app jika tersedia.

MODE OFFLINE:
- Setelah aplikasi berhasil dibuka online sekali dan service worker aktif, halaman utama bisa dibuka offline.
- Perhitungan dan fitur JavaScript yang berada di aplikasi berjalan di perangkat tanpa server.
- Data transaksi disimpan di penyimpanan browser perangkat ini; jangan hapus data situs/browser tanpa ekspor cadangan.
- Offline bukan berarti data otomatis tersinkron ke perangkat lain.
- Fitur yang membuka layanan luar (misalnya WhatsApp) tetap memerlukan internet.
- Jika file diubah, versi cache mungkin perlu diperbarui; buka ulang saat online.

CATATAN:
Ini adalah aplikasi web statis. Tidak ada backend/server database. Jangan anggap PIN lokal sebagai keamanan setingkat aplikasi perbankan.

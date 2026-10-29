DOMPETKU - PAKET GITHUB PAGES

Semua file ada di root (tanpa folder ikon). Unggah isi ZIP ini langsung ke halaman utama repository GitHub.

File utama:
- index.html: aplikasi DompetKu
- sw.js: cache/offline dasar untuk file satu origin
- manifest.json: konfigurasi instalasi aplikasi
- icon-192.png dan icon-512.png: ikon aplikasi
- icon-1080.png, icon-2160.png, icon-4k.png: ikon resolusi tinggi
- icon-source.png: gambar ikon sumber

Cara pakai:
1. Ekstrak ZIP.
2. Upload semua file yang ada di dalamnya langsung ke root repository (jangan upload ZIP sebagai satu file).
3. Timpa index.html, sw.js, dan manifest.json lama saat diminta.
4. Commit changes.
5. Buka website ketika online, tunggu sampai selesai dimuat, lalu uji offline.

Penting:
- Offline hanya berlaku untuk aplikasi dan file same-origin yang sudah tersimpan di cache; fitur yang butuh internet/layanan eksternal mungkin tetap tidak bekerja offline.
- Jangan mengunggah file cadangan JSON berisi transaksi ke repository publik.
- Jangan hapus data browser lama sebelum membuat dan memeriksa cadangan transaksi.

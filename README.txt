DOMPETKU — GITHUB PAGES + OFFLINE

Unggah semua isi ZIP ini ke root repository GitHub Pages, bukan ke dalam folder lain:
- index.html
- manifest.json
- sw.js
- icons/icon-192.png dan icons/icon-512.png

Di GitHub: Settings > Pages > Deploy from a branch > main > /(root).
Buka website melalui HTTPS saat online setidaknya sekali agar service worker terpasang dan cache awal terisi. Setelah itu, buka kembali website dan coba mode pesawat.

Untuk memasang di Android: buka URL di Chrome biasa (bukan browser dalam aplikasi), menu ⋮ > Instal aplikasi jika tersedia. Jika hanya muncul Buat pintasan, gunakan itu; instalasi PWA bergantung dukungan Chrome dan syarat browser.

PENTING: data transaksi di localStorage terikat pada origin/browser. Memindahkan app ke GitHub Pages tidak otomatis memindahkan data dari file HTML lama atau alamat host lain. Sebelum mengganti file, ekspor/cadangkan data melalui Pengaturan & data. Jangan unggah file cadangan JSON ke repository publik.

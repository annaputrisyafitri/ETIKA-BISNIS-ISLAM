PAKET AR & VR - ETIKA BISNIS ISLAM
=================================

ISI PAKET
---------
1. ar.html             Halaman Augmented Reality berbasis marker Hiro.
2. vr.html             Halaman Virtual Reality berbasis A-Frame.
3. menu-ar-vr.html     Potongan menu untuk ditambahkan ke halaman utama.
4. README.txt          Panduan pemasangan dan pengujian.

CARA MEMASANG KE GITHUB
-----------------------
1. Buka repositori GitHub yang menerbitkan website ETIKA-BISNIS.
2. Pastikan ar.html dan vr.html diunggah pada folder yang sama dengan
   halaman utama website (biasanya root repositori).
3. Buka file menu-ar-vr.html, salin seluruh isi bagian <section> dan <style>,
   lalu tempelkan ke dalam <body> file halaman utama Anda pada posisi menu
   yang diinginkan.
4. Commit perubahan dan tunggu GitHub Pages menerbitkan ulang website.
5. Uji tautan:
   https://NAMA-USERNAME.github.io/NAMA-REPOSITORY/ar.html
   https://NAMA-USERNAME.github.io/NAMA-REPOSITORY/vr.html

PENGUJIAN AR
------------
- Buka ar.html dari smartphone melalui HTTPS.
- Izinkan akses kamera.
- Cetak/buka marker Hiro dari perangkat lain:
  https://ar-js-org.github.io/AR.js/data/images/HIRO.jpg
- Arahkan kamera ke marker. Objek 3D seharusnya muncul di atas marker.
- AR ini menggunakan marker-based tracking, bukan penempatan objek bebas
  pada permukaan (markerless AR).

PENGUJIAN VR
------------
- Buka vr.html di browser desktop untuk menguji mode 3D.
- Gunakan mouse untuk melihat sekeliling dan W-A-S-D untuk bergerak.
- Pilih objek JUJUR, AMANAH, atau ADIL untuk menampilkan penjelasan.
- Pada headset dan browser yang mendukung WebXR, tekan tombol VR yang
  disediakan A-Frame di kanan bawah lalu ikuti instruksi perangkat.

CATATAN KOMPATIBILITAS DAN KEAMANAN
----------------------------------
- GitHub Pages menggunakan HTTPS; akses kamera memerlukan izin pengguna.
- AR.js dan A-Frame dimuat dari CDN, sehingga perangkat harus terhubung
  ke internet.
- Dukungan AR/VR berbeda menurut perangkat, browser, dan headset.
- Jangan memasukkan API key rahasia ke HTML/JavaScript publik.
- Tautan "Kembali" mengarah ke root website (./). Jika struktur website
  Anda berbeda, sesuaikan href tersebut.
- Versi ini merupakan halaman tambahan mandiri. Tidak mengubah atau
  menggantikan file HTML utama dan fitur yang sudah ada.
- Jika library CDN gagal dimuat karena jaringan atau kebijakan browser,
  periksa koneksi dan console browser.

VERSI
-----
Paket dasar integrasi AR/VR Etika Bisnis Islam.

PRAKTIKUM PERTEMUAN 3 - LKP 2B
Membuat Halaman Profil Responsif

Isi folder:
- index.html       : halaman profil (menggunakan halaman LKP 2A)
- style.css        : CSS yang sudah ditambahkan media queries
- assets/foto.jpg  : gambar profil contoh

CARA MENJALANKAN
1. Ekstrak ZIP ini.
2. Buka folder lpk-2b menggunakan Visual Studio Code.
3. Jalankan index.html di browser (bisa memakai ekstensi Live Server).
4. Pastikan halaman tampil dan navigasi Tentang, Keahlian, serta Kontak berfungsi.

CARA MENGUJI RESPONSIVITAS (SESUAI MODUL)
1. Buka halaman di Google Chrome.
2. Tekan F12, lalu klik ikon Device Toggle atau tekan Ctrl+Shift+M.
3. Atur lebar layar menjadi:
   - 375px (iPhone SE): cards tampil 1 kolom.
   - 768px (iPad): cards tampil 2 kolom.
   - 1200px (Desktop): cards tampil 4 kolom.
4. Ambil screenshot masing-masing ukuran dan simpan di folder lpk-2b dengan nama:
   - screenshot-375.png
   - screenshot-768.png
   - screenshot-1200.png

CATATAN
- Foto profil pada folder assets adalah foto contoh. Ganti dengan foto sendiri
  jika diperlukan; pertahankan nama file foto.jpg.
- Ganti email@example.com dan username GitHub pada index.html dengan akun sendiri.
- Screenshot harus diambil dari browser setelah halaman dijalankan, bukan dari
  gambar contoh.

CONTOH COMMIT GITHUB
git add lpk-2b/
git commit -m "LKP 2B: Responsive design dengan media queries"
git push

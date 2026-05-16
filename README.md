# Table Export PDF and Excel - 41 Card Game

## Deskripsi
Proyek ini adalah sebuah aplikasi berbasis web untuk merekap hasil permainan kartu 41. Aplikasi ini memungkinkan pengguna untuk memasukkan jumlah pemain, nama pemain, serta skor setiap permainan. Setelah permainan selesai, hasil dapat diekspor ke dalam format Excel atau PDF. Website ini dibangun full frontend tanpa backend, jadi menggunakan JavaScript sebagai interaksi pada halamannya. Selain itu, terdapat beberapa validasi yang ada untuk menambah fitur dan kesan baik dalam pengalaman pengguna.

## Fitur
- Menambahkan jumlah pemain (2-4 pemain).
- Memasukkan nama pemain berdasarkan jumlah pemain.
- Menambahkan permainan dan masukan skor untuk setiap permainan.
- Validasi input skor (antara 0 dan 41).
- Menghapus baris permainan.
- Mengubah nama pemain.
- Menjumlahkan skor otomatis.
- Validasi input skor kosong.
- Auto-save sesi di browser + opsi lanjutkan sesi terakhir.
- Menampilkan ringkasan total skor dan pemenang (skor tertinggi).
- Mengekspor hasil permainan ke format Excel.
- Mengekspor hasil permainan ke format PDF.
- PWA (Progressive Web App) — bisa diinstall ke home screen HP dan dipakai offline.

## Penggunaan
1. Buka link [bit.ly/empatSatu](https://bit.ly/empatSatu) di browser.
2. Masukkan jumlah pemain.
3. Masukkan nama pemain.
4. Tambahkan dan masukan skor untuk setiap permainan.
5. Setelah selesai, klik "Selesai Permainan".
6. Ekspor hasil permainan ke format Excel atau PDF dengan mengklik tombol yang sesuai.
7. Jika tidak sengaja refresh, pilih "Lanjutkan" ketika muncul prompt untuk melanjutkan sesi terakhir.

## Teknologi yang Digunakan
- HTML
- CSS (Bootstrap 5)
- JavaScript
- [SweetAlert2](https://sweetalert2.github.io/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs)
- Service Worker (PWA)

## Versioning
- v1.0, pertama kali commit - 7 Agustus 2024
- v1.1, upload create.md - 7 Agustus 2024
- v1.2, tambahkan tanggal export dan jumlah poin pada export pdf dan excel - 8 Agustus 2024
- v1.2.1, tambahkan icon pada tab website - 3 Januari 2025
- v1.3, update width minimum input type pada skor sesuai max width pixel - 3 Januari 2025
- v1.3.1, update icon menjadi local repo github - 3 Januari 2025
- v1.3.2 & v1.3.3, fixing width minimum input type - 3 Januari 2025
- v1.3.4, ganti nama player pada frontend dengan modal dan javascript - 4 Januari 2025
- v1.4, update file cdn menjadi local repo github - 28 Januari 2025
- v1.4.1, local file cdn error, deleting... - 29 Januari 2025
- v1.4.2, detail... : - 29 Januari 2025
	* (bug) input e pada type number
	* (bug) baris permainan pada table ketika dihapus, angka nomor permainan tidak urut
	* (fitur baru) maksimal 2 digit pada saat input skor pada input type number
	* (bug) pop-up (modal bootstrap) ubah nama pemain bisa dilakukan close dengan tombol silang merah dan tombol batal
	* (fitur baru) ketika input error atau kosong (saat klik selesai permainan) akan berwarna merah pada kotak yg kosong
	* (fitur baru) ada notifikasi jika tidak melakukan perubahan nama pemain pada modal bootstrap, trigger -> submit perubahan nama pemain
- v1.4.3, update batas maksimal jumlah pemain - 29 Januari 2025
- v1.4.4, update readme.md - 30 Januari 2025
- v1.5.0, menggunakan agent ai untuk mengetes agent ai dan memperbarui fitur seperti autosave, export pdf dirapihkan dan update readme md
- v1.5.1, update readme.md - 12 Mei 2026
- v1.6.0, tambah fitur PWA (manifest.json, service worker, installable, offline) - 16 Mei 2026

## Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori ini dan buat pull request dengan perubahan yang Anda usulkan. Semua kontribusi sangat dihargai!

## Lisensi
Proyek ini dilisensikan di bawah MIT License. Lihat file LICENSE untuk informasi lebih lanjut.

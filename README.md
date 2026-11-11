# Pelatihan Sales Enter Komputer

Web latihan untuk karyawan training, dibuat dari Modul Sales Enter Komputer (v0.5).

- Pilihan Ganda: 276 soal, 15 topik (Sales, SOP, FAQ, Dasar Komputer, lalu Processor sampai Keyboard; minimal 20 soal per kategori komputer)
- Esai: 251 pertanyaan dengan penilaian mandiri (20 per kategori komputer, plus studi kasus penjualan)
- Step by Step: simulasi layanan pelanggan walk-in dan merakit PC

Satu file statis (`index.html`), tanpa build. Buka langsung di browser atau aktifkan GitHub Pages (Settings, Pages, branch `main`, folder root).
Jawaban peserta tersimpan di browser masing-masing (localStorage).

## Admin dan riwayat skor (versi 0.6)

Halaman Admin (edit soal dan jawaban, riwayat nama dan skor peserta) memakai database bersama dari Claude Artifact, jadi **hanya aktif di versi artifact**. Di GitHub Pages (hosting statis) aplikasi tetap jalan sebagai latihan mandiri, tetapi tab Admin tidak muncul dan hasil hanya tersimpan di browser masing-masing.

## Live Selling (versi 0.8)

Halaman baru berisi 29 komentar customer di siaran langsung, dikelompokkan dalam 6 kategori (Harga & Promo, Stok & Pengiriman, Spesifikasi & Rekomendasi, Garansi & Layanan, Cara Beli & Pembayaran, Keraguan & Keluhan). Peserta menjawab sebagai host dalam bentuk esai, lalu melihat contoh jawaban host yang ramah, contoh yang perlu dihindari, dan poin penilaian mandiri.

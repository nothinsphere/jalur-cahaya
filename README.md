# Jalur Cahaya

Modul belajar interaktif untuk teknisi fiber optik, bergaya lembar datasheet dan gambar teknik.

- Tahap 1: https://nothinsphere.github.io/jalur-cahaya/
- Tahap 2: https://nothinsphere.github.io/jalur-cahaya/tahap-2/
- Tahap 3: https://nothinsphere.github.io/jalur-cahaya/tahap-3/
- Tahap 4: https://nothinsphere.github.io/jalur-cahaya/tahap-4/
- Tahap 5: https://nothinsphere.github.io/jalur-cahaya/tahap-5/
- Tahap 6: https://nothinsphere.github.io/jalur-cahaya/tahap-6/
- Tahap 7: https://nothinsphere.github.io/jalur-cahaya/tahap-7/
- Lampiran: https://nothinsphere.github.io/jalur-cahaya/lampiran/ (glosarium, asumsi simulasi, sumber teknis, lembar praktik, rubrik)

Materi diperbarui 27 Oktober 2026.

**Tahap 1 · K3 & teori dasar** (`index.html`)

- 1.1 Keselamatan kerja: cahaya laser yang tidak terlihat, serpihan kaca, APD
- 1.2 Struktur kabel: 6 jenis kabel (duct, udara figure-8, ADSS, tanam langsung, drop FTTH, indoor), diselami dari jaket luar sampai core dengan skala ukuran sebenarnya
- 1.3 Single-mode & multimode: pelebaran pulsa terhadap jarak
- 1.4 Kode warna TIA-598 dan pencari nomor core
- 1.5 Redaman: dB, dBm, tekukan, dan kalkulator anggaran FTTH dengan tiga penilaian terpisah: daya terima ONT, arah ONT ke OLT, dan rugi ODN kelas B+ (13–28 dB) dengan margin desain
- 1.6 Konektor SC/LC/FC/ST serta poles UPC/APC
- Kuis 9 soal

**Tahap 2 · Pengenalan alat** (`tahap-2/index.html`)

- 2.1 Alat potong & kupas: stripper 3 lubang dan cleaver (sudut belah serta cacat belahan)
- 2.2 Fusion splicer: bagian-bagiannya dan simulasi layar (pelurusan core vs cladding)
- 2.3 Bahan habis pakai: sleeve pelindung, alkohol IPA, tisu, dan lainnya
- 2.4 Alat ukur: VFL, OPM, dan OTDR dengan event yang bisa diketuk
- Kuis: cocokkan alat dengan pekerjaannya + 5 soal

**Tahap 3 · Praktik persiapan** (`tahap-3/index.html`)

- 3.1 Urutan kerja: susun 8 langkah persiapan kabel loose tube di closure
- 3.2 Mengupas: kaitan panjang kupas, panjang belah, dan panjang sleeve
- 3.3 Membersihkan: benar atau salah
- 3.4 Membelah: langkah memakai cleaver
- 3.5 Siap sambung: checklist sebelum masuk splicer
- Kuis 6 soal

**Tahap 4 · Penyambungan & finishing** (`tahap-4/index.html`)

- 4.1 Fusion splicing: langkah di splicer dan game menilai layar hasil sambungan
- 4.2 Memanaskan sleeve: posisi sleeve dan akibatnya bila tidak di tengah
- 4.3 Mechanical splice & fast connector: simulasi lengkungan serat, tabel perbandingan
- 4.4 Menata di tray: cari 5 kesalahan, plus tray yang benar
- 4.5 Menutup closure: checklist
- Kuis 6 soal

**Tahap 5 · Pengukuran** (`tahap-5/index.html`)

- 5.1 Konektor bersih dulu: game menilai tampilan inspection scope, cara membersihkan
- 5.2 OPM di pelanggan: ukur di port ODP, ujung drop, dan ONT; game menilai bacaan dBm
- 5.3 Light source & OPM: simulasi referensi (REF) dan ukur redaman jalur di 1310/1550 nm
- 5.4 VFL: game identifikasi core dan kebocoran di tray closure
- 5.5 Setelan OTDR: rentang, lebar pulsa, waktu rata-rata, kabel peluncur
- 5.6 Membaca OTDR: dua kursor untuk panjang jalur, redaman sambungan, dan dB/km
- Kuis 7 soal

**Tahap 6 · Troubleshooting & perawatan** (`tahap-6/index.html`)

- 6.1 Ukur mundur: simulasi 4 kasus gangguan pelanggan dengan OPM di 6 titik
- 6.2 Tanda gangguan di OTDR: game membaca jejak 1310/1550 nm (tekukan, sambungan buruk, konektor, putus, gainer)
- 6.3 Dari OTDR ke tiang: koreksi kabel peluncur, kelebihan panjang serat, dan gulungan cadangan
- 6.4 Sambungan gagal: game pesan error splicer
- 6.5 Membersihkan alat: cara membersihkan bagian splicer dan cleaver
- 6.6 Uji busur dan jadwal perawatan
- Kuis 7 soal

**Tahap 7 · Aplikasi lapangan** (`tahap-7/index.html`)

- 7.1 Cara kerja PON: animasi data ke pelanggan, dari pelanggan bergiliran, dan tabrakan bila tanpa giliran
- 7.2 Splitter: rancang splitter ODC dan ODP, lihat jumlah pelanggan dan daya di ONT
- 7.3 Perangkat di jalur: game menaruh OTB, closure, ODC, ODP, roset, ONT
- 7.4 Peta core: telusuri jalur tiap ODP dan jawab soal membaca peta core
- 7.5 Menghitung kebutuhan: ODP, splitter, port PON, dan ukuran kabel untuk satu perumahan
- 7.6 Simulasi pasang baru: delapan keputusan dari persiapan sampai dokumentasi
- Kuis 7 soal dan ringkasan nilai kuis ketujuh tahap (tersimpan di perangkat)

**Lampiran** (`lampiran/index.html`)

- L.1 Glosarium singkatan dengan pencarian
- L.2 Asumsi simulasi yang dipakai di semua tahap
- L.3 Sumber teknis dan tanggal pembaruan
- L.4 Lembar pencatatan praktik (tersimpan di peramban, bisa dicetak)
- L.5 Rubrik penilaian: K3, ketepatan core, kualitas sambungan, pengukuran, dokumentasi

**Fitur bersama semua halaman**

- Tujuan pembelajaran di awal Tahap 1
- Tombol "Lanjutkan belajar" ke posisi terakhir
- Status per tahap: materi dibaca, kuis dikerjakan, praktik dinilai
- Jawaban kuis sementara tidak hilang saat halaman dimuat ulang
- Navigasi bagian yang selalu terlihat, tombol setara untuk diagram OTDR (Tahap 2) dan tray (Tahap 4)

Progres disimpan di `localStorage` peramban, tidak dikirim ke mana pun.

Tiap tahap adalah satu file HTML mandiri tanpa dependensi selain Google Fonts.
Angka di dalamnya adalah patokan umum untuk belajar; di lapangan, ikuti datasheet perangkat dan standar operator.

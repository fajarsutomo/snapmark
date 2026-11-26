# Panduan SnapMark

SnapMark menangkap layar Windows dan memungkinkan Anda memberi anotasi yang **tetap bisa diedit** — kotak, panah, teks, sensor, dan lainnya adalah objek terpisah, bukan coretan di gambar. Gambar aslinya tidak pernah diubah.

[Bahasa lain / Other languages](../README.md)

## Daftar isi

1. [Memasang](#memasang)
2. [Menangkap layar](#menangkap-layar)
3. [Alat anotasi](#alat-anotasi)
4. [Pintasan keyboard](#pintasan-keyboard)
5. [Menyalin dan menyimpan](#menyalin-dan-menyimpan)
6. [Proyek dan riwayat](#proyek-dan-riwayat)
7. [Pengaturan](#pengaturan)
8. [Privasi](#privasi)
9. [Pemecahan masalah](#pemecahan-masalah)

## Memasang

Jalankan installer `SnapMark_x.y.z_x64-setup.exe`. Pemasangan hanya untuk akun Anda (tidak perlu hak administrator). Setelah selesai, SnapMark berjalan di **tray** (area ikon dekat jam). Jika ikonnya tidak terlihat, klik panah ^ untuk menampilkan ikon tersembunyi.

Klik kanan ikon tray untuk membuka menu: **Tangkap**, **Riwayat**, **Buka proyek…**, **Pengaturan**, **Keluar**.

## Menangkap layar

1. Tekan **Print Screen** (atau klik ikon tray, atau pilih **Tangkap**). Layar membeku sesaat; jika ada beberapa monitor, semuanya ikut tertangkap.
2. **Seret** untuk memilih area. Area bisa diubah kapan saja, juga setelah ada anotasi: seret **garis tepinya** untuk menggeser, seret **pegangan** di sudut/sisi untuk mengubah ukuran, atau seret di area gelap di luarnya untuk memilih ulang. Panah keyboard menggeser area; **Ctrl + panah** mengubah ukurannya; **Shift** membuat langkahnya 10 piksel.
3. Gunakan toolbar untuk menambahkan anotasi.
4. Tekan **Enter** untuk menyalin ke clipboard, atau **Ctrl+S** untuk menyimpan. **Esc** membatalkan.

Esc pertama membatalkan pilihan objek; Esc berikutnya menutup SnapMark.

## Alat anotasi

| Alat | Tombol | Catatan |
|---|---|---|
| Pilih & ubah | `V` | Klik objek untuk memilih; **Shift+klik** menambah/mengurangi pilihan. Seret untuk memindahkan, tarik pegangan untuk mengubah ukuran. |
| Kotak | `R` | **Shift** = persegi. Bisa diberi isi. |
| Elips | `E` | **Shift** = lingkaran. |
| Garis | `L` | **Shift** = kunci sudut 45°. Gaya: biasa, ganda, putus-putus. |
| Panah | `A` | **Shift** = 45°. Kepala di satu atau kedua ujung. |
| Pena bebas | `P` | Coretan bebas. |
| Stabilo | `H` | Penanda tembus pandang. |
| Sensor | `S` | Mozaik, blur, atau **blok hitam** (paling aman). Bentuk kotak atau kuas. |
| Angka langkah | `N` | Klik untuk menaruh 1, 2, 3… berurutan. |
| Teks | `T` | Latar bisa dipilih. **Ctrl+Enter** atau **Esc** menyelesaikan. |

Warna, ketebalan, ukuran font, dan tebal dapat diubah di toolbar; perubahan berlaku untuk objek yang sedang dipilih.

## Pintasan keyboard

| Tombol | Fungsi |
|---|---|
| `Enter` / `Ctrl+C` | Salin hasil ke clipboard |
| `Ctrl+S` | Simpan PNG ke folder simpan |
| `Ctrl+Shift+S` | Simpan sebagai… |
| `Ctrl+Alt+S` | Simpan proyek `.snapmark` |
| `Ctrl+Z` / `Ctrl+Y` (atau `Ctrl+Shift+Z`) | Urungkan / ulangi |
| `Ctrl+D` | Duplikat objek terpilih |
| `Ctrl+A` | Pilih semua objek |
| `Ctrl+]` / `Ctrl+[` | Ke depan / ke belakang |
| `Delete` / `Backspace` | Hapus objek terpilih |
| Panah (`Shift` = 10 px) | Geser objek terpilih; tanpa pilihan, geser area (dengan `Ctrl`: ubah ukuran area) |
| `Esc` | Batalkan pilihan, lalu tutup |

## Menyalin dan menyimpan

Hasilnya selalu **hanya area yang dipilih**, pada **resolusi asli layar**, persis seperti yang terlihat.

- **Salin** (Enter): masuk ke clipboard, siap ditempel.
- **Simpan** (Ctrl+S): langsung ke folder simpan dengan nama `snapmark_20261125_143005.png` (tanggal_jam). Nama yang sudah ada tidak ditimpa (diberi akhiran `_2`, `_3`, …). Folder bawaan: `Gambar\SnapMark`.
- **Simpan sebagai** (Ctrl+Shift+S): pilih nama dan folder sendiri.

Setelah berhasil menyalin atau menyimpan, SnapMark menutup otomatis.

## Proyek dan riwayat

**Proyek `.snapmark`** menyimpan gambar asli beserta semua anotasi sebagai objek, sehingga bisa dibuka dan diedit lagi nanti. Simpan dengan **Ctrl+Alt+S**; buka dengan klik dua kali file-nya, atau lewat tray → **Buka proyek…**.

> **Hati-hati dengan sensor.** Karena file proyek menyimpan gambar *asli*, bagian yang Anda sensor masih bisa dilihat oleh siapa pun yang membuka file itu. Untuk dibagikan, gunakan **Salin** atau **Simpan PNG**, yang hanya berisi hasil yang sudah disensor. SnapMark memberi peringatan sebelum menyimpan proyek yang berisi sensor.

**Riwayat**: setiap Salin/Simpan dicatat otomatis sebagai proyek yang bisa diedit lagi (50 terakhir secara bawaan, hanya di komputer ini). Buka lewat tray → **Riwayat**, lalu klik item untuk mengeditnya kembali.

## Pengaturan

Tray → **Pengaturan**.

| Pengaturan | Keterangan |
|---|---|
| Hotkey tangkap layar | Bawaan `Print Screen`. Klik **Ubah…**, lalu tekan kombinasi baru (pakai Ctrl/Alt/Win agar tidak mengganggu pengetikan). |
| Folder simpan | Tujuan Ctrl+S. |
| Bahasa | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, atau ikuti Windows. |
| Riwayat | Jumlah item yang disimpan (0 = mati, maksimal 500). |
| Mulai bersama Windows | SnapMark langsung siap sejak login. |
| Warna petunjuk | Warna teks instruksi saat memilih area. |
| Tema | Ikuti Windows, Terang, Gelap, atau Liquid Glass. |
| Pembaruan | Cek & pasang otomatis tiap 6 jam, atau tombol **Periksa sekarang**. |

Pembaruan diunduh dari rilis resmi, dipasang tanpa jendela installer, dan SnapMark terbuka lagi sendiri; pengaturan dan riwayat tetap. Pembaruan menunggu sampai Anda selesai mengedit.

## Privasi

- Tangkapan layar dan proyek **tidak pernah keluar dari komputer Anda**.
- Tidak ada telemetri. Satu-satunya akses jaringan adalah memeriksa pembaruan.

## Pemecahan masalah

**Print Screen tidak melakukan apa-apa / hotkey tidak aktif.** Windows 11 dapat memakai tombol itu untuk alat tangkapan layarnya sendiri. Di Pengaturan SnapMark klik **Buka pengaturan keyboard Windows**, lalu matikan opsi yang membuat tombol Print Screen membuka alat itu (nama dan letak opsinya berbeda-beda menurut versi Windows). Atau pilih hotkey lain.

**Ikon tray tidak terlihat.** Klik panah ^ di bilah tugas; seret ikon SnapMark keluar agar selalu tampak.

**Lokasi data.** Pengaturan: `%APPDATA%\app.snapmark.desktop\settings.json`. Riwayat: `%LOCALAPPDATA%\app.snapmark.desktop\history`.

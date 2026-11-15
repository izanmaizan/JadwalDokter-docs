# Jadwal Dokter

Papan informasi jadwal dokter yang mengambil data dari layanan antrean, dengan penanganan tanda tangan dan otorisasi otomatis.

## Kegunaan

- Menampilkan jadwal dokter pada layar informasi.
- Mengambil data jadwal dari layanan antrean resmi.
- Menyimpan dan menampilkan riwayat permintaan.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Bahasa | PHP |
| Integrasi | Layanan antrean dan vaksinasi |
| Fitur | Tanda tangan dan otorisasi dibuat otomatis |
| Infrastruktur | Docker, dipindah dari XAMPP |

## Alur singkat

1. Papan mengambil data jadwal dari layanan resmi.
2. Permintaan ditandatangani secara otomatis.
3. Hasil ditampilkan dalam bentuk jadwal per poli dan dokter.

## Ringkasan

| | |
|---|---|
| Status | Berjalan, dipindah ke Docker |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.

# Deteksi File Berbahaya - Berbasis python
## Tampilan Awal Program
Saat program dijalankan, pengguna disambut dengan antarmuka utama berwarna hitam dengan aksen emas, dilengkapi tombol:
- 📁 Pilih Folder
- 📄 Pilih File
- 🧾 Buat Laporan PDF

tampilan awal aplikasi:

![Image](https://github.com/user-attachments/assets/338e9838-a947-4cdd-939d-6458fe9e838d)

## Proses Analisis File
Setelah pengguna memilih satu atau beberapa file, aplikasi akan:
- Membaca file menggunakan library filetype.
- Membandingkan antara ekstensi asli dan ekstensi tertulis.
- Menentukan status file apakah Normal atau Disamarkan.
- Menampilkan metadata (ukuran, hash, waktu pembuatan, MIME type, dll) di tabel GUI.

Hasil analisis file pada GUI:

![Image](https://github.com/user-attachments/assets/7167bedc-8c51-4760-bec2-dcee4b809ce9)

## Pembuatan Laporan PDF
Setelah proses analisis selesai, pengguna dapat menekan tombol 🧾 Buat Laporan PDF. Sistem akan:
- Menghasilkan file PDF dengan nomor urut otomatis (laporan_deteksi_1.pdf, laporan_deteksi_2.pdf, dst).
- Menyimpan laporan di folder /reports/.
- Menampilkan tabel hasil deteksi dan metadata lengkap di halaman terpisah.

PDF memiliki desain header hitam-emas, tabel terformat rapi, serta footer berisi waktu pembuatan dan nomor halaman.

Contoh hasil laporan PDF:

![Image](https://github.com/user-attachments/assets/273163b3-bb7d-410f-83ec-5c0fa330b19e)

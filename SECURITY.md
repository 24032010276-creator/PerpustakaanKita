Keamanan Proyek — Perpustakaan Kita

Ringkasan langkah keamanan yang sudah diterapkan:
- Kredensial demo di UI dihapus.
- Literal password default di JavaScript diganti dengan `REDACTED_DEMO_PASSWORD` untuk mencegah eksposur casual.

Rekomendasi tambahan sebelum produksi:
- Jangan menyimpan password atau data sensitif di `localStorage` untuk aplikasi produksi.
- Gunakan backend/API dengan penyimpanan terenkripsi untuk data pengguna nyata.
- Tambahkan instruksi clear-password/reset untuk admin jika fitur user management ditambahkan.

Jika Anda menginginkan, saya bisa:
- Menambahkan halaman dokumentasi singkat (`README.md`) dengan instruksi deploy & keamanan (saya sudah menambahkan `PUBLISHING.md`).
- Menghapus file backup (`MOMO.html`) dari repo publik jika Anda ingin repo hanya menyertakan `index.html`.

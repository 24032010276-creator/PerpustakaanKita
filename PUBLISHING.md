Perpustakaan Kita — Petunjuk Publikasi

Ringkasan:
- Situs ini di-publish menggunakan GitHub Pages di branch `gh-pages`.
- URL publik: https://24032010276-creator.github.io/PerpustakaanKita/

Langkah pengujian dari device lain:
1. Buka URL di peramban biasa pada device lain (HP/Laptop lain). Jika situs tidak muncul, tunggu beberapa menit karena propagation.
2. Jika perlu menguji fitur penyimpanan (localStorage), buka Developer Tools → Application → Local Storage untuk melihat data.

Keamanan & catatan penting:
- Kredensial demo telah dihapus dari UI dan literal password di JavaScript diganti menjadi placeholder `REDACTED_DEMO_PASSWORD`.
- Jangan masukkan data sensitif nyata dalam demo karena situs statis ini menyimpan data di localStorage pada browser pengguna.

Bagaimana mengembalikan akun demo (developer/testing):
- Anda dapat menambahkan user/password pada `localStorage` di browser secara manual atau membuat endpoint dev untuk mengisi data pada pengujian lokal.
- Atau tambahkan skrip pengisi di console saat menguji: 
  localStorage.setItem('userPasswords', JSON.stringify({'1':'1LANGKAHDIDEPAN','wawa':'wawaalpat'}));

Butuh bantuan lain? Laporkan ke pemilik repo.
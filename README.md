# Jobsheet-01

## Pertanyaan
1. Kenapa field "Alamat" dan "No. HP" tidak diberi required, sedangkan "Nama" dan "No.
Anggota" diberi?
2. Apa yang akan terjadi (di browser) kalau kamu klik tombol "Simpan" tanpa mengisi field
"Nama"? Coba buka filenya di browser dan praktikkan.
3. Form ini juga belum punya action pada tag <form>-nya — apa dampaknya saat tombol
"Simpan" ditekan?

### Jawaban
1. karena keduanya merupakan data utama (krusial) yang menjadi identitas wajib bagi seorang anggota perpustakaan.
2. Browser akan memunculkan pesan peringatan atau tooltip seperti "Harap isi bidang ini" (Please fill out this field) tepat di kotak input "Nama", dan halaman tidak akan dimuat ulang.
3. saat tombol diklik, browser hanya akan memuat ulang (refresh) halaman itu sendiri, dan data yang diisi mungkin hanya akan menempel sementara sebagai parameter di alamat web tanpa di proses
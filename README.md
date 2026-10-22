# Pantau Tabungan Pelajar — SMPN 4 Majenang

Aplikasi web untuk memantau dan merekap simpanan murid kelas 7, 8, dan 9.

- Membaca data langsung dari spreadsheet **Tabungan Pelajar 7, 8, dan 9** (tab `Users` dan `Transactions`) melalui gviz JSONP.
- Bila data langsung tidak dapat dimuat (mis. berkas belum dibagikan sebagai "Pelihat tautan"), aplikasi menampilkan **snapshot terakhir** yang tertera pada label status di bagian atas.
- Fitur: ringkasan keseluruhan dan per jenjang, rekap per kelas, pencarian murid (nama/NIS) dengan saring jenjang/kelas, dan daftar murid terdaftar yang belum bertransaksi.
- Akun demo (NIS 1111) tidak ikut dihitung.

Berkas: `index.html` (satu berkas, tanpa dependensi).

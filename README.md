
🔗 Judul Proyek: Analisis Data Inventaris Barang
📁 Deskripsi Singkat
Proyek ini merupakan bagian dari latihan analisis data menggunakan Microsoft Excel, yang mencakup:

Ekstraksi data dari kode barang.

Perhitungan tahun perkiraan perbaikan berdasarkan kode dan masa fungsi.

Klasifikasi fakultas berdasarkan kode unit.

Penggunaan fungsi COUNTIF, SUMIF, dan logika IF untuk membuat ringkasan data otomatis.

Pembuatan dashboard ringkas dengan data validasi dan referensi.

🎯 Tujuan Proyek
Melatih penggunaan rumus Excel lanjutan seperti MID(), LEFT(), COUNTIF(), SUMIF(), dan IF().

Mengelompokkan dan menganalisis data berdasarkan kode unit fakultas.

Menentukan jumlah barang dan biaya berdasarkan kategori.

🧠 Keterampilan yang Digunakan
Microsoft Excel (Rumus, Tabel, Logika)

Analisis data dasar

Pengelompokan dan visualisasi data

📌 Contoh Rumus yang Digunakan
excel
Copy
Edit
=LEFT(A2,2)+D2    --> Menghitung tahun perkiraan perbaikan
=IF(B2=520,"FTI",IF(B2=310,"FE","FK"))  --> Menentukan fakultas dari kode unit
=COUNTIF(range,kriteria) --> Menghitung jumlah item per fakultas
=SUMIF(range,kriteria,sum_range) --> Menjumlahkan harga per fakultas

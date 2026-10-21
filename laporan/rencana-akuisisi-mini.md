# Laporan Rencana Akuisisi Mini

## Arsip Digital Sanggar Tari

### 1. Latar Belakang

Sanggar tari memiliki berbagai dokumentasi, seperti catatan kegiatan, foto latihan, rekaman musik, dan video pertunjukan. Jika tidak dikelola dengan baik, arsip dapat sulit ditemukan atau hilang. Oleh karena itu, diperlukan rencana akuisisi data untuk menyimpan dan mengelola arsip secara digital.

### 2. Jenis dan Karakteristik Data

| Jenis Data   | Format         | Karakteristik                                           | Ukuran per Unit | Jumlah |
| ------------ | -------------- | ------------------------------------------------------- | --------------- | -----: |
| Dokumen teks | TXT, CSV, JSON | Informasi kegiatan, nama penari, tanggal, dan deskripsi | 2 KB            |  2.000 |
| Foto         | JPG, PNG       | Resolusi, dimensi gambar, dan tingkat kompresi          | 3 MB            |  1.000 |
| Audio        | MP3, WAV       | Durasi, frekuensi sampling, dan jumlah kanal            | 20 MB           |    100 |
| Video        | MP4, MOV       | Resolusi, frame rate, codec, dan durasi                 | 500 MB          |    100 |
| Model 3D     | OBJ, PLY, STL  | Jumlah titik, permukaan, dan tekstur                    | 50 MB           |     20 |
| Data lokasi  | GeoJSON        | Koordinat, geometri, dan sistem koordinat               | 1 KB            |     10 |

### 3. Asumsi Akuisisi Data

Jumlah data dan ukuran file pada tabel merupakan asumsi perencanaan. Data diperoleh dari dokumentasi kegiatan sanggar, foto, rekaman musik, video pertunjukan, serta informasi lokasi. Setiap arsip diberi metadata, seperti nama kegiatan, tanggal, jenis data, sumber, dan keterangan.

### 4. Estimasi Kebutuhan Penyimpanan

Berdasarkan asumsi jumlah dan ukuran setiap jenis data, diperoleh estimasi berikut:

* Dokumen teks: sekitar 0,0038 GB
* Foto: sekitar 2,93 GB
* Audio: sekitar 1,95 GB
* Video: sekitar 48,83 GB
* Model 3D: sekitar 0,98 GB
* Data lokasi: sangat kecil, sekitar 0,00001 GB

Total kebutuhan penyimpanan awal sekitar 54,69 GB. Cadangan 30% adalah sekitar 16,41 GB. Dengan demikian, kapasitas penyimpanan yang perlu disiapkan sekitar 71,10 GB.

### 5. Rencana Pengelolaan Arsip

Arsip dikelompokkan berdasarkan jenis data dan kegiatan. Nama file dibuat konsisten, misalnya `latihan_tari_2026-10-21.jpg`. Metadata digunakan agar arsip mudah dicari. Salinan cadangan juga perlu dibuat untuk mengurangi risiko kehilangan data.

### 6. Kesimpulan

Rencana akuisisi ini membantu sanggar tari mengelola arsip secara lebih terstruktur. Video menjadi jenis data dengan kebutuhan penyimpanan terbesar. Berdasarkan asumsi yang digunakan, kapasitas sekitar 71,10 GB perlu disiapkan termasuk cadangan 30%.

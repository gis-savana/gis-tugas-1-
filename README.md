# gis-tugas-1-
## File **`export (1).geojson`** berisi data geospasial berbentuk **LineString** yang menggambarkan satu jalur jalan di wilayah desa atau kelurahan. Data ini dibuat melalui situs [geojson.io](https://geojson.io) dengan menggambar langsung jalur jalan pada peta, lalu disimpan dalam format GeoJSON. File ini digunakan untuk keperluan pemetaan dan dapat disimpan di **MongoDB** dengan aturan satu jalan satu record. Tujuan pembuatan file ini adalah untuk memahami struktur data GeoJSON serta penerapannya dalam sistem informasi geografis (SIG) dan aplikasi peta digital.
🧭 Cara Pembuatan

Membuka situs geojson.io

Menentukan lokasi desa/kelurahan pada peta

Menggunakan ikon “Draw a line” (gambar garis miring di sisi kanan peta) untuk menggambar jalan

Menyimpan hasil dalam format .geojson

Mengecek hasil agar tidak ada kesalahan sintaks dan format

💾 Penyimpanan

File disimpan dengan nama export (1).geojson

Data berisi satu jalur jalan (1 LineString) dari satu desa atau kelurahan

Dapat dimasukkan ke dalam database MongoDB dengan aturan:
👉 1 jalan = 1 record (dokumen)

📘 Tujuan

Tugas ini bertujuan untuk:

Mengenal format GeoJSON dan penggunaannya dalam sistem informasi geografis (SIG)

Memahami struktur data geospasial dalam format JSON

Mempersiapkan data untuk penyimpanan dan visualisasi di aplikasi berbasis peta (misalnya Leaflet atau Mapbox)

🧩 Tools yang Digunakan

geojson.io
 untuk menggambar peta dan menghasilkan GeoJSON

GitHub
 untuk menyimpan dan mendokumentasikan file

(Opsional) MongoDB untuk menyimpan data jalan

# UAP


# Aplikasi Klasifikasi Gambar dengan Flask

Repositori ini berisi contoh sederhana implementasi model klasifikasi gambar menggunakan Flask. Model dilatih menggunakan Mobilenet untuk mengklasifikasikan gambar ke dalam tiga kelas. Aplikasi web memungkinkan pengguna mengunggah gambar dan mendapatkan prediksi secara real-time.

## Struktur Proyek
|- static
|- templates
|- app.py
|- model.h5
|- README.md


## Dependensi
Pastikan untuk menginstal library yang dibutuhkan sebelum menjalankan aplikasi:
```bash
pip install flask tensorflow
```

## Pelatihan Model
Model klasifikasi gambar dilatih menggunakan MobileNetV. Model disimpan sebagai model.h5. Sesuaikan jumlah unit keluaran di lapisan terakhir dan fungsi aktivasi sesuai dengan jumlah kelas.

![image](https://github.com/Arlana00/Modul6/assets/72141320/cbb4f410-c639-44d8-af62-846b9f743381)


## Aplikasi Flask
Aplikasi web Flask (main.py) berfungsi sebagai antarmuka untuk model klasifikasi gambar. Aplikasi menggunakan model yang disimpan untuk membuat prediksi pada gambar yang diunggah oleh pengguna.

## Cara Menjalankan

```bash
Copy code
python app.py
Buka browser dan akses
http://127.0.0.1:5000/.
Anda dapat mengunggah gambar dan mendapatkan prediksi.
```
![Screenshot (81)](https://github.com/Arlana00/Modul6/assets/72141320/cf87d06d-5eb5-4fd5-a661-cab8a085ace6)


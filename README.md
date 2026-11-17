# Tugas 1 Komputasi Numerik
## Penyelesaian SPL Tiga Variabel Menggunakan Metode Eliminasi Gauss

Repository ini berisi dokumentasi dan implementasi tugas 1 mata kuliah **Komputasi Numerik**, yaitu penyelesaian Sistem Persamaan Linear (SPL) tiga variabel menggunakan metode **Eliminasi Gauss** dengan bahasa pemrograman Python.

---
## Video Demonstrasi

Video demonstrasi pengerjaan tugas, implementasi program, dan penjelasan hasil dapat diakses melalui tautan berikut:

**[Tonton Video Demonstrasi Komputasi Numerik](https://drive.google.com/file/d/1-27iGWx4S8PXgZ-5B1g43TgrSA3BehyW/view?usp=sharing)**

## Identitas Mahasiswa

| Keterangan | Informasi |
|---|---|
| Nama | M. Irfan Mubarok |
| NIM | 202511420111 |
| Program Studi | Teknik Informatika |
| Mata Kuliah | Komputasi Numerik |
| Institusi | Universitas Dr. Soetomo |

## Deskripsi Tugas

Tujuan pengerjaan tugas ini adalah menerapkan metode numerik untuk menyelesaikan sistem persamaan linear tiga variabel melalui algoritma dan implementasi program Python.

Metode Eliminasi Gauss digunakan untuk mengubah matriks augmented menjadi bentuk segitiga atas melalui operasi baris elementer. Selanjutnya, nilai setiap variabel diperoleh menggunakan proses substitusi balik.

Implementasi dibuat menggunakan Google Colab dengan struktur kode yang dibagi ke dalam beberapa cell agar dapat dijalankan secara berurutan. Setiap bagian program juga dilengkapi penjelasan mengenai proses dan fungsi kode.

## Permasalahan

Sistem persamaan linear yang diselesaikan adalah:

Persamaan 1: 2t + u + 3v = 1

Persamaan 2: 4t + 3u + v = 13

Persamaan 3: -2t + 5u + 2v = -5

## Metode Penyelesaian

Metode yang digunakan adalah **Eliminasi Gauss**, dengan tahapan sebagai berikut:

1. Memasukkan koefisien dan konstanta persamaan ke dalam matriks augmented.
2. Menentukan elemen pivot sebagai dasar proses eliminasi.
3. Melakukan pertukaran baris apabila diperlukan.
4. Melakukan operasi baris elementer untuk menghilangkan elemen di bawah pivot.
5. Membentuk matriks segitiga atas.
6. Memeriksa jenis solusi sistem persamaan.
7. Melakukan substitusi balik untuk memperoleh nilai variabel apabila solusi tunggal ditemukan.
8. Melakukan validasi hasil dengan persamaan awal.

## Struktur Repository

```text
Komputasi-Numerik/
│
├── Algoritma SPL 3 variabel.txt
├── Link Akun.txt
├── Prompt tugas 1.txt
├── SPL_3_Variabel_v1.ipynb
├── LICENSE
└── README.md
```

**Keterangan file:**

- `Algoritma SPL 3 variabel.txt` — Dokumentasi tahapan algoritma penyelesaian SPL tiga variabel.
- `Link Akun.txt` — File pendukung.
- `Prompt tugas 1.txt` — Dokumentasi prompt yang digunakan dalam proses pengembangan tugas.
- `SPL_3_Variabel_v1.ipynb` — Implementasi metode Eliminasi Gauss menggunakan Python di Google Colab.
- `LICENSE` — Informasi lisensi repository.
- `README.md` — Dokumentasi utama repository.

## Cara Menjalankan Program

Program dapat dijalankan melalui Google Colab tanpa perlu melakukan instalasi lingkungan Python secara lokal.

1. Buka file `SPL_3_Variabel_v1.ipynb` pada repository ini.
2. Pilih opsi **Open in Colab** atau buka melalui tautan berikut:

   [Buka Notebook di Google Colab](https://colab.research.google.com/github/mirfanmbrk/Komputasi-Numerik/blob/main/SPL_3_Variabel_v1.ipynb)

3. Jalankan setiap cell secara berurutan dari bagian paling atas.
4. Amati proses eliminasi, substitusi balik, dan hasil validasi yang ditampilkan oleh program.

## Hasil Penyelesaian

Berdasarkan implementasi metode Eliminasi Gauss, diperoleh hasil:

| Variabel | Nilai |
|---|---:|
| t | 3 |
| u | 1 |
| v | -2 |

Dengan demikian, solusi sistem persamaan linear tersebut adalah:

t = 3, u = 1, dan v = -2.

## Validasi Hasil

Validasi dilakukan dengan memasukkan kembali nilai variabel yang diperoleh ke dalam persamaan awal.

- Persamaan pertama: \(2(3)+1+3(-2)=1\)
- Persamaan kedua: \(4(3)+3(1)+(-2)=13\)
- Persamaan ketiga: \(-2(3)+5(1)+2(-2)=-5\)

Seluruh hasil substitusi sesuai dengan konstanta pada persamaan awal. Oleh karena itu, solusi yang diperoleh dinyatakan valid.

## Penutup

Melalui tugas ini, metode Eliminasi Gauss diterapkan untuk menyelesaikan sistem persamaan linear tiga variabel secara terstruktur menggunakan Python. Proses pengerjaan mencakup penyusunan algoritma, implementasi program, serta pengujian kembali hasil perhitungan untuk memastikan kebenaran solusi.

**M. Irfan Mubarok**  
**202511420111**

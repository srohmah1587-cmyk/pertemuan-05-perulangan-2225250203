# Pertemuan 05 Perulangan Python

**Nama:** Siti Rohmah
**NIM:** 2225250203
**Kelas:** 3A

## Tujuan

Menggunakan perulangan `for` dan `while` dalam Python untuk menyelesaikan masalah yang membutuhkan proses berulang secara terstruktur dan efisien.

## Cara Menjalankan

Program dapat dijalankan melalui terminal dengan perintah:

```bash
python3 kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

Langkah-langkah perulangan untuk menyelesaikan program deret aritmetika adalah sebagai berikut:

1. Memulai program.
2. Memasukkan nilai suku pertama (`a`).
3. Memasukkan nilai beda antar suku (`b`).
4. Memasukkan jumlah suku (`n`).
5. Melakukan perulangan sebanyak `n` kali.
6. Pada setiap perulangan, menampilkan nilai suku deret aritmetika.
7. Menghitung suku berikutnya dengan menambahkan beda (`b`) pada suku sebelumnya.
8. Setelah jumlah perulangan mencapai `n`, perulangan berhenti.
9. Menampilkan hasil deret aritmetika.
10. Program selesai.

## Hasil Pengujian

| No. | Input                 | Keluaran yang Diharapkan | Keluaran Aktual | Status   |
| --- | --------------------- | ------------------------ | --------------- | -------- |
| 1   | a = 2, b = 3, n = 5   | 2, 5, 8, 11, 14          | 2, 5, 8, 11, 14 | Berhasil |
| 2   | a = 10, b = -2, n = 4   | 10, 8, 6, 4              | 5, 7, 9, 11     | Berhasil |
| 3   | a = 1.5, b = 0.5, n = 3 | 1.5, 2.0, 2.5           | 10, 8, 6, 4, 2  | Berhasil |

## Refleksi

Kesalahan perulangan yang ditemukan adalah jumlah perulangan tidak sesuai dengan jumlah suku yang diinginkan. Hal ini dapat terjadi karena batas perulangan pada `for` kurang tepat, sehingga program dapat menghasilkan suku terlalu banyak atau terlalu sedikit.

Cara memperbaikinya adalah memastikan batas perulangan menggunakan nilai `n` sesuai dengan jumlah suku yang ingin ditampilkan. Selain itu, nilai suku harus diperbarui setelah setiap proses perulangan dengan menambahkan nilai beda (`b`).

Dari praktikum ini, saya memahami bahwa perulangan `for` dapat digunakan ketika jumlah pengulangan sudah diketahui, sedangkan `while` lebih sesuai ketika perulangan bergantung pada suatu kondisi.

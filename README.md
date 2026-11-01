# Pertemuan 14 - Perancangan Proyek Rekap Kehadiran Siswa

Repository ini berisi tugas proyek mata kuliah Algoritma dan Pemrograman tentang perancangan program sederhana menggunakan Python dengan proyek Rekap Kehadiran Siswa.

## Identitas Mahasiswa

- **Nama:** Aulia Nurrizqi
- **NIM:** 2225250160
- **Kelas:** 3A
- **Program Studi:** S1 Pendidikan Matematika
- **Mata Kuliah:** Algoritma dan Pemrograman

## Tujuan Proyek

1. Merancang program sederhana menggunakan bahasa Python.
2. Mengidentifikasi masalah dalam pencatatan kehadiran siswa.
3. Menentukan kebutuhan input, proses, dan output program.
4. Membuat algoritma atau pseudocode program.
5. Merancang struktur folder dan fungsi program.
6. Menentukan test case untuk pengujian program.
7. Menggunakan VS Code, Git, dan GitHub untuk mengelola proyek.

## Deskripsi Proyek

Proyek Rekap Kehadiran Siswa merupakan program sederhana berbasis Python yang dirancang untuk membantu proses pencatatan dan pengelolaan data kehadiran siswa.

Program ini dapat digunakan untuk mencatat status kehadiran siswa, menghitung jumlah kehadiran, serta menghasilkan rekap data kehadiran secara otomatis.

## Fitur Program

1. Menambahkan data siswa.
2. Mencatat kehadiran siswa.
3. Menentukan status hadir, izin, sakit, dan alpa.
4. Menampilkan seluruh data kehadiran siswa.
5. Menghitung jumlah kehadiran berdasarkan status.
6. Menghitung persentase kehadiran siswa.
7. Menyimpan data ke dalam file.

## Struktur Folder

```text
rekap-kehadiran-siswa/
├── README.md
├── proposal.md
├── .gitignore
├── data/
│   └── data_kehadiran.txt
├── src/
│   ├── main.py
│   ├── data_siswa.py
│   ├── absensi.py
│   └── laporan.py
├── tests/
│   └── test_case.md
└── output/
    └── .gitkeep
```

## Input, Proses, dan Output

**Input:**
- Nama siswa.
- Nomor identitas siswa.
- Status kehadiran siswa.

**Proses:**
- Menyimpan data siswa.
- Memvalidasi status kehadiran.
- Menghitung jumlah hadir, izin, sakit, dan alpa.
- Menghitung persentase kehadiran.

**Output:**
- Daftar kehadiran siswa.
- Rekap jumlah kehadiran.
- Persentase kehadiran siswa.
- Laporan kehadiran dalam bentuk file.

## Status Kehadiran

| Kode | Keterangan |
|---|---|
| H | Hadir |
| I | Izin |
| S | Sakit |
| A | Alpa |

## Struktur Fungsi Program

- `tambah_siswa()` untuk menambahkan data siswa.
- `catat_kehadiran()` untuk mencatat status kehadiran.
- `tampilkan_data()` untuk menampilkan data siswa.
- `hitung_rekap()` untuk menghitung jumlah kehadiran.
- `hitung_persentase()` untuk menghitung persentase kehadiran.
- `simpan_data()` untuk menyimpan data ke dalam file.
- `main()` untuk menjalankan program utama.

## Test Case

| ID | Input/Kondisi | Hasil yang Diharapkan |
|---|---|---|
| TC01 | Menambahkan data siswa valid | Data berhasil ditambahkan |
| TC02 | Mencatat status H | Status hadir tersimpan |
| TC03 | Mencatat status I | Status izin tersimpan |
| TC04 | Mencatat status S | Status sakit tersimpan |
| TC05 | Mencatat status A | Status alpa tersimpan |
| TC06 | Memasukkan status tidak valid | Muncul pesan kesalahan |
| TC07 | Menampilkan rekap kehadiran | Rekap ditampilkan dengan benar |
| TC08 | Menyimpan data ke file | Data berhasil disimpan |

## Cara Menjalankan Program

Pastikan Python 3 sudah terpasang di komputer.

Buka folder proyek menggunakan Visual Studio Code, kemudian buka terminal dan jalankan perintah:

```bash
python src/main.py
```

Ikuti petunjuk yang ditampilkan pada terminal.

## Tools yang Digunakan

- **Python 3** - Bahasa pemrograman.
- **Visual Studio Code** - Editor untuk menulis kode.
- **Git** - Mengelola perubahan program.
- **GitHub** - Menyimpan dan mengelola repository proyek.

## Kesimpulan

Perancangan proyek Rekap Kehadiran Siswa bertujuan untuk menghasilkan program sederhana yang dapat membantu pencatatan dan pengelolaan kehadiran siswa. Melalui proyek ini, mahasiswa dapat menerapkan konsep Python, seperti list, dictionary, fungsi, validasi input, dan file handling. Rancangan ini akan menjadi dasar untuk proses implementasi, pengujian, dan dokumentasi pada Pertemuan 15.

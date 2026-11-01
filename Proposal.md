# PROPOSAL PROYEK

# PROGRAM REKAP KEHADIRAN SISWA BERBASIS PYTHON

**Mata Kuliah:** Algoritma dan Pemrograman
**Program Studi:** S1 Pendidikan Matematika
**Fakultas:** Keguruan dan Ilmu Pendidikan
**Universitas:** Universitas Sultan Ageng Tirtayasa
**Tahun Ajaran:** 2026/2027 Ganjil

---

# 1. JUDUL PROYEK

**Program Rekap Kehadiran Siswa Berbasis Python**

# 2. LATAR BELAKANG

Kehadiran siswa merupakan salah satu aspek penting dalam kegiatan pembelajaran di sekolah. Data kehadiran digunakan oleh guru untuk mengetahui tingkat kedisiplinan dan keaktifan siswa dalam mengikuti kegiatan pembelajaran. Setiap hari guru perlu mencatat kehadiran siswa berdasarkan kategori hadir, izin, sakit, dan alpa.

Dalam proses pencatatan secara manual, guru sering mengalami kesulitan ketika harus merekap data kehadiran dalam jumlah banyak. Selain membutuhkan waktu, pencatatan manual juga berisiko menimbulkan kesalahan dalam menghitung jumlah kehadiran siswa.

Berdasarkan permasalahan tersebut, diperlukan sebuah program sederhana berbasis Python yang dapat membantu proses pencatatan dan rekapitulasi kehadiran siswa secara otomatis. Program ini dirancang untuk memasukkan data siswa, mencatat status kehadiran, menghitung jumlah kehadiran berdasarkan kategori, serta menyimpan hasil rekap ke dalam file teks.

Dengan adanya program ini, diharapkan proses pengelolaan data kehadiran siswa menjadi lebih mudah, cepat, teratur, dan mengurangi kesalahan dalam perhitungan.

# 3. PENGGUNA DAN TUJUAN

## A. Pengguna

Pengguna utama program ini adalah guru atau wali kelas yang bertugas mencatat dan mengelola data kehadiran siswa.

## B. Tujuan

1. Mempermudah guru dalam mencatat kehadiran siswa.
2. Mengelola data kehadiran berdasarkan kategori hadir, izin, sakit, dan alpa.
3. Menghitung jumlah kehadiran setiap siswa secara otomatis.
4. Mengetahui jumlah siswa berdasarkan kategori kehadiran.
5. Menampilkan persentase kehadiran siswa.
6. Menyimpan hasil rekap kehadiran dalam bentuk file teks.
7. Membantu guru memperoleh informasi kehadiran siswa secara lebih sistematis.

# 4. RUANG LINGKUP PROYEK

## A. Fitur Wajib

1. Menambahkan data nama siswa.
2. Menampilkan daftar siswa yang telah dimasukkan.
3. Mencatat kehadiran siswa berdasarkan kategori hadir, izin, sakit, dan alpa.
4. Memvalidasi kategori kehadiran yang dimasukkan pengguna.
5. Menghitung jumlah kehadiran setiap siswa.
6. Menghitung total siswa berdasarkan kategori kehadiran.
7. Menghitung persentase kehadiran siswa.
8. Menampilkan hasil rekap kehadiran.
9. Menyimpan laporan kehadiran ke dalam file teks.

## B. Batasan Proyek

1. Program dibuat menggunakan bahasa pemrograman Python.
2. Program dijalankan melalui terminal atau console pada VS Code.
3. Data siswa yang digunakan merupakan data contoh.
4. Program tidak menggunakan database atau layanan eksternal.
5. Status kehadiran terdiri atas empat kategori, yaitu hadir, izin, sakit, dan alpa.
6. Data disimpan menggunakan file teks sederhana.
7. Program digunakan untuk pengelolaan kehadiran dalam satu kelas.

# 5. ANALISIS KEBUTUHAN

## A. Kebutuhan Fungsional

| Kode | Kebutuhan Fungsional                                          | Prioritas |
| ---- | ------------------------------------------------------------- | --------- |
| F01  | Program dapat menambahkan nama siswa.                         | Wajib     |
| F02  | Program dapat menampilkan daftar siswa.                       | Wajib     |
| F03  | Program dapat mencatat status kehadiran siswa.                | Wajib     |
| F04  | Program dapat memvalidasi kategori kehadiran.                 | Wajib     |
| F05  | Program dapat menghitung jumlah hadir, izin, sakit, dan alpa. | Wajib     |
| F06  | Program dapat menghitung persentase kehadiran.                | Wajib     |
| F07  | Program dapat menampilkan hasil rekap kehadiran.              | Wajib     |
| F08  | Program dapat menyimpan laporan ke file teks.                 | Wajib     |

## B. Kebutuhan Nonfungsional

1. Program mudah dijalankan melalui terminal VS Code.
2. Tampilan program sederhana dan mudah dipahami.
3. Pesan kesalahan ditampilkan dengan jelas.
4. Nama fungsi dan variabel menggunakan istilah yang mudah dimengerti.
5. Program dapat digunakan kembali untuk mencatat kehadiran pada pertemuan berikutnya.
6. Data yang digunakan dapat diuji menggunakan beberapa kondisi input.

# 6. SPESIFIKASI INPUT, PROSES, DAN OUTPUT (IPO)

| Komponen | Keterangan                                                                                                           |
| -------- | -------------------------------------------------------------------------------------------------------------------- |
| Input    | Nama siswa, tanggal kehadiran, dan status kehadiran.                                                                 |
| Proses   | Memvalidasi data, mencatat status kehadiran, menghitung jumlah setiap kategori, dan menghitung persentase kehadiran. |
| Output   | Daftar kehadiran siswa, jumlah hadir, izin, sakit, alpa, persentase kehadiran, dan laporan.txt.                      |

## Contoh IPO

**Input:**

* Nama siswa: Andi, Budi, Citra.
* Tanggal: 01 November 2026.
* Status kehadiran: Hadir, Izin, Hadir.

**Proses:**

* Program menerima data nama siswa.
* Program menerima status kehadiran.
* Program memvalidasi status kehadiran.
* Program menghitung jumlah setiap kategori.
* Program menghitung persentase kehadiran.

**Output:**

* Jumlah hadir: 2 siswa.
* Jumlah izin: 1 siswa.
* Jumlah sakit: 0 siswa.
* Jumlah alpa: 0 siswa.
* Persentase kehadiran: 66,67%.

# 7. ALGORITMA DAN PSEUDOCODE

## A. Algoritma Program

1. Mulai program.
2. Menampilkan menu utama.
3. Pengguna memilih menu yang tersedia.
4. Jika memilih menu tambah siswa, pengguna memasukkan nama siswa.
5. Jika memilih menu catat kehadiran, pengguna memilih siswa dan memasukkan tanggal serta status kehadiran.
6. Program memvalidasi status kehadiran.
7. Jika status tidak sesuai, program menampilkan pesan kesalahan.
8. Jika status sesuai, data kehadiran disimpan.
9. Jika memilih menu rekap, program menghitung jumlah hadir, izin, sakit, dan alpa.
10. Program menghitung persentase kehadiran.
11. Program menampilkan hasil rekap.
12. Jika memilih menu simpan laporan, program menyimpan hasil ke file teks.
13. Jika memilih menu keluar, program dihentikan.
14. Selesai.

## B. Pseudocode

```text
MULAI

BUAT daftar_siswa
BUAT data_kehadiran

ULANGI:
    TAMPILKAN MENU UTAMA
    1. Tambah Siswa
    2. Catat Kehadiran
    3. Tampilkan Rekap
    4. Simpan Laporan
    5. Keluar

    INPUT pilihan

    JIKA pilihan = 1:
        INPUT nama_siswa
        SIMPAN nama_siswa

    JIKA pilihan = 2:
        INPUT tanggal
        PILIH siswa
        INPUT status_kehadiran

        JIKA status tidak sesuai:
            TAMPILKAN pesan kesalahan
        JIKA status sesuai:
            SIMPAN data_kehadiran

    JIKA pilihan = 3:
        HITUNG jumlah hadir
        HITUNG jumlah izin
        HITUNG jumlah sakit
        HITUNG jumlah alpa
        HITUNG persentase kehadiran
        TAMPILKAN hasil rekap

    JIKA pilihan = 4:
        SIMPAN laporan ke file teks
        TAMPILKAN pesan berhasil

    JIKA pilihan = 5:
        KELUAR DARI PROGRAM

SAMPAI pilihan = 5

SELESAI
```

# 8. STRUKTUR PROGRAM DAN MODULARISASI

Program dibagi menjadi beberapa fungsi agar setiap bagian memiliki tugas yang jelas dan memudahkan proses pengujian serta pengembangan.

| Nama Fungsi         | Tanggung Jawab                                  |
| ------------------- | ----------------------------------------------- |
| tambah_siswa()      | Menambahkan data siswa ke dalam daftar.         |
| tampilkan_siswa()   | Menampilkan seluruh data siswa.                 |
| catat_kehadiran()   | Mencatat status kehadiran siswa.                |
| validasi_status()   | Memeriksa kategori kehadiran.                   |
| hitung_rekap()      | Menghitung jumlah hadir, izin, sakit, dan alpa. |
| hitung_persentase() | Menghitung persentase kehadiran siswa.          |
| simpan_laporan()    | Menyimpan hasil rekap ke file teks.             |
| main()              | Mengatur jalannya program dan menu utama.       |

## Struktur Folder Proyek

```text
rekap-kehadiran-siswa/
│
├── README.md
├── proposal.md
├── .gitignore
│
├── data/
│   └── siswa_contoh.txt
│
├── src/
│   ├── main.py
│   ├── data_siswa.py
│   ├── kehadiran.py
│   └── laporan.py
│
├── tests/
│   └── test_case.md
│
└── output/
    └── .gitkeep
```

Struktur folder tersebut digunakan untuk memisahkan kode program, data siswa, pengolahan kehadiran, dokumentasi, dan hasil laporan.

# 9. STRUKTUR DATA

Struktur data yang digunakan dalam proyek ini adalah:

**1. List**

Digunakan untuk menyimpan kumpulan data siswa dan data kehadiran.

**2. Dictionary**

Digunakan untuk menyimpan informasi siswa seperti ID, nama, dan riwayat kehadiran.

**3. String**

Digunakan untuk menyimpan nama siswa, tanggal, dan kategori kehadiran.

**4. File TXT**

Digunakan untuk menyimpan data siswa dan laporan hasil rekap kehadiran.

## Contoh Model Data

```python
data_siswa = [
    {
        "id": "S001",
        "nama": "Andi",
        "kehadiran": {
            "01-11-2026": "Hadir",
            "02-11-2026": "Izin"
        }
    },
    {
        "id": "S002",
        "nama": "Budi",
        "kehadiran": {
            "01-11-2026": "Hadir",
            "02-11-2026": "Hadir"
        }
    }
]
```

# 10. TEST CASE

Pengujian dilakukan untuk memastikan program dapat berjalan sesuai dengan kebutuhan yang telah dirancang.

| ID   | Kategori | Input/Kondisi                                  | Hasil yang Diharapkan                                  |
| ---- | -------- | ---------------------------------------------- | ------------------------------------------------------ |
| TC01 | Normal   | Menambahkan nama siswa Andi.                   | Data siswa berhasil disimpan.                          |
| TC02 | Normal   | Status kehadiran Hadir.                        | Status berhasil dicatat.                               |
| TC03 | Normal   | Status kehadiran Izin.                         | Status berhasil dicatat.                               |
| TC04 | Batas    | Daftar siswa masih kosong.                     | Program menampilkan pesan belum ada data siswa.        |
| TC05 | Invalid  | Memasukkan status kehadiran "Libur".           | Program menolak input dan menampilkan pesan kesalahan. |
| TC06 | Normal   | Terdapat 2 hadir, 1 izin, 1 sakit, dan 1 alpa. | Rekap menampilkan jumlah sesuai data.                  |
| TC07 | Normal   | 4 kali hadir dari 5 pertemuan.                 | Persentase kehadiran sebesar 80%.                      |
| TC08 | Invalid  | Memilih menu yang tidak tersedia.              | Program menampilkan pesan pilihan tidak valid.         |
| TC09 | Normal   | Menyimpan hasil rekap.                         | File laporan berhasil dibuat.                          |

# 11. PEMBAGIAN TUGAS

Pembagian tugas dilakukan agar setiap anggota kelompok memiliki tanggung jawab yang jelas dalam proses pengerjaan proyek.

| Peran          | Tanggung Jawab                                                        |
| -------------- | --------------------------------------------------------------------- |
| Ketua Kelompok | Mengatur kegiatan, mengawasi pekerjaan, dan mengintegrasikan program. |
| Programmer 1   | Membuat fitur penambahan dan penampilan data siswa.                   |
| Programmer 2   | Membuat fitur pencatatan dan validasi kehadiran.                      |
| Programmer 3   | Membuat fitur perhitungan rekap dan persentase kehadiran.             |
| Programmer 4   | Membuat fitur penyimpanan laporan dan pengujian program.              |
| Dokumentasi    | Menyusun README.md, proposal.md, dan mengelola repository GitHub.     |

Catatan: Pembagian tugas disesuaikan dengan jumlah anggota kelompok. Satu anggota dapat memegang lebih dari satu tanggung jawab.

# 12. JADWAL PELAKSANAAN

| Waktu                | Kegiatan                | Target                                                |
| -------------------- | ----------------------- | ----------------------------------------------------- |
| Pertemuan 14         | Perancangan proyek      | Proposal, pseudocode, struktur folder, dan test case. |
| Sebelum Pertemuan 15 | Implementasi awal       | Pembuatan fitur utama program.                        |
| Pertemuan 15         | Pengujian dan debugging | Program terintegrasi, diuji, dan diperbaiki.          |
| Pertemuan 16         | Presentasi proyek       | Demonstrasi program dan evaluasi hasil.               |

# 13. REPOSITORY GITHUB

Proyek ini akan dikelola menggunakan GitHub sebagai tempat penyimpanan kode program dan dokumentasi kelompok.

**Nama Repository:** `rekap-kehadiran-siswa`

Repository akan berisi:

1. README.md sebagai petunjuk penggunaan program.
2. proposal.md sebagai dokumen rancangan proyek.
3. Folder src untuk menyimpan kode Python.
4. Folder data untuk menyimpan data siswa.
5. Folder tests untuk menyimpan test case.
6. Folder output untuk menyimpan hasil laporan.

GitHub digunakan untuk mempermudah kolaborasi antaranggota kelompok serta mencatat setiap perkembangan proyek melalui commit secara bertahap.

## Contoh Perintah Git

```bash
git init
git add .
git commit -m "docs: menambahkan proposal proyek"
git branch -M main
git remote add origin URL_REPOSITORY
git push -u origin main
```

---

# PENUTUP

Program Rekap Kehadiran Siswa Berbasis Python merupakan proyek sederhana yang dirancang untuk membantu guru dalam mengelola data kehadiran siswa secara lebih efektif dan sistematis. Program ini menyediakan fitur pencatatan kehadiran, pengelompokan status kehadiran, perhitungan jumlah kehadiran, perhitungan persentase, serta penyimpanan laporan.

Melalui proyek ini, mahasiswa dapat menerapkan berbagai materi yang telah dipelajari dalam mata kuliah Algoritma dan Pemrograman, seperti penggunaan variabel, percabangan, perulangan, fungsi, list, dictionary, dan pengolahan file. Dengan demikian, proyek ini diharapkan dapat menjadi penerapan ilmu pemrograman dalam menyelesaikan permasalahan sederhana di bidang pendidikan.

Proposal ini akan menjadi pedoman dalam tahap implementasi, pengujian, debugging, dan dokumentasi pada pertemuan berikutnya.

# Labpy06

# Muhammad Rizal Hardiansyah (312410257)

# Soal Praktikum
Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:

    Fungsi tambah() untuk menambah data

    Fungsi tapilkan() untuk menampilkan data

    Fungsi hapus(nama) untuk menghapus data berdasarkan nama

    Fungsi ubah(nama) untuk mengubah data berdasarkan nama

    Buat flowchart dan penjelasan programnya
![Screenshot_20241202_044544_Chrome](https://github.com/user-attachments/assets/e85695b8-b9e9-40c2-8294-f5b75e051e58)
![Screenshot_20241202_044559_Chrome](https://github.com/user-attachments/assets/8f4b16f8-0bd7-4cfd-8cd7-957a727779f3)

# Menu Tambah Data
1. Fungsi ini menerima dua parameter: nama dan nilai.

2. Fungsi ini akan menambahkan dictionary yang berisi nama dan nilai mahasiswa ke dalam list mahasiswa.

3. Setelah menambahkan data, fungsi akan mencetak pesan konfirmasi.

# Menu Tampilkan Data
1. Fungsi ini menampilkan semua data mahasiswa yang tersimpan dalam list.

2. Jika list mahasiswa kosong, akan ditampilkan pesan bahwa tidak ada data.

3. Jika ada data, fungsi ini akan mencetak daftar mahasiswa beserta nilainya dengan nomor urut.

# Menu Hapus Data
1. Fungsi ini menghapus data mahasiswa berdasarkan nama yang diberikan.

2. Menggunakan list comprehension, fungsi ini membuat list baru _mhs yang berisi semua mahasiswa kecuali yang namanya sama dengan nama yang diberikan.

3. Jika ada perubahan dalam jumlah mahasiswa, maka data mahasiswa diupdate dan akan mencetak pesan konfirmasi. Jika tidak, akan mencetak pesan bahwa data tidak ditemukan.

# Menu Ubah Data
1.Fungsi ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama.

2.Fungsi ini mencari mahasiswa yang namanya sama dengan nama yang diberikan dan mengubah nilainya menjadi nilai_baru.

3.Jika data ditemukan, akan mencetak pesan konfirmasi. Jika tidak, akan mencetak pesan bahwa data tidak ditemukan.

# Flowchart

# Latihan 11
Ubahlah kode dibawah ini menjadi fungsi menggunakan lambada import math

def a(x): return x**2

def b(x, y): return math.sqrt(x2 + y2)

def c(*args): return sum(args)/len(args)

def d(s): return "".join(set(s))


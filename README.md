# Pratikum3

Richie Pranata 

Bahasa Pemograman

312410451

# Code program 
```Python
max_number = int(0)
    
while True:
    number = int(input("Masukkan bilangan (input 0 untuk berhenti): "))
        
    if number == 0:
        break
        
    if number > max_number:
        max_number = number
    
print("Bilangan terbesar: ", max_number)

```
# Hasil Eksekusi Program
![foto1](https://github.com/rich-pro12/foto1/blob/main/Screenshot%202024-10-22%20212012.png?raw=true)

# Penjelasan Kode
```Python
max_number = int(0)
```

Fungsi: Menginisialisasi variabel max_number dengan nilai 0. Variabel ini akan digunakan untuk menyimpan nilai bilangan terbesar yang ditemukan selama perulangan.

Tujuan: Menyiapkan tempat untuk menyimpan bilangan terbesar sementara.

```Python
while True:
```
Fungsi: Memulai perulangan tanpa batas (infinite loop), yang akan terus berjalan hingga kondisi break terpenuhi.

Tujuan: Melakukan input bilangan secara berulang sampai pengguna memasukkan angka 0 untuk berhenti.

```Python
number = int(input("Masukkan bilangan (input 0 untuk berhenti): "))
```
Fungsi: Mengambil input dari pengguna dalam bentuk string, kemudian mengubahnya menjadi tipe data integer (int()).

Tujuan: Meminta pengguna memasukkan bilangan dan mempersiapkannya untuk digunakan dalam perbandingan.

```Python
if number == 0:
    break
```
Fungsi: Memeriksa apakah bilangan yang diinputkan oleh pengguna adalah 0. Jika iya, perulangan dihentikan dengan break.

Tujuan: Menyediakan mekanisme untuk keluar dari perulangan ketika pengguna ingin berhenti memasukkan bilangan.

```Python
if number > max_number:
    max_number = number
```
Fungsi: Memeriksa apakah bilangan yang baru dimasukkan lebih besar dari bilangan terbesar yang disimpan di max_number. Jika iya, max_number diperbarui dengan bilangan tersebut.

Tujuan: Menyimpan bilangan terbesar yang telah ditemukan sejauh ini.

```Python
print("Bilangan terbesar: ", max_number)
```
Fungsi: Mencetak bilangan terbesar yang ditemukan setelah perulangan berakhir.

Tujuan: Memberi tahu pengguna hasil akhir yaitu bilangan terbesar yang telah mereka masukkan.

# Flowchart
![foto1]( )




# praktikum_3

Nama : muhammad hafizh alfauzi

Kelas : TI.24.A.5

NIM : 312410501

Mata Kuliah : Bahasa Pemograman

# flowchart

![foto](https://github.com/Moviezal/Praktikum/blob/e0dacea467ca19a47e4108582ed970ce2691b9b2/33449603-2379-40dc-ac8b-0228933cdb0e.jpg)

```python
 max_number = int(0):
```

Inisialisasi variabel max_number dengan nilai 0. Variabel ini akan digunakan untuk menyimpan bilangan terbesar yang ditemukan

```python
while True
```

Memulai sebuah loop tak terbatas (infinite loop). Loop ini akan terus berjalan hingga ada kondisi yang menghentikannya.

```python
number = int(input("Masukkan bilangan (input 0 untuk berhenti): ")):
```

Meminta pengguna untuk memasukkan sebuah bilangan. Bilangan yang dimasukkan akan disimpan dalam variabel number

```python
if number == 0::
```

Mengecek apakah bilangan yang dimasukkan adalah 0. Jika ya, maka break Keluar dari loop while. Ini berarti program akan berhenti ketika pengguna memasukkan 0.

```python
if number > max_number::
```

Mengecek apakah bilangan yang dimasukkan lebih besar dari nilai max_number saat ini. Jika ya, maka max_number = number Nilai max_number diperbarui menjadi nilai number yang baru. Ini artinya, bilangan yang baru saja dimasukkan menjadi bilangan terbesar sejauh ini.

#kode flowchart 

max_number = 0

while True:
  x = int(input("Masukkan angka (atau 0 untuk berhenti): "))

  if x == 0:
    break

  if x > max_number:
    max_number = x

print("Angka terbesar adalah:", max_number)


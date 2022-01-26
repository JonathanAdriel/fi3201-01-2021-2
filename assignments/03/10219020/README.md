# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10298345'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
![image](https://user-images.githubusercontent.com/66507928/151111018-31225dbc-53b8-4d16-8685-78df3194c0ab.png)


## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
![image](https://user-images.githubusercontent.com/66507928/151111573-e5c8bf0f-7897-4c6e-9075-8dd545ea0460.png)


## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
![image](https://user-images.githubusercontent.com/66507928/151111794-bcc7a52c-c448-41aa-b7fd-340801e96e4f.png)


## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ Membuat karakter kotak yang jumlahnya sama dengan angka-angka di NIM. Angka 0 tidak memunculkan kotak, angka 1 akan membuat 1 kotak, angka 2 akan membuat 2 kotak, dst. 
+ Terdapat dua jenis kotak yaitu kotak kosong (char1) yang berwarna putih dan kotak hitam (char2) yang berwarna hitam. 

### JONATHAN ADRIEL - 10219020 

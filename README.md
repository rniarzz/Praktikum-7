# Nama: Rini Ariza
# NIM: 312210337
# Kelas: TI.22.A3

## PERTEMUAN 12
## SOAL

![soal](https://user-images.githubusercontent.com/115542704/206460646-4c089e2d-9d9c-427b-a326-d43c633e78d6.png)

## Diagram class

![diagramClass](https://user-images.githubusercontent.com/115542704/206462308-ab57022f-da40-422a-9e52-1c59252d2123.png)

## Flowchart

![flowchart (3)](https://user-images.githubusercontent.com/115542704/206462353-41fd2d95-2329-4f92-9403-e679c5bc1784.png)

## Program

pertama saya membuat dictionary terlebih dahulu untuk menampung data
```python
mahasiswa = {}
```

kemudian membuat sebuah class daftar nilai
```python
class daftarNilai()
```

Lalu saya melanjutkan dengan membuat method method fungsinya sebagai berikut
```
def tambah(self)
def ubah(self)
def lihat(self)
def hapus(self)
def keluar(self)
```

lalu saya mengisi setiap method dengan elemen-elemen nya
```python
nama= input("masukan nama: ")
nim= input("masukan nim :")                                         
nilaiTugas= int(input("Masukkan Nilai Tugas: "))
nilaiUts= int(input("Masukkan Nilai UTS\t: "))            
nilaiUas= int(input("Masukkan Nilai UAS\t: "))             
nilaiAkhir= (30/100 * nilaiTugas) + (35/100 * nilaiUts) + (35/100 * nilaiUas)
mahasiswa[nama]=nim,nilaiTugas,nilaiUts,nilaiUas,nilaiAkhir
```

lalu saya membuat sebuah looping
```python
while True:
    data = daftarNilai()
    print('\ntambah\t(1)\nubah\t(2)\nlihat\t(3)\nhapus\t(4)\nkeluar\t(5)')
    c = input("\nsilahkan masukan pilihan : ")
    print()
```

Dan terakhir membuat fungsi if else untuk menjalankan method
```python
if (c == "1"):
    data.tambah()
elif (c == "2"):
    data.ubah()
elif (c == "3"):
    data.lihat()
elif (c == "4"):
    data.hapus()
elif (c == "5"):
    data.keluar()
    break    
```

# output program

ini adalah output apabila memilih tambah(1)

<img width="201" alt="ri 1" src="https://user-images.githubusercontent.com/115542704/206483140-39549453-0508-4cce-bbb3-d7f73d897270.png">

ini adalah output apabila memilih ubah(2)

<img width="204" alt="ri 2" src="https://user-images.githubusercontent.com/115542704/206483199-e31314e6-d2ba-4110-9666-f82ce5f923c3.png">

ini adalah output apabila memilih untuk tambah lagi

<img width="203" alt="ri 3" src="https://user-images.githubusercontent.com/115542704/206483359-405e5d49-55bc-4332-a71b-0d0d3dc5cd1a.png">

ini adalah output apabila memilih hapus(3)

<img width="197" alt="ri 4" src="https://user-images.githubusercontent.com/115542704/206483433-e252c767-a030-45ed-9ce5-18db0ecc43d7.png">

ini adalah output apabila memilih lihat (4)

<img width="506" alt="ri 5" src="https://user-images.githubusercontent.com/115542704/206483485-44b5bb66-ffc6-4748-9f13-540e6a868a07.png">

ni adalah output apabila memilih else

<img width="221" alt="ri 6" src="https://user-images.githubusercontent.com/115542704/206483557-8eb6066b-c456-4244-b1e3-b9154bfb2302.png">

# SEKIAN TERIMAKASIH


# Nama: Rini Ariza
# NIM: 312210337
# Kelas: TI.22.A3

## PERTEMUAN 12
## SOAL

![soal](https://user-images.githubusercontent.com/115542704/206460646-4c089e2d-9d9c-427b-a326-d43c633e78d6.png)

## diagram class

![diagramClass](https://user-images.githubusercontent.com/115542704/206462308-ab57022f-da40-422a-9e52-1c59252d2123.png)

## flowchart

![flowchart (3)](https://user-images.githubusercontent.com/115542704/206462353-41fd2d95-2329-4f92-9403-e679c5bc1784.png)

## program

pertama saya membuat sebuah class daftar nilai

        class daftarNilai()

Lalu saya melanjutkan dengan membuat method method fungsinya

            def tambah(self)
        def ubah(self)
        def lihat(self)
        def hapus(self)

lalu saya mengisi setiap method dengan elemen elemen nya

            nama= input("masukan nama: ")
        nim= input("masukan nim :")                                         
        nilaiTugas= int(input("Masukkan Nilai Tugas: "))
        nilaiUts= int(input("Masukkan Nilai UTS\t: "))            
        nilaiUas= int(input("Masukkan Nilai UAS\t: "))             
        nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)
        dt[nama]=nim,nilaiTugas,nilaiUts,nilaiUas,nilaiAkhir

lalu saya membuat sebuah looping

        while True:
        input('tambah   (1)
            ubah     (2)
            lihat    (3)
            hapus    (4)
            ')
            c = input("\nsilahkan masukan pilihan : ")

  dan terakhir membuat fungsi if else untuk menjalankan method

            if (c=="1"):
            data.tambah()
        elif (c=="2"):
            data.ubah()
        elif (c=="3"):
            data.lihat()
        elif (c=="4"):
            data.hapus()
        else:
            data.keluar()
            break         

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


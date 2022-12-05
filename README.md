# PRAKTIKUM 8

PROGRAM OBJECT ORIENTED

Yang pertama kita Harus Membuat List
Contoh:
ist_nim = []
list_nama = []
list_study = []
list_uts = []
list_uas = []
list_ipk = []


![Screenshot (98)](https://user-images.githubusercontent.com/115479895/205728685-5238c7d1-5b25-47bd-97a6-179fa432df8a.png)




Setelah  Membuat List Lalu Bikin program Menampilkan data List Yang Telah diBuat


def tampilData (self):
        n = 0
        print("\nJumlah Mahasiswa Yang Sudah TerInput : ")
        for i in range(x):
            n+=1
            if list_ipk[i] >= 3.60 :
                print("\n--------------------Mahasiswa ke-",n,"----------------------------")
                print("Nim Mahasiswa : ",list_nim[i])
                print("Nama Mahasiswa : ",list_nama[i])
                print("Progam Study Mahasiswa : ",list_study[i])
                print("Masukkan Nilai UTS : ",list_uts[i])
                print("Masukkan Nilai UAS : ",list_uas[i])
                print("ipk Mahasiswa : ",list_ipk[i])
                print("--------------------------------------------------------------------")



![Screenshot (96)](https://user-images.githubusercontent.com/115479895/205730098-1f568c4a-5c56-4d58-8c22-b8bf22745a0e.png)

Setelah Sudah  Bikin List Tampilkan Data Lalu
 diinput kembali  Tampilan List Yang Telah  Buat Diatas,
Atau Juga  Bisa buat perubahan data Ketika Ada Perubahan didalam Data Tersebut.

else:
                i+=1
        print("Catatan : Apabila Mahasiswa Yang Tidak Tampil Dikarenakan ipk")

    stop = False
    x = 0
    while (not stop):
        print("TAMBAHKAN DATA ANDA")
        print("=======================================\n")
        inputNim = int(input("Masukkan Nim : "))
        inputNama = input("Masukkan Nama : ")
        inputStudy = input("Masukkan Program Study : ")
        inputUts = int(input("Masukkan Nilai UTS : "))
        inputUas = int(input("Masukkan Nilai UAS : "))
        inputipk = float(input("Masukkan IPK : "))
        print("TERIMAKASIH SUDAH MENAMPILKAN DATA ANDA!")
        print("============================================\n")
        x+=1
        x+=1
        ulang = input("Apakah ingin Mengubah Data (y/t) ? : ")
        if ulang == 't':
            stop = True

Tampilan Data Yang sudah jadi Ketika Tidak Mengalami Perubahan Data

![Screenshot (101)](https://user-images.githubusercontent.com/115479895/205732546-b87503cb-b92d-420e-be23-449ec16490c2.png)


Tampilan Yang sudah jadi ketika Mengalami Perubahan Data.
![Screenshot (94)](https://user-images.githubusercontent.com/115479895/205731556-91ec2e82-2d7f-4ec8-a527-0b7b618319c1.png)





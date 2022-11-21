# Praktikum3

# Lab2 Struktur Kondisi

# LATIHAN 1
MEMBUAT PROGRAM SEDERHANA DENGAN MENGINPUT 2 BUAH BILANGAN UNTUK MENENTUKAN BILANGAN TERBESAR MENGGUNAKAN STATEMENT IF

 Source code & Output (Hasil Running Program)
    Berikut adalah source code latihan 1 :

a = int(input("bilangan a : "))
b = int(input("bilangan b : "))

if a > b:
    print(f"terbesar adalah {a}")
elif b > a :
    print(f"terbesar adalah {b}")

    Berikut adalah tampilan source code dan output :
![image1.png](sikirinsot/lat1.png)

# LATIHAN 2
MEMBUAT PROGRAM UNTUK MENGURUTKAN DATA BERDASARKAN INPUT SEJUMLAH DATA (MINIMAL 3 VARIABLE INPUT ATAU LEBIH), KEMUDIAN MENAMPILKAN HASIL DENGAN URUT DARI DATA TERKECIL

 Source code & Output (Hasil Running Program)
    Berikut adalah source code latihan 2 :

    a, b, c = (
    int(input("Masukan nilai Ke-1: ")),
    int(input("Masukan nilai Ke-2: ")),
    int(input("Masukan nilai Ke-3: "))
)
if a<b and a<c:
    if b<c:
        print("Urutan Bilangan : ",a,b,c)
    else:
        print("Urutan Bilangan : ",a,c,b)
elif b<a and b<c:
    if a<c:
        print("Urutan Bilangan : ",b,a,c)
    else:
        print("Urutan Bilangan : ",b,c,a)
else:
    if a<b:
        print("Urutan Bilangan : ",c,a,b)
    else:
        print("Urutan Bilangan : ",c,b,a)

    Berikut adalah tampilan source code dan output :
![image2.png](sikirinsot/lat2.png)
![image3.png](sikirinsot/lat2a.png)

# Lab3 Perulangan

# LATIHAN 1
MEMBUAT PROGRAM DENGAN PERULANGAN BERTINGKAT (NESTED)

 Source code & Output (Hasil Running Program)

 start = 0;
stop = 10;
for i in range(10):
    for j in range(start,stop):
        print(j, sep=" ", end=" ")
        if j < 10 :
            print('{0:>2}'.format(""), end="")
        else :
            print('{0:>1}'.format(""), end="")
    start+=1
    stop+=1
    print("")

    Berikut adalah tampilan source code dan output :
![image4.png](sikirinsot/lat3.png)

# LATIHAN 2
MENAMPILKAN n BILANGAN ACAK YANG LEBIH KECIL DARI 0.5 DAN NILAI n DIISI PADA SAAT RUNTIME MENGGUNAKAN KOMBINASI WHILE DAN FOR

 Source code & Output (Hasil Running Program)

 import random


jumlah = int(input("Masukan Jumlah Nilai :"))
for i in range(jumlah):
    i=random.uniform(0.0,0.5)
    print("Data Ke:", i)
    print("SELESAI")

    Berikut adalah tampilan source code dan output :
![image5.png](sikirinsot/lat4.png)




# SEKIAN AND MATUR NUWUN
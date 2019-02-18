# labpy03.py
#Perulangan RANDOM di bawah 0,5
``` python
a = 100000000

for x in range(1,9):

    if(x>=1 and x<=2):
    
        b = a*0
        
        print("Laba Bulan ke-",x," :",b)
        
    if(x>=3 and x<=4):
    
        c=a*0.1
        
        print("Laba Bulan ke-",x," :",c)
        
    if(x>=5 and x<=7):
    
        d=a*0.5
        
        print("Laba Bulan ke-",x," :",d)
        
    if(x==8):
    
        e=a*0.2
        
        print("Laba Bulan ke-",x," :",e)
        
total = b+b+c+c+d+d+d+e

print("\ntotal : ", total)
```

Pernyataan break dan continue digunakan untuk mengubah aliran kontrol.Pernyataan break, ketika dijalankan dalam perulangan while, for, do...while, dan pernyataan switch, menyebabkan keluar dari pernyataan itu lalu eksekusi program berlanjut dengan pernyataan berikutnya.

![ss5](https://user-images.githubusercontent.com/46735662/52929189-efddee00-3375-11e9-9096-ff11757ea5b1.png)

#PERULANGAN TAK TERBATAS JIKA DI MASUKAN DATA 0 AKAN BERAKHIR 
```python
max=0

while True:

    a=int(input("Masukan bilangan:"))
    
    if a ==0:
    
        break
        
    if a>max:
    
        max=a
        
print("bilangan terbesar:",max)
```

Pengulangan digunakan untuk menjalankan satu atau beberapa pernyataan sebanyak beberapa kali. dengan kata lain, pengulangan memungkinkan kita untuk menjalankan beberapa pernyataan hanya dengan menuliskan pernyataan tersebut satu kali saja.


![ss4](https://user-images.githubusercontent.com/46735662/52928746-e18ed280-3373-11e9-9e60-f785430d03b1.png)

#PENGULANGAN ACAK

import random

n = input("masukan nilai N:")

for x in range (1,6):

  print("data ke:",x,"=>",random.uniform(0.0,0.5))
  
print("Selesai")

*penjelasan algoritma

-[x]masukan nilai N=5
-[x]gunakan for range, untuk mengulang data
-[x]cetak data dan memasukan random.uniform kurang dari 0,5
-[x]jika selesai maka RUN


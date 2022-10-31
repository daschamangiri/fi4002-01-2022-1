# 10219010
Dascha Gularni Purnawulan


## materi sebelumnya
+ Euler
+ Runge - Kutta
+ Predator Prey
+ Monte Carlo
+ Sistem Bandul dan Pegas
+ Discrete Fourier Transform (DFT) to Fast Fourier Transform (FFT)
+ Lorentz


## materi paling menarik
+ Materi yang paling menarik adalah metode Runge-Kutta orde 4 karena saya baru pertama kali belajar materi tersebut. Selain itu, berdasarkan ekspansi fungsi dari Deret Taylor, Metode Runge-Kutta orde 4 memiliki galat pemotongan yang minimum sehingga menghasilkan solusi yang baik.


## materi paling membosankan
+ Sistem bandul dan pegas karena memiliki banyak kemungkinan yang terjadi sehingga banyak yang harus dipelajari


## materi yang sudah dipahami
+ Monte Carlo karena memiliki pemahaman codingan yang sederhana.


## materi yang belum dipahami
+ Sistem bandul dan pegas karena saya belum terlalu mengerti pemahaman codingannya.


## contoh program

```python
# contoh program python
import matplotlib.pyplot as plt
import random 

inside = 0 
n = 1000

x_inside=[]
y_inside=[]
x_outside=[]
y_outside=[]

for _ in range(n):
    x=random.uniform(0.0,2.0)
    y=random.uniform(0.0,4.0)
    if y<=x**2:
        inside+=1
        x_inside.append(x)
        y_inside.append(y)
    else:
        x_outside.append(x)
        y_outside.append(y)

Luas=8*inside/n
print(Luas)
        
fig, ax=plt.subplots()
ax.set_aspect('equal')
ax.scatter(x_inside, y_inside, color='g', marker='s')
ax.scatter(x_outside, y_outside, color='r', marker='s')

plt.draw()
```

Hasilnya adalah

![image](https://user-images.githubusercontent.com/112105008/198960182-2378a456-4316-4d67-84c0-d2100279adc0.png)

```
```


## cara perkuliahan
+ Menurut saya perkuliahan selama ini sudah cukup baik dan mudah dimengerti karena diberi pr setiap minggu sehingga kami mampu mengulik dan memahaminya lebih dalam lagi.


## topik sistem fisis
+ Menurut saya sistem fisis yang menarik adalah osilasi, meskipun saya belum terlalu paham codingannya. Sistem fisis tersebut menarik karena menggunakan persamaan Runge-kutta


## simulasi dan visualisasi
+ Topik yang ingin saya simulasikan adalah Monte Carlo karena pemahaman codingannya cukup mudah. Pustaka atau library python yang digunakan adalah matplotlib.pyplot. Pustaka tersebut bertujuan menampilkan plot grafik dan menggunakan random untuk menampilkan angka yang acak pada input yang digunakan.

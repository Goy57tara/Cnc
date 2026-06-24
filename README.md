# CNC Milling dan CNC Turning

## Mata Kuliah CAD/CAM

---

# 1. Pendahuluan

Computer Numerical Control (CNC) merupakan teknologi manufaktur yang menggunakan komputer untuk mengendalikan pergerakan mesin secara otomatis berdasarkan program yang telah dibuat sebelumnya. Teknologi CNC banyak digunakan dalam industri manufaktur karena mampu menghasilkan produk dengan tingkat presisi yang tinggi, kualitas yang konsisten, dan waktu produksi yang lebih efisien dibandingkan mesin konvensional.

Dua proses pemesinan CNC yang paling umum digunakan adalah **CNC Milling** dan **CNC Turning**.

---

# 2. CNC Milling

## 2.1 Pengertian CNC Milling

CNC Milling adalah proses pemesinan dimana alat potong (cutting tool) berputar untuk menghilangkan material dari benda kerja sehingga menghasilkan bentuk yang diinginkan.

Pada proses milling:

* Tool berputar
* Benda kerja dijepit pada meja mesin
* Pergerakan terjadi pada sumbu X, Y, dan Z

---

## 2.2 Prinsip Kerja CNC Milling

1. Membuat desain menggunakan software CAD.
2. Membuat toolpath menggunakan software CAM.
3. Menghasilkan program G-Code.
4. Program dijalankan pada mesin CNC.
5. Tool memotong material sesuai lintasan yang telah ditentukan.

---

## 2.3 Sumbu Gerak CNC Milling

### 3 Axis

* X : Kanan ↔ Kiri
* Y : Depan ↔ Belakang
* Z : Atas ↔ Bawah

```text
        Z+
        ↑
        │
Y- ←────┼────→ Y+
        │
        ↓
        Z-

      X+/X-
```

### 4 Axis

Memiliki tambahan sumbu rotasi A.

### 5 Axis

Memiliki tambahan sumbu rotasi A dan B/C sehingga mampu membuat geometri yang lebih kompleks.

---

## 2.4 Operasi Dasar CNC Milling

### Face Milling

Digunakan untuk meratakan permukaan benda kerja.

### End Milling

Digunakan untuk membuat profil dan kontur.

### Slot Milling

Digunakan untuk membuat alur (slot).

### Pocket Milling

Digunakan untuk membuat rongga (pocket).

### Drilling

Digunakan untuk membuat lubang.

### Chamfering

Digunakan untuk membuat sudut miring.

---

## 2.5 Tool pada CNC Milling

### End Mill

Tool yang paling umum digunakan.

Jenis:

* Flat End Mill
* Ball Nose End Mill
* Corner Radius End Mill

### Face Mill

Digunakan untuk proses perataan permukaan.

### Drill Bit

Digunakan untuk proses pengeboran.

---

## 2.6 Contoh Produk CNC Milling

* Bracket
* Housing
* Mold
* Dudukan sensor
* Komponen otomasi
* Cover mesin

---

# 3. CNC Turning

## 3.1 Pengertian CNC Turning

CNC Turning adalah proses pemesinan dimana benda kerja berputar sedangkan pahat bergerak memotong material hingga diperoleh bentuk yang diinginkan.

Proses ini dilakukan menggunakan mesin CNC Lathe atau CNC Bubut.

---

## 3.2 Prinsip Kerja CNC Turning

1. Material dijepit pada chuck.
2. Chuck memutar benda kerja.
3. Tool bergerak pada sumbu X dan Z.
4. Material dipotong sesuai program.

---

## 3.3 Sumbu Gerak CNC Turning

### Sumbu X

Mengatur diameter benda kerja.

### Sumbu Z

Mengatur panjang benda kerja.

```text
      Z+
      →

====================
      Benda Kerja
====================

      ↑ X+
      ↓ X-
```

---

## 3.4 Operasi Dasar CNC Turning

### Facing

Meratakan ujung benda kerja.

### Straight Turning

Mengurangi diameter benda kerja.

### Taper Turning

Membuat bentuk tirus.

### Grooving

Membuat alur.

### Threading

Membuat ulir.

### Parting

Memotong benda kerja.

### Drilling

Membuat lubang pada pusat benda kerja.

---

## 3.5 Tool pada CNC Turning

### Turning Tool

Digunakan untuk pembubutan umum.

### Grooving Tool

Digunakan untuk membuat alur.

### Threading Tool

Digunakan untuk membuat ulir.

### Parting Tool

Digunakan untuk memotong benda kerja.

### Boring Tool

Digunakan untuk memperbesar diameter lubang bagian dalam.

---

## 3.6 Contoh Produk CNC Turning

* Poros (shaft)
* Bushing
* Pulley
* Baut
* Mur
* As motor

---

# 4. Parameter Pemesinan

## 4.1 Spindle Speed (N)

Kecepatan putaran spindle.

Rumus:

```text
N = (1000 × Vc) / (π × D)
```

Keterangan:

* N = Putaran spindle (rpm)
* Vc = Cutting speed (m/min)
* D = Diameter tool atau benda kerja (mm)

---

## 4.2 Feed Rate (F)

Kecepatan gerak pahat saat proses pemotongan.

Satuan:

```text
mm/min
```

---

## 4.3 Depth of Cut (DOC)

Kedalaman pemotongan material dalam satu lintasan.

Semakin besar DOC maka:

* Material yang terpotong lebih banyak
* Beban mesin meningkat
* Waktu pengerjaan lebih cepat

---

# 5. Perbandingan CNC Milling dan CNC Turning

| Aspek         | CNC Milling            | CNC Turning    |
| ------------- | ---------------------- | -------------- |
| Yang Berputar | Tool                   | Benda Kerja    |
| Sumbu Utama   | X, Y, Z                | X, Z           |
| Bentuk Produk | Kompleks dan prismatik | Silinder       |
| Mesin         | Milling Machine        | Lathe Machine  |
| Tool          | End Mill, Face Mill    | Turning Tool   |
| Produk        | Bracket, Housing       | Shaft, Bushing |

---

# 6. Integrasi CAD/CAM pada CNC

Alur kerja CNC modern:

```text
CAD
 ↓
CAM
 ↓
Toolpath
 ↓
Post Processor
 ↓
G-Code
 ↓
Mesin CNC
```

### Software CAD

* SolidWorks
* Autodesk Inventor
* AutoCAD

### Software CAM

* SolidCAM
* MasterCAM
* Fusion 360 CAM

---

# 7. Keunggulan CNC

* Presisi tinggi
* Produksi cepat
* Kualitas konsisten
* Mampu membuat bentuk kompleks
* Mengurangi human error

---

# 8. Kesimpulan

CNC Milling dan CNC Turning merupakan dua proses pemesinan yang paling banyak digunakan dalam industri manufaktur modern. CNC Milling digunakan untuk membuat komponen dengan bentuk kompleks menggunakan tool yang berputar, sedangkan CNC Turning digunakan untuk membuat komponen berbentuk silinder dengan cara memutar benda kerja.

Kedua teknologi ini menjadi bagian penting dalam sistem CAD/CAM karena mampu menghasilkan produk yang presisi, efisien, dan sesuai dengan kebutuhan industri saat ini.

# 📘 Analisis Data Nilai Siswa

Repositori ini berisi program Python untuk melakukan analisis data nilai siswa dari berbagai mata pelajaran. Analisis meliputi perhitungan statistik dasar serta visualisasi grafik menggunakan **pandas**, **matplotlib**, dan **seaborn**.


## 📁 Dataset

File data yang digunakan bernama `nilai_siswa.csv` dan menggunakan pemisah `;`.

**Struktur kolom:**

| Kolom      | Deskripsi      |
| ---------- | -------------- |
| **Nama**   | Nama siswa     |
| **Matpel** | Mata pelajaran |
| **Nilai**  | Nilai siswa    |

**Contoh isi file:**

```
Nama;Matpel;Nilai
Ade;Bahasa Indonesia;87
Aira;Bahasa Indonesia;88
Badi;Bahasa Inggris;78
Cyla;Bahasa Inggris;90
Khansa;Matematika;98
```


## 🛠️ Instalasi dan Persiapan

Pastikan library berikut sudah terinstall:

```bash
pip install pandas matplotlib seaborn
```

Jalankan program dengan:

```bash
python analisis.py
```


## 📜 Fitur Program

### ✔ 1. Membaca Dataset

Program membaca file CSV dengan pemisah `;` agar data terformat dengan benar.

```python
data = pd.read_csv('nilai_siswa.csv', sep=';')
```

---

### ✔ 2. Menampilkan Data Awal

Menunjukkan beberapa baris awal untuk memastikan data terbaca dengan baik.

---

### ✔ 3. Statistik Deskriptif

Program menghitung:

* Rata-rata nilai
* Median
* Modus
* Statistik umum dengan `describe()`
* Nilai maksimum per mata pelajaran
* Nilai minimum per mata pelajaran

---

### ✔ 4. Visualisasi

Program menghasilkan beberapa grafik untuk memahami pola nilai siswa.

#### 📊 **a. Rata-rata Nilai per Mata Pelajaran (Bar Chart)**

Menunjukkan perbandingan rata-rata antar mata pelajaran.

#### 📦 **b. Boxplot Sebaran Nilai**

Digunakan untuk melihat:

* Median
* Rentang nilai
* Outlier
* Variasi nilai tiap mata pelajaran

#### 📈 **c. Histogram + KDE**

Menampilkan distribusi nilai siswa secara visual.

#### 📉 **d. Countplot Frekuensi Nilai**

Menunjukkan berapa banyak siswa memperoleh nilai tertentu.

---

## 🧠 Tujuan Proyek

Proyek ini dibuat untuk:

* Mempelajari teknik dasar analisis data
* Memahami statistik deskriptif
* Melatih pembuatan grafik data
* Menyediakan contoh sederhana pengolahan dataset menggunakan Python

---

## 🧩 Struktur Proyek

```
📂 projek-nilai-siswa/
│── analisis.py
│── nilai_siswa.csv
│── README.md
```

---

## ✨ Hasil Akhir

Program akan menampilkan:

* Statistik nilai siswa
* Grafik bar
* Boxplot
* Histogram
* Countplot

Semua grafik ditampilkan menggunakan jendela matplotlib.
<img width="997" height="619" alt="image" src="https://github.com/user-attachments/assets/f9fd34e2-fd7d-4496-9d39-1a56801f6601" />
<img width="1486" height="751" alt="image" src="https://github.com/user-attachments/assets/ea9eaf3d-1b1e-4518-b6cf-4ce7dc590582" />


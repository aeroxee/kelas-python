---
title: Tipe Data dan Operator
description: Belajar tipe data dan operator pada bahasa pemrograman Python
author: Fajri Fath
---

## Operator

Operator adalah sebuah penugasan untuk memberikan nilai terhadap variabel. 

```py
nama = "Python"
```

---

## Tipe Data

Tipe data pada bahasa pemrograman python

- [Tipe data String](#tipe-data-string)
- [Tipe data Integer]()
- [Tipe data Float]()
- [Tipe data Boolean]()

### Tipe data string

Tipe data string adalah tipe data yang berbentuk character atau kalimat. Tipe data ini memiliki objek-objek yang dapat kita gunakan untuk mengatur character yang dibuat.

Contoh pembuatan tipe data string

```py
nama = "Python"
alamat = "Padang"
```

#### Built-in Method type()

Untuk mengetahui atau menprint tipe data pada python kita dapat menggunakan perintah `type`, sebagai contoh:

```py
nama = "Python"
tipe = type(nama)

print(tipe)
# Output: string
```

#### Method-method yang ada di tipe data string

Method adalah sebuah objek yang berbentuk fungsi untuk memudahkan programmer melakukan sesuatu terhadap pekerjaan. Berikut beberapa contoh method yang sering digunakan pada tipe data string.

1. `upper` adalah method yang berfungsi merubah kalimat menjadi huruf besar semua.
```py title="Contoh method upper"
nama = "python programming"
nama_upper = nama.upper()
print(nama_upper)
```
```title="Output"
PYTHON PROGRAMMING
```

2. `capitalize` adalah method yang berfungsi untuk merubah setial huruf pada suatu kata menjadi huruf besar.
```py title="Contoh method capitalize"
nama = "python programming"
nama_cap = nama.capitalize()
print(nama_cap)
```
```title="Output"
Python Programming
```

3. `count` adalah method untuk menghitung berapa huruf yang ada pada variabel string.
```py title="Contoh method count"
alamat = "Padang"
s = "a"
c = alamat.count(a)
print(c)
```
```title="Output"
2
```

4. `split` adalah method untuk membagi tipe data string menjadi `list` berdasarkan seperator yang diberikan.
```py title="Contoh method split"
nama = "python,programming,is,the,best"
s = nama.split(",")
print(s)
print(type(s))
```
```title="Output"
['python', 'programming', 'is', 'the', 'best']
List
```

5. `startswith` adalah method untuk mencek apakah variabel string itu diawali dengan huruf yang diberikan. Method ini akan mengembalikan tipe data boolean.
```py title="Contoh method startswith"
nama = "Python Programming"
s = nama.startswith("Python")
print(s)
```
```title="Output"
True
```

6. Dan masih banyak lainnya.

### Tipe data Integer

Tipe data ini adalah tipe data yang berbentuk bilangan bulat.

```py title="Contoh integer"
umur = 30
print(umur)
print(type(umur))
```
```title="Output"
"""
30
int
```

### Tipe data float

Tipe data ini adalah tipe data yang berbentuk bilangan desimal.

```py title="Contoh float"
tinggi = 172.5
print(tinggi)
print(type(tinggi))
```
```title="Output"
172.5
float
```

### Tipe data Boolean

Tipe data ini adalah tipe data yang berbentuk boolean(benar atau salah)/(0 atau 1). Tipe data ini banyak digunakan di percabangan if-else.

```py title="Contoh tipe data boolean"
umur = 20
apakah_dewasa = umur > 18
print(apakah_dewasa)
```
```title="Output"
True
```
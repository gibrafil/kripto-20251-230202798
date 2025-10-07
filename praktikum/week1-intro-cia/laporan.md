# Laporan Praktikum Kriptografi
Minggu ke-: 1
Topik: week1-intro-cia  
Nama: Ahmad Galif Ganendra  
NIM: 230202798 
Kelas: 5IKRA  

---

## 1. Tujuan
(Tujuan dari percobaan ini adalah untuk memahami konsep dasar hash dan  
implementasi algoritma SHA-256).  
Melalui praktikum ini, mahasiswa diharapkan dapat:  
- Mengetahui cara kerja fungsi hash satu arah dan perbedaannya dengan enkripsi  
- Mengimplementasikan algoritma SHA-256 menggunakan bahasa pemrograman Python  
- Menganalisis hasil hash dari berbagai input untuk melihat efek avalanche  
- Menyadari pentingnya fungsi hash dalam menjaga integritas dan keamanan data  


---

## 2. Dasar Teori
(Hashing dengan SHA-256)  
Hash function merupakan salah satu konsep dasar dalam kriptografi yang mengubah  
variabel menjadi keluaran dengan panjang tetap. Proses ini bersifat satu arah dan  
tidak dapat dikembalikan ke bentuk aslinya. Salah satu algoritma hash yang umum  
digunakan adalah SHA-256 (Secure Hash Algorithm 256-bit), yang dikembangkan oleh  
National Security Agency (NSA). Hash banyak digunakan untuk keamanan data  
digital seperti penyimpanan password, tanda tangan digital, dan validasi file.  

SHA-256 menghasilkan keluaran berupa string heksadesimal sepanjang 64 karakter.  
Input akan menghasilkan output hash yang sepenuhnya berbeda — fenomena ini disebut  
SHA-256 dianggap sangat kuat untuk mendeteksi perubahan data dan menjaga integritas.  

---

## 3. Alat dan Bahan  
- Git dan akun GitHub  


---

## 4. Langkah Percobaan
(Tuliskan langkah yang dilakukan sesuai instruksi.  
Contoh format:
1. Membuat file `caesar_cipher.py` di folder `praktikum/week2-cryptosystem/src/`.
2. Menyalin kode program dari panduan praktikum.
3. Menjalankan program dengan perintah `python caesar_cipher.py`.)

---

## 5. Source Code
(Salin kode program utama yang dibuat atau dimodifikasi.  
Gunakan blok kode:

```python
# contoh potongan kode
def encrypt(text, key):
    return ...
```
)

---

## 6. Hasil dan Pembahasan
(- Lampirkan screenshot hasil eksekusi program (taruh di folder `screenshots/`).  
- Berikan tabel atau ringkasan hasil uji jika diperlukan.  
- Jelaskan apakah hasil sesuai ekspektasi.  
- Bahas error (jika ada) dan solusinya. 

Hasil eksekusi program Caesar Cipher:

![Hasil Eksekusi](screenshots/output.png)
![Hasil Input](screenshots/input.png)
![Hasil Output](screenshots/output.png)
)

---

## 7. Jawaban Pertanyaan
(Jawab pertanyaan diskusi yang diberikan pada modul.  
- Pertanyaan 1: …  
- Pertanyaan 2: …  
)
---

## 8. Kesimpulan
(Tuliskan kesimpulan singkat (2–3 kalimat) berdasarkan percobaan.  )

---

## 9. Daftar Pustaka
(Cantumkan referensi yang digunakan.  
Contoh:  
- Katz, J., & Lindell, Y. *Introduction to Modern Cryptography*.  
- Stallings, W. *Cryptography and Network Security*.  )

---

## 10. Commit Log
(Tuliskan bukti commit Git yang relevan.  
Contoh:
```
commit abc12345
Author: Nama Mahasiswa <email>
Date:   2025-09-20

    week2-cryptosystem: implementasi Caesar Cipher dan laporan )
```

# Praktikum 3 :
Menentukan Bilangan Terbesar dari 3 Bilangan (Python)
Penjelasan Tugas
Tugas ini bertujuan untuk membuat program Python yang dapat menerima tiga buah input bilangan bulat dan menentukan serta mencetak bilangan mana yang memiliki nilai terbesar.
________________________________________
# Flowchart Program
 ![flowchart](https://github.com/user-attachments/assets/d128bfa7-57c3-437e-9465-02df8c546e6e)

Penjelasan Flowchart : 
Di awali dengan START, lalu dilanjutkan dengan proses INPUT untuk 3 bilangan, yaitu bilangan 1, bilangan 2 dan bilangan 3. Kemudian, program dengan menggunakan serangkaian Keputusan untuk membandingkan nilai-nilai tersebut.
1.	Membandingkan bilangan 1 dengan bilangan 2 dan bilangan 3. Jika bilangan 1 lebih besar dari keduanya, maka bilangan 1 yang terbesar.
2.	Jika tidak, program membandingkan bilangan 2 dengan bilangan 1 dan bilangan 3. Jika bilangan 2 lebih besar dari keduanya, maka bilangan 2 yang terbesar.
3.	Jika proses diatas tidak terpenuhi, otomatis bilangan 3 adalah bilangan terbesar. Hasil perbandingan akan dicetak melalui proses OUTPUT, dan alur program diakhiri dengan END.

Kode Program (terbesar.py)

A = int(input("bilangan 1: "))
B = int(input("bilangan 2: "))
C = int(input("bilangan 3: "))

if A >= B and A >= C:
    print("1 bilangan terbesar")
    
elif B >= A and B >= C:
    print("2 bilangan terbesar")
    
else:

    print("3 bilangan terbesar")
    
   ![screenshoot](https://github.com/user-attachments/assets/86e5b39b-4059-4382-983b-69c4981961c1)


 
# Penjelasan Kode Program:
1.	Input: Program menggunakan input() dan diubah ke tipe int() untuk menerima tiga bilangan bulat. Blok try-except digunakan untuk menangani kesalahan jika input yang dimasukkan bukan angka.
   
2.	Percabangan if-elif-else:
if A >= B and A >= C:: Mengecek apakah A lebih besar atau sama dengan kedua bilangan lainnya.
elif B >= A and B >= C:: Jika kondisi pertama salah, cek apakah B lebih besar atau sama dengan A dan C.
else:: Jika kedua kondisi di atas salah, maka otomatis C adalah yang terbesar.

3.	Output: Bilangan terbesar dicetak menggunakan fungsi print().
_____________________________
# Hasil OUTPUT
 <img width="975" height="132" alt="image" src="https://github.com/user-attachments/assets/b083db63-886c-4044-a611-982065743f7d" />


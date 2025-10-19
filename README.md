Praktikum3: Menentukan Bilangan Terbesar dari 3 Bilangan (Python)
Penjelasan Tugas

Penjelasan Tugas
Tugas ini bertujuan untuk membuat program Python yang dapat menerima tiga buah input bilangan bulat dan menentukan serta mencetak bilangan mana yang memiliki nilai terbesar.

Flowchart Program

Penjelasan Flowchart: Flowchart diawali dengan START, dilanjutkan dengan proses INPUT untuk tiga bilangan (bil1, bil2, bil3). Kemudian, program menggunakan serangkaian keputusan untuk membandingkan nilai-nilai tersebut.

Pertama, membandingkan bil1 dengan bil2 dan bil3. Jika bil1 lebih besar dari keduanya, maka bil1 adalah yang terbesar.
Jika tidak, program membandingkan bil2 dengan bil1 dan bil3. Jika bil2 lebih besar dari keduanya, maka bil2 adalah yang terbesar.
Jika kedua kondisi di atas tidak terpenuhi, secara otomatis bil3 adalah bilangan terbesar. Hasil perbandingan (bilangan terbesar) akan dicetak melalui proses OUTPUT, dan alur program diakhiri dengan END.

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


Penjelasan Kode Program:

Input: Program menggunakan input() dan diubah ke tipe int() untuk menerima tiga bilangan bulat. Blok try-except digunakan untuk menangani kesalahan jika input yang dimasukkan bukan angka.

Percabangan if-elif-else:

if A >= B and A >= C:: Mengecek apakah A lebih besar atau sama dengan kedua bilangan lainnya.

elif B >= A and B >= C:: Jika kondisi pertama salah, cek apakah B lebih besar atau sama dengan A dan C.

else:: Jika kedua kondisi di atas salah, maka otomatis C adalah yang terbesar.

Output: Bilangan terbesar dicetak menggunakan fungsi print().

Hasil OUTPUT

<img width="1869" height="404" alt="image" src="https://github.com/user-attachments/assets/8569b7b8-80ed-42f7-b4ac-a3c6d4c8255c" />

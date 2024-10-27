# praktikum2vyta
# 1.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari 3 bilangan yang di inputkan  
![Screenshot 2024-10-27 102432](https://github.com/user-attachments/assets/ba89a2c1-e652-40b9-8ca8-c07234cb2870)

![Screenshot 2024-10-26 122223](https://github.com/user-attachments/assets/4b460ad0-908a-47d6-be3b-34154c45121e)

1. input bilangan

pengguna diminta untuk memasukan tiga bilangan satu per satu. Nilai yang dimasukan akan dikonversi menjadi tipe data float, yang awalnya string menjadi bilangan desimal.

2. input pengguna:

   a = float(input("Masukan bilangan pertama (A): ")
   
   b = float(input("Masukan bilangan kedua (B): ")
   
   c = float(input("Masukan bilangan ketiga (C): ")
   
4. pengggunaan (in-elif-else) untuk membandingkan ketiga bilangan:

   -if a > b and a > c: Kondisi ini mengecek apakah a lebih besar dari b dan c. jika benar, maka a adalah bilangan terbesar, dan program mencetak hasilnya.

   -elif b > a and b > c: jika kondisi pertama salah, maka program akan mengecek apakah b lebih besar dari a dan c. jika benar, maka b adalah bilangan terbesar.

   -else: jika kedua kondisi di atas salah , maka c yang di anggap bilangan terbesar

5. Output hasil:

    - Program mencetak bilangan terbesar yang ditemukan
      
   ![Screenshot 2024-10-26 122255](https://github.com/user-attachments/assets/c203a7db-8a55-4f18-acc7-811d5a2dc785)

# 2.) Buat codingan dari flowchart yang untuk menentukan bilangan terbesar dari N bilangan yang diinputkan, untuk menentukan jumlah N,berikan masukan angka 0 



![Screenshot 2024-10-26 120323](https://github.com/user-attachments/assets/b199916e-b5cd-43a1-a0d8-81c90d48c533)


1. Definisi fungsi: def cari_terbesar_dari_n():
   
fungsi ini akan mencari nilai terbesar dari N bilangan yang dimasukkan pengguna

2. Inisialisasi Variabel:

   terbesar = float('-inf')

   - membuat variabel terbesar dengan nilai awal negatif tak hingga (-inf)
     
   - ini memastikan bahwa bilangan pertama yang dimasukkan akan selalu lebih dari nilai awal
  
3. Input jumlah bilangan:

   n = int(input("Masukkan jumlah bilangan (N) atau 0 untuk mengakhiri: "))

   - Meminta pengguna memasukkan berapa banyak bilangan yang akan dibandingkan
     
   - Input dikonversi ke integer menggunakan int()

4. Pengecekan input awal:

    - jika pengguna memasukkan 0, program akan menampilkan pesan dan mengakhiri fungsi
      
    - retrun digunakan untuk keluar dari fungsi

5. perulangan dan perbandingan:

    - menggunakan loop for untuk meminta input sebanyak N kali
      
    - setiap input di konversikan ke float dan di bandingkan dengan nilai terbesar saat ini
      
    - jika bilangan yang baru dimasukkan lebih besar, nilai terbesar diperbarui

7. Output hasil :

   ![Screenshot 2024-10-26 120455](https://github.com/user-attachments/assets/de61d1e6-9b40-4c57-9164-028d100bf1f1)


      












   

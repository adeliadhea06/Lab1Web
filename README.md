# Praktikum 1 : HTML Dasar
## Lab 1 Tag HTML Dasar

Nama : Dhea Dwi Adelia

NIM : 312210116

Kelas : TI.22.A.1

- __Definisi HTML__

 _Hypertest Markup Language_ atau disebut dengan __HTML__ merupakan bahasa komputer yang digunakan untuk membuat sebuah halaman web dan menampilkan berbagai informasi didalam sebuah browser.

- Tools yang digunakan yaitu sublime text
- Berikut ini adalah langkah - langkah membuat Praktikum dasar HTML

1. Siapkan aplikasi sublime text, lalu membuat file baru dengan nama lab1_tag_dasar.html dan tambahkan tag dasar dokumen HTML
2. Kemudian di dalam tag <title> ketik text untuk menampilkan judul browser, dan diakhiri dengan </title>
  
   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/c92e3f93-c701-4661-84a9-8d2efbc7f1a1)

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/5d28ac76-3844-4ce2-9851-9348387a0d09)

3. Untuk membuat paragraf yaitu menggunakan tag seperti berikut.

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/dd8837f2-5384-40c1-b61e-ac954d991b6f)

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/5e71d5a2-e90e-4b13-9c35-5418f132f7e0)

4. Lalu ketika memberikan judul menggunakan heading.

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/4a74bbc4-33f1-4b3f-b7aa-54b6d9895837)

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/7979d02d-1533-43e8-b316-8ea28f6e8921)

5. Cara untuk memformat text menggunakan tag bold, italic, untuk marked text, dan sebagainya.

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/40a1b1c6-6cea-44d2-9396-6fcb1cf2a236)

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/72d57124-9d55-46b4-a74f-1e7f1029dac8)

6. Kemudian untuk menambahkan foto menggunakan <img src="" , src merupakan lokasi gambar yang akan ditampilkan. Sebelumnya gambar disimpan terlebih dahulu di file yang sama.

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/05133602-03c1-4745-8165-496799326f9b)

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/54bcbac4-64a9-4e46-99e5-f15cde38b48e)

   Fungsi __width__ yaitu untuk ukuran lebar gambar

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/bc05b0cf-9562-4219-b14e-f71cc8db8760)

7. Setelah itu menambahkan hyperlink
   Untuk membuat hyperlink yaitu buat file lalu cantumkan nama file tersebut menggunakan kode dibawah. Ketika di klik, akan tertuju kepada link tersebut.

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/818ec453-b5ca-46e3-ad91-966bbb94a790)

   ![image](https://github.com/adeliadhea06/Lab1Web/assets/115794875/c29d2973-9dc5-4551-aa6d-a9beaa7aa2f5)

8. Yang terakhir adalah kode dan tampilan setelah saya ubah.

   ![Screenshot (270)](https://github.com/adeliadhea06/Lab1Web/assets/115794875/705561ab-c99d-4082-950e-f013440588fb)

   ![Screenshot (269)](https://github.com/adeliadhea06/Lab1Web/assets/115794875/677ce1c5-2e56-46e8-9ac7-fbe3f4349302)

   __Body bgcolor__ yaitu untuk menambahkan warna di background web, sedangkan __padding__ untuk menata letak pada halaman web agar terlihat rapi.

### Jawab Pertanyaan Berikut
   1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
      Jawab:
      
      Ya, Karena terjadi salah penempatan tag
      
   3. Apa perbedaan dari tag <p dengan tag <br, berikan penjelasannya!
      Jawab:
      
      Tag <p benar-benar digunakan untuk mengganti paragraf untuk memudahkan memahami isi dari halaman. Sedangkan tag <br/ hanya digunakan untuk mengganti baris.
      
   5. Apa perbedaan atribut title dan alt pada tag <img, berikan penjelasannya!

      Jawab:

      - Alt adalah atribut yang ditambahkan ke tag gambar dalam HTML.

      - Sedangkan Title adalah atribut lain yang dapat ditambahkan ke tag gambar dalam HTML.
        
   7. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

      Jawab:

      Untuk mengatur ukuran gambar dalam HTML, dapat menggunakan atribut width (lebar) dan height (tinggi). Agar tampilan gambar tetap proporsional, sebaiknya mengisi hanya salah satu dari kedua atribut tersebut, biasanya width atau height, sementara yang lainnya akan dihitung secara otomatis oleh browser.
      
   9. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

      Jawab:

      - _blank :

        Ketika target="_blank" digunakan, tautan akan membuka halaman yang ditautkan dalam tab atau jendela browser baru, terpisah dari halaman asal. Ini berguna ketika Anda ingin menjaga pengguna tetap di halaman asal dan membuka tautan eksternal atau tautan yang tidak ingin menggantikan halaman asal.

        - _self :
          
          Ini adalah nilai default untuk atribut target. Ketika target="_self" digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab yang sama di mana halaman asal berada. Ini berarti halaman asal akan digantikan dengan halaman yang baru.

          - _top :

            Ketika target="_top" digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab paling atas atau paling tinggi dalam tumpukan jendela browser. Jadi, jika halaman asal ada dalam bingkai (frame), tautan akan membuka halaman baru di luar bingkai tersebut.

            - _parent :

              target="_parent" digunakan ketika halaman web memiliki bingkai (frame) yang saling terkait. Ini akan membuka tautan di jendela atau tab yang menggantikan bingkai "induk" yang berisi tautan tersebut.

# Aplikasi Web "Writing"


## Sekilas Tentang

**Writing** adalah _lightweight distraction-free_ teks editor di browser.


## Instalasi #1 (Hosting di Heroku)

#### Kebutuhan Sistem
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
- Git account
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
- Heroku account


#### Langkah instalasi dalam CLI.
1. Fork repository *Writing* ke akun github personal
   - Tekan tombol Fork
![image](https://user-images.githubusercontent.com/70611863/196932464-53eb7824-0c71-4b57-887f-5455b41c3b90.png)

   - Pilih Create fork
![image](https://user-images.githubusercontent.com/70611863/196934169-df0db5fc-003e-45ff-9638-45d8a72431e5.png)

2. Buat file bernama index.php
   ```
   touch index.php
   ```
   
3. Buat file bernama composer.json
   ```
   touch composer.json
   ```

4. Dengan text editor, masukkan kode berikut ke dalam file-file tersebut
   - index.php
   ```
   <?php include_once("index.html"); ?>
   ```
   
   - composer.json
   ```
   {}
   ```
5. Commit kedua file tersebut ke dalam fork github yang telah dibuat
   - Klik tombol Add file dan pilih Upload files
![image](https://user-images.githubusercontent.com/70611863/196934444-e015fd1c-c914-4dfa-8c13-c3eea04d0b73.png)

   - Masukkan file index.php dan composer.json lalu tekan Commit changes
![image](https://user-images.githubusercontent.com/70611863/196934701-3686adab-df69-4078-816d-ea4c4315389a.png)


6. Clone repositori *Writing* yang telah ditambahkan index.php dan composer.json ke direktori lokal
   - Tekan tombol Code dan copy link repository
![image](https://user-images.githubusercontent.com/70611863/196936172-40e2c4a6-2d1e-49ba-9bc4-26e223afa68e.png)

   - Buka cmd dalam direktori yang diinginkan lalu masukkan command
   ```
   git clone https://github.com/Raff-28/writing.git
   cd writing
   ```
   
7. Login kedalam Heroku CLI
   ```
   heroku login
   ```
 
8. Membuat heroku app dengan nama komdatp3-kel7
   ```
   heroku create komdatp3-kel7
   ```
   
9. Mendeploy aplikasi ke heroku
   ```
   git push heroku master
   ```
   
10. Membuka aplikasi *Writing* yang telah dihost pada Heroku
      ```
      heroku open
      ```


## Instalasi #2 (Hosting di Netlify)

#### Kebutuhan Sistem
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
- Git account
- Netlify account


#### Langkah instalasi.
1. Clone *Writing* ke dalam direktori kita
   ```
   $ git clone https://github.com/josephernest/writing.git
   ```
   
2. Sambungkan github kita dengan Netlify
![image](https://user-images.githubusercontent.com/70611852/196861862-0d51835c-b180-4a01-9537-e4b2c85692e5.png)

3. Pilih repository yang telah kita clone sebelumnya
![image](https://user-images.githubusercontent.com/70611852/196861962-b6b1db4f-a793-441e-905c-83542e1788c6.png)


4. Deploy ke Netlify
![image](https://user-images.githubusercontent.com/70611852/196862011-6da19537-e261-45a3-8e68-3fafd8e937d0.png)

   
## Konfigurasi

Tidak ada


##  Maintenance

Untuk melakukan perubahan pada kode menggunakan CLI, dilakukan sebagai berikut.
   ```
   git add .
   git commit -am "Commit desc"
   ```
   

## Otomatisasi

Tidak ada


## Cara Pemakaian

Cara pemakaian **Writing** ini sangat mudah. Berikut untuk lebih jelasnya :

- CTRL + D: Mengganti mode tampilan
- CTRL + P: Print atau export dalam bentuk PDF
- CTRL + S: Menyimpan source code dalam bentuk file .MD

dan beberapa command lain yang dapat dilihat pada:

- CTRL + SHIFT + H: Show help
![image](https://user-images.githubusercontent.com/70611852/196862433-b0acb869-35ab-4338-b6e3-aa6fa39d190d.png)

![image](https://user-images.githubusercontent.com/70611852/196862368-58c51c8b-3745-405b-aed3-cb88f1bf74e5.png)


## Pembahasan
**Writing** merupakan editor *markdown* yang cukup simpel. Beberapa kelebihan dari editor ini yaitu:
- *Fast rendering* (Tidak ada delay dan flickering).
- Sesuai kebutuhan utama
   - write
   - preview
   - save code
   - print / save as pdf
- Minimalist / Distraction-free (Dapat langsung dipakai tanpa welcome page, login page, dsb).

Tentu saja, sebuah aplikasi pasti memiliki kekurangan. Kekurangan yang dimiliki **Writing** antara lain:
- Kurang menarik dari segi tampilan. 
- Tidak ada otomatisasi fitur atau shortcut untuk memudahkan pengetikan seperti **bold**, *italic*, ~~strikethrough~~, dsb
- Harus mengingat atau menghafal syntax untuk menulis markdown

Jika dibandingkan dengan editor sejenisnya seperti **StackEdit**, editor ini memiliki beberapa keunggulan dan kelemahan. Berikut adalah beberapa perbandingan antara keduanya :
- **Writing** menyediakan editor *lightweight* yang simpel, minimalis, sesuai kebutuhan, dan tidak ada delay ataupun flicker.
- Kekurangannya yaitu kurang menarik dari segi tampilan dan tidak adanya fitur otomatisasi yang dapat memudahkan pengetikan.
- **StackEdit** lebih menarik dari segi tampilan, serta memiliki fitur otomatisasi yang cukup lengkap. 
- Sayangnya editor ini memiliki kekurangan yang dirasa cukup mengganggu, yaitu adanya delay dan seringnya terjadi flicker ketika ada persamaan matematika dalam ketikan. 

**Writing**
![image](https://user-images.githubusercontent.com/70611852/196862604-7a15ff05-145b-4e04-b37b-f9f36811c2a0.png)

**StackEdit**
![image](https://user-images.githubusercontent.com/70611852/196862588-3f44124d-ac37-44d9-ad19-0f788d508b43.png)



## Referensi
1. [Writing](https://github.com/josephernest/writing) - Writing
2. [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) - Heroku CLI
3. [Netlify](https://www.netlify.com/) - Netlify
4. [StackEdit](https://stackedit.io/) - StackEdit

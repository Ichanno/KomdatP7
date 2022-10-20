# Aplikasi Web "Writing"


## Sekilas Tentang

**Writing** adalah _lightweight distraction-free_ teks editor di browser.


## Instalasi

#### Kebutuhan Sistem
- Heroku CLI


#### Langkah instalasi dalam CLI.
1. Clone *Writing* ke dalam direktori kita
   ```
   $ git clone https://github.com/josephernest/writing.git
   ```
   
2. Login kedalam Heroku CLI
   ```
   heroku login
   ```

3. Membuat heroku app dengan nama komdatp3-kel7
   ```
   heroku create komdatp3-kel7
   ```
   
4. Mendeploy aplikasi ke heroku
   ```
   git push heroku main
   ```


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

- Tampilan aplikasi web
- Fungsi-fungsi utama
- Isi dengan data real/dummy (jangan kosongan) dan sertakan beberapa screenshot


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


## Referensi

Cantumkan tiap sumber informasi yang anda pakai.

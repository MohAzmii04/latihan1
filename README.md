**Hallo nama saya Mohammad Azmi Abdussyukur.** Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah Applikasi git , akun git. Sebelum itu saya akan kasih tutorial cara penginstalan GIT.

**Cara penginstalan GIT**

Pertama anda harus mendownload Aplikasi Git, buka website resminya Git di git-scm.com .
![195978004-f83ef297-525c-4675-8d1e-61391bcb8a78](https://user-images.githubusercontent.com/115864496/196386932-2ded26b9-09ef-4732-bae0-97e6035c2349.png)
 Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

![67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8](https://user-images.githubusercontent.com/115864496/196388507-e277a256-20bf-46be-a17f-1effae993bba.png)

Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1
![195978194-04778e47-f0cd-4d03-9ceb-23394a12b588](https://user-images.githubusercontent.com/115864496/196388786-2a7a0bb3-cf92-4642-8956-f291bba8b859.png)

**Cara membuat akun git**
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
![195978233-065cd98e-8f18-4b11-ab55-3ebec7a60813](https://user-images.githubusercontent.com/115864496/196389090-91a71f79-3f43-4864-b7c3-7d45c0abdc21.png)

Pada langka selanjutnya anda boleh langsung diskip saja.

**Membuat repositori baru**
Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![195978469-53789f6c-4d88-4b94-ac44-77d8c05be1f0](https://user-images.githubusercontent.com/115864496/196391143-95798c95-df44-4009-92c7-2fee2e450e8d.png)


Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.

![195978342-860c1ebf-98a0-470c-8586-272e72bfc79d](https://user-images.githubusercontent.com/115864496/196391466-b49ff5eb-6813-4863-9ab0-44b1dd522687.png)


Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

![195978391-435ade62-7139-47d7-b50b-073c6c000bdb](https://user-images.githubusercontent.com/115864496/196391809-9f10f727-a4e3-4b15-be20-0c83b4453c21.png)


Membuat Repository Local
Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here .
![195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f](https://user-images.githubusercontent.com/115864496/196393358-475135a6-01d4-4124-b20d-6da8c349a77c.png)

Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “email_user” $ git config --global user.name “nama_user”

![email](https://user-images.githubusercontent.com/115864496/196398009-156e62c6-8484-4fb6-8304-66a4d7b3b613.png)


Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1 ![cd labpemograman](https://user-images.githubusercontent.com/115864496/196398284-02c1aa5d-ef66-48e6-90c6-f38b69b336b5.png)
 ".

Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

![cara penggunnaan 1](https://user-images.githubusercontent.com/115864496/196398749-eecce526-b3ea-4450-b13b-ec177a23915f.png)


Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

![membuat file readme](https://user-images.githubusercontent.com/115864496/196398850-395c54b5-0293-46c1-a495-4a73bb20f060.png)


Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. 
![git addddd](https://user-images.githubusercontent.com/115864496/196596849-af6fde52-c639-4ee6-8d46-ad48b1ae679c.png)


Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit" 67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3
![commit](https://user-images.githubusercontent.com/115864496/196596983-2fee026a-1948-4ed4-9f71-97085a00a898.png)


File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/MohAzmii04/latihan1 
![url](https://user-images.githubusercontent.com/115864496/196597155-cd8fc19a-1373-42ef-b93f-2c6c31d9136f.png)

Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. git_push

![1](https://user-images.githubusercontent.com/115864496/196597649-81c3940d-c87b-47df-9db1-ece2879146ce.png)


Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/MohAzmii04/latihan1 . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1" git_push

![end](https://user-images.githubusercontent.com/115864496/196597935-8cb1527a-160b-47fd-b30a-619fa62e6dea.png)

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya
FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.

**Terimakasih**

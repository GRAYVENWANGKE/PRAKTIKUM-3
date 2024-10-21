# Cara Membuat Repository
<p>Dalam petunjuk ini, saya akan membahas bagaimana cara membuat repository baru di windows.</p>

## 1 persiapan
siapkan software bernama "git" bisa di download di website resmi https://git-scm.com/downloads

### installasi
jalankan setup git yang didownload dan akan muncul jendela seperti ini :
![jendela install](![home - Imgur](![git - Imgur](https://github.com/user-attachments/assets/cd8788bc-d93c-4aa8-bbdc-b45a4f77931e))
klik next saja sampai selesai dan install

## 2. Membuat akun Github
<p>Selanjutnya anda harus mempunyai akun github terlebih dahulu, jika anda belum pernah mendaftar, silahkan anda kunjungi website github.com lalu buat akun github</p>

### buat repository.
klik tombol "+" pada sudut kanan atas halaman web lalu klik "new repository"
![menambah repository](https://i.imgur.com/MqIEA8T.png)
maka akan mucul halaman di bawah ini :
![halaman penambahan repository](![home - Imgur](![indomie rebus - Imgur](https://github.com/user-attachments/assets/9d1d1c96-ea2c-4b92-879d-00c992b96018)
)
)
isi nama repository sesuai keinginan anda lalu klik "create repository"

## 3 cara menggunakan git
buka software "git bash" yang sudah di install tadi, lalu ketikkan command line di bawah ini :
```
$ git config --global user.name "username yg anda buat di github"
$ git config --global user.email "email yg anda pakai untuk github"
```
contohnya seperti ini:
![contoh 1](![undefined - Imgur](![sarimi isi 2 - Imgur](https://github.com/user-attachments/assets/4e3567fe-252a-4947-8c25-18cec406426e)
)
lalu ketik command:
```
$ git config --list
```
maka akan muncul seperti ini:
![contoh 2](![git - Imgur (1)](![sedap goreng - Imgur](https://github.com/user-attachments/assets/a663ec0a-f478-4ad7-9e1c-0bfb131f920f)
)


jika username dan email terisi sesuai yg anda ketik berarti berhasil
lalu buat folder untuk tempat menyimpan repository local di komputer anda dengan cara buat new folder di tempat yg anda suka contohnya:
![contoh 3](![gitt - Imgur](https://github.com/user-attachments/assets/f0958cc4-f3ce-46d0-9c25-1bd673c54ee8))

saya membuat folder "latihanvcs" di drive D
lalu klik kanan dan pilih "git bash here"
lalu ketik command:
```
$ git init
```
Lalu masukan perintah berikut untuk membuat file "readme.md"
```
$ echo "# Latihan1" >> readme.md
```
lalu ketik :
```
$ git add readme.md
```
setelah itu commit dengan cara :
```
$ git commit -m "komentar"
```
contohnya seperti ini:
![contoh 4](![git - Imgur (3)](![mie goyeng - Imgur](https://github.com/user-attachments/assets/a3dc6211-cbb3-43ad-ba35-8ea650f04310)
)

lalu ketik:
```
$ git remote add origin "link url repository di github"
```
contoh bisa dilihat di gambar sebelumnya
untuk mendapatkan link repository yg anda buat anda tinggal ke akun github anda
klik repository yg anda buat
![contoh 5](![posting - Imgur](![mie sakura - Imgur](https://github.com/user-attachments/assets/bd37d1f6-f8db-499a-a827-75429b1252bf)
)


lalu klik klik copy or download
![contoh 6](![copy or download - Imgur](https://github.com/user-attachments/assets/def8c62e-fa57-42ce-ba7c-3ec6087a0db3))


lalu ketik :
```
$ git push -u origin master
```
lalu anda akan diminta username dan password untuk login ke github anda dan selamat repository anda berhasil di isi (upload) dengan file readme.md silahkan cek repository anda di github dan anda akan melihat perubahan yg tadinya kosong menjadi berisi file readme.md

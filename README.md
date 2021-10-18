# LatihanVCS
# Cara install Git di Windows
# 1. Unduh Git
untuk menginstall Git, anda perlu mengunduh file-nya terlebih dahulu di situs resminya. karena saya pakai git-scm, linknya adalah https://git-scm.com/
# 2. Install Git
setelah selesai mengunduh file Git, silahkan install aplikasi nya, caranya seperti dibawah ini

![Install git 1](https://user-images.githubusercontent.com/92351461/136926471-6ddf0c29-7cab-4f4c-a0c6-a6b67b5678e7.PNG)

lalu klik next terus seperti gambar dibawah, sampai ke menu install

![Install git 2](https://user-images.githubusercontent.com/92351461/136926593-540ea778-2c0e-4b7b-ba03-2f7b952a1e76.PNG)

![Install git 3](https://user-images.githubusercontent.com/92351461/136926700-ab019616-6717-4744-8ec5-8918a1952269.PNG)

![Install git 4](https://user-images.githubusercontent.com/92351461/136926702-635bf4aa-3ad9-41b6-9f1a-57adabf7975f.PNG)

![Install git 5](https://user-images.githubusercontent.com/92351461/136926705-6b4a0439-1c19-4e68-ba30-093ed900a8db.PNG)

![Install git 6](https://user-images.githubusercontent.com/92351461/136926709-7ebe5029-b314-4782-9cfe-c6b5c0d23779.PNG)

![Install git 7](https://user-images.githubusercontent.com/92351461/136926710-8b019626-6642-412d-a9c8-6a1c9ffe0ab8.PNG)

![Install git 8](https://user-images.githubusercontent.com/92351461/136926716-974bf591-3a41-4b45-b739-a103a94fdc4c.PNG)

![Install git 9](https://user-images.githubusercontent.com/92351461/136926721-b5527ecc-2ae7-4ab4-a44a-16fedc4b84c0.PNG)

![Install git 10](https://user-images.githubusercontent.com/92351461/136926724-8ca7a0d3-956d-43db-9b1b-2e32d663aa14.PNG)

![Install git 11](https://user-images.githubusercontent.com/92351461/136926673-b5959ca7-440c-477b-9c17-ba8b7a5222a8.PNG)

![Install git 12](https://user-images.githubusercontent.com/92351461/136926679-f9aa4fc1-6b38-4813-b000-d666abff0edb.PNG)

![Install git 13](https://user-images.githubusercontent.com/92351461/136926684-8f38e6c4-c2b3-4940-adc7-91f9fec10faf.PNG)

![Install git 14](https://user-images.githubusercontent.com/92351461/136926688-181e19b5-19b0-4eeb-9e3d-730e6526c305.PNG)

![Install git 15](https://user-images.githubusercontent.com/92351461/136926692-e5609eb6-53dd-4d23-b9e3-5e39b16920f7.PNG)

![Install git 16](https://user-images.githubusercontent.com/92351461/136926696-b1ea483c-9127-46fb-a307-228b2ce5bd27.PNG)


# 3. setelah proses instalasi selesai, saatnya membuat akun jika belum memiliki akun, dan silahkan masuk ke akun github anda, jika sebelumnya telah memiliki akun github

![login git 1](https://user-images.githubusercontent.com/92351461/136927491-9770276a-b0dc-43f3-8c5b-8491df9db141.PNG)

# 4. setelah berhasil login di github, saatnya anda membuat file repository baru, seperti gambar dibawah ini

![login git 2](https://user-images.githubusercontent.com/92351461/136927758-6f562ff0-0350-467a-a569-5947586264c9.PNG)

# 5. isikan repository name, dan pilih repository untuk jadi file public atau private, saya buat public disini, setelah itu centang pilihan add a readme file, lalu klik create repository

![login git 3](https://user-images.githubusercontent.com/92351461/136928161-a9a918b6-ab89-407d-a531-81bbb05b7d99.png)

cek kembali file repository anda, jika sudah terdapat file repository yang anda buat tadi, maka pembuatan repository berhasil. sekian terima kasih.

# Cara Menggunakan Git

# Pada saat pertama kali menggunakan Git, kita perlu melakukan konfigurasi username dan email yang telah kita daftarkan di github, dengan cara berikut ini:

git config --global user.name "username"
git config --global user.name "email"

![git 1](https://user-images.githubusercontent.com/92351461/137724853-17b669f6-89a3-4db0-bf78-2dde5ef940da.PNG)

setelah itu, jalankan perintah git init untuk membuat repository local, seperti gambar di bawah, karena saya sudah memiliki repository, maka tampilannya akan seperti ini

git init
![git 2](https://user-images.githubusercontent.com/92351461/137725076-4adc51f4-dddd-4628-9e87-615e4b23b65d.PNG)

untuk membuat file, dapat menggunakan Text Editor, lalu menyimpan file pada repository. saya membuat file readme.md dengan perintah berikut

echo "#latihanGit" >> readme.md
![git 3](https://user-images.githubusercontent.com/92351461/137725441-7ab9a396-57e5-4d87-b85e-e625f470e1c7.PNG)

untuk menambahkan file yang telah kita buat, gunakan perintah git add (nama file), tanpa tanda dalam kurung, seperti contoh dibawah, saya menambahkan file readme.md, dan jika terjadi kesalahan ketik, seperti readme.md tetapi kita ketik raedme.md, maka akan muncul informasi (fatal: pathspech 'raedme.md' did not match any files (karena direktori tidak ada file yang bernama tersebut

git add readme.md
![git 4](https://user-images.githubusercontent.com/92351461/137726124-9c3de82b-d6e4-48c1-9517-887a154f0902.PNG)

setelah itu, untuk menyimpan perubahan yang ada ke dalam database repository lokal, gunakan perintah git commit -m "nama project", tulis dengan nama komentar setiap kita men-commit projek, saya menambahkan project dengan nama menambahkan project

git commit -m "menambahkan project"
![git 5](https://user-images.githubusercontent.com/92351461/137726647-d7e8f850-8284-4efd-8e30-27663ffbbfb0.PNG)

untuk menyimpan setiap perubahan pada repository lokal, kita gunakan perintah git remote add origin diikuti dengan url file repository kita di github, seperti dibawah ini, saya membuat repository github dengan nama file LatihanVCS

untuk mendapatkan link repository di github, kita dapat masuk ke akun github, dan klik repository yang telah kita buat, lalu klik code, dan link tersebut dapat kita paste kan seperti ini
![git 6](https://user-images.githubusercontent.com/92351461/137727435-114d52d0-14f1-4907-ae5a-ae18a791774b.PNG)

git remote add origin https://github/rezansap/LatihanVCS.git
![git 7](https://user-images.githubusercontent.com/92351461/137727082-a69518c9-dad9-4fcb-9e5a-da7bdd2a3983.PNG)

dan untuk mengirim perubahan pada repository lokal ke server, gunakan perintah git push, perintah ini akan meminta kita untuk memasukan username dan password pada akun github kita

git push -u origin master
![git 8](https://user-images.githubusercontent.com/92351461/137728559-5e3859f5-e53e-4db1-8fd8-b6848d0a1fb4.PNG)

Selesai, sekian dan terima kasih

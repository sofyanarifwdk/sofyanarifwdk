# Cara penggunaan git
Cara penggunaan git atau github untuk berkolaborasi mengelola pekerjaan

### 1. Download Git
*   Download Git, buka website resminya Git (git-scm.com).
*   Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
    menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
*   Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan
    buka CMD atau PowerShell, kemudian ketik perintah.
<img scr="tugas/images/downloadgit.png">

*   Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email 
*   konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
*   apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan 
    saat menjalankan perintah git commit.
*   Config Global Repository

<img scr="tugas/images/gitconfig.png">

### 2. Perintah dasar Git
* git config
    Salah satu perintah git yang paling banyak digunakan adalah git config, yang bisa digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll. Contohnya, perintah berikut bisa digunakan untuk mengatur email:

<img scr="tugas/images/gitconfig.png">


* git init
    Perintah ini digunakan untuk membuat repositori baru. Caranya:

* git add
    Perintah git add bisa digunakan untuk menambahkan file ke index. Contohnya, perintah berikut ii akan menambahkan file bernama temp.txt yang ada di direktori lokal ke index:

* git clone
    Perintah git clone digunakan untuk checkout repositori. Jia repositori berada di remove server, gunakan:

    Jika salinan repositori lokal ingin dibuat, gunakan:


* git commit
    Perintah git commit digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository. Gunakan:

* git status
    Perintah git status menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit. Gunakan:

* git push
    git push adalah perintah git dasar lainnya. Push akan mengirimkan perubahan ke master branch dari remote repository yang berhubungan dengan direktori kerja Anda. Misalnya:

* git checkout
    Perintah git checkout bisa digunakan untuk membuat branch atau untuk berpindah diantaranya. Misalnya, perintah berikut ini akan membuat branch baru dan berpindah ke dalamnya:

    Untuk berpindah dari branch satu ke lainnya, gunakan:

* git remote
    Perintah git remote akan membuat user terhubung ke remote repository. Perintah berikut ini akan menampilkan repository yang sedang dikonfigurasi:    

    Perintah ini membuat user bisa menghubungkan repository lokal ke remote server:


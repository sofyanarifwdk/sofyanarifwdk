# Cara penggunaan git
Cara penggunaan git

### 1. Download Git
*   Download Git, buka website resminya Git (git-scm.com).
![downloadgit](https://user-images.githubusercontent.com/79274212/195904905-ad5c7f21-b92b-4416-acb0-f5d657e5842d.png)
*   Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
    menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
*   Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan
    buka CMD atau PowerShell, kemudian ketik perintah.

<img scr="tugas/images/gitversion.png">

*   Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email 
*   konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
*   apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan 
    saat menjalankan perintah git commit.
*   Config Global Repository

<img scr="tugas/images/gitconfig.png">

### 2. Perintah dasar Git

* git config
    Salah satu perintah git yang paling banyak digunakan adalah git config, yang bisa digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll. Contohnya, perintah berikut bisa digunakan untuk mengatur email:
    
    
    $ git config --global user.email sam@google.com

<img scr="tugas/images/gitconfig.png">


* git init
    Perintah ini digunakan untuk membuat repositori baru. Caranya:
    
    
    
    $ git init

<img scr="tugas/images/gitinit.png">


* git add
    Perintah git add bisa digunakan untuk menambahkan file ke index. Contohnya, perintah berikut ini akan menambahkan file bernama temp.txt yang ada di direktori lokal ke index:
    
    
    
    $ git add temp.txt

<img scr="tugas/images/gitadd.png">

* git clone
    Perintah git clone digunakan untuk checkout repositori. Jia repositori berada di remove server, gunakan:
    
    
    
    $ git clone alex@93.188.160.58:/path/to/repository

<img scr="tugas/images/clone 1.png">

    Jika salinan repositori lokal ingin dibuat, gunakan:
    
    
    
    $ git clone /path/to/repository

<img scr="tugas/images/clone 2.png">

* git commit
    Perintah git commit digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository. Gunakan:
    
    
    
    $ git commit –m “Isi dengan keterangan untuk commit”

<img scr="tugas/images/gitcommit.png">

* git status
    Perintah git status menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit. Gunakan:
    
    
    
    $ git status

<img scr="tugas/images/gitsts.png">

* git push
    git push adalah perintah git dasar lainnya. Push akan mengirimkan perubahan ke master branch dari remote repository yang berhubungan dengan direktori kerja Anda. Misalnya:
    
    
    
    $ git push -u origin master

<img scr="tugas/images/gitpush.png">

* git checkout
    Perintah git checkout bisa digunakan untuk membuat branch atau untuk berpindah diantaranya. Misalnya, perintah berikut ini akan membuat branch baru dan berpindah ke dalamnya:
    
    
    
    $ command git checkout -b <nama-branch>

<img scr="tugas/images/gitcheckout1.png">

    Untuk berpindah dari branch satu ke lainnya, gunakan:
    
    
    
    $ git checkout <branch-name>

<img scr="tugas/images/gitcheckout2.png">

* git remote add origin [url]
    Perintah git remote akan membuat user terhubung ke remote repository. Perintah berikut ini akan menampilkan repository yang sedang dikonfigurasi:    
    
    
    
    $ git remote add origin https://github.com/abuazzam/labpy1.git

<img scr="tugas/images/gitremote1.png">

    Perintah ini membuat user bisa menghubungkan repository lokal ke remote server:
    
    
    
    $ git remote add origin <93.188.160.58>

<img scr="tugas/images/gitremote2.png">

* git branch
    Perintah git branch bisa digunakan untuk me-list, membuat atau menghapus branch. Untuk menampilkan semua branch yang ada di repository, gunakan:
    
    
    
    $ git branch

<img scr="tugas/images/gitbranch1.png">

    Untuk menghapus branch:
    
    
    
    $ git branch -d <branch-name>

<img scr="tugas/images/gitbranch2.png">

* git pull
    Untuk menggabungkan semua perubahan yang ada di remote repository ke direktori lokal, gunakan perintah pull:
    
    
    
    $ git pull

<img scr="tugas/images/gitpull.png">

* git merge
    Perintah merge digunakan untuk menggabungkan sebuah branch ke branch aktif. Gunakan:
    
    
    
    $ git merge <nama-branch>

<img scr="tugas/images/gitmerger.png">

### 3. Cara Penggunaan Git

    1.  bagaimana menambahkan folder baru yang di beri nama "tugas"

        $ mkdir tugas
    
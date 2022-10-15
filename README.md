# Cara penggunaan git
Cara penggunaan git

### 1. Download Git
*   Download Git, buka website resminya Git (git-scm.com).
![downloadgit](https://user-images.githubusercontent.com/79274212/195904905-ad5c7f21-b92b-4416-acb0-f5d657e5842d.png)
*   Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
    menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
*   Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan
    buka CMD atau PowerShell, kemudian ketik perintah.

![gitversion](https://user-images.githubusercontent.com/79274212/195978591-bc684e7f-d79b-447b-b1a6-f5a8c6a56534.png)
<img scr="tugas/images/gitversion.png">

*   Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email 
*   konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
*   apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan 
    saat menjalankan perintah git commit.
*   Config Global Repository
![gitconfig](https://user-images.githubusercontent.com/79274212/195976229-67b98caf-7514-4a09-983e-5c2092c79db5.png)
<img scr="tugas/images/gitconfig.png">

### 2. Perintah dasar Git

* git config
    Salah satu perintah git yang paling banyak digunakan adalah git config, yang bisa digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll. Contohnya, perintah berikut bisa digunakan untuk mengatur email:
</br><br\>   
    $ git config --global user.email sam@google.com
![gitconfig](https://user-images.githubusercontent.com/79274212/195976229-67b98caf-7514-4a09-983e-5c2092c79db5.png)

<img scr="tugas/images/gitconfig.png">


* git init
    Perintah ini digunakan untuk membuat repositori baru. Caranya:
    
    $ git init

![gitinit](https://user-images.githubusercontent.com/79274212/195976332-3ba657c9-cf14-49ee-abc0-5b8192584e7a.PNG)

<img scr="tugas/images/gitinit.png">


* git add
    Perintah git add bisa digunakan untuk menambahkan file ke index. Contohnya, perintah berikut ini akan menambahkan file bernama temp.txt yang ada di direktori lokal ke index

    $ git add temp.txt

![gitadd](https://user-images.githubusercontent.com/79274212/195976324-521c3afa-b8cc-4fb4-85ca-bbbddd6584c1.PNG)

<img scr="tugas/images/gitadd.png">

* git clone
    Perintah git clone digunakan untuk checkout repositori. Jia repositori berada di remove server, gunakan:
    
    $ git clone alex@93.188.160.58:/path/to/repository

![clone 1](https://user-images.githubusercontent.com/79274212/195976319-3b4fff6f-bc01-4724-9371-4ecd0b5c14aa.PNG)

<img scr="tugas/images/clone 1.png">

    Jika salinan repositori lokal ingin dibuat, gunakan:

    $ git clone /path/to/repository

![clone 2](https://user-images.githubusercontent.com/79274212/195976320-e78c6b33-0651-4dfe-a0d3-03de9325b8b9.PNG)

<img scr="tugas/images/clone 2.png">

* git commit
    Perintah git commit digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository. Gunakan:

    $ git commit –m “Isi dengan keterangan untuk commit”

![gitcommit](https://user-images.githubusercontent.com/79274212/195976330-14879088-0496-4e70-ad82-a892f72a8909.PNG)

<img scr="tugas/images/gitcommit.png">

* git status
    Perintah git status menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit. Gunakan:

    $ git status

![gitsts](https://user-images.githubusercontent.com/79274212/195976295-443a0ede-ba38-4367-b7b5-2cfd0b7804a0.PNG)

<img scr="tugas/images/gitsts.png">

* git push
    git push adalah perintah git dasar lainnya. Push akan mengirimkan perubahan ke master branch dari remote repository yang berhubungan dengan direktori kerja Anda. Misalnya:  

    $ git push -u origin master

![gitpush](https://user-images.githubusercontent.com/79274212/195976336-e3128838-6106-46b1-9bf9-927dae0e6ee7.PNG)

<img scr="tugas/images/gitpush.png">

* git checkout
    Perintah git checkout bisa digunakan untuk membuat branch atau untuk berpindah diantaranya. Misalnya, perintah berikut ini akan membuat branch baru dan berpindah ke dalamnya:

    $ command git checkout -b <nama-branch>

![gitcheckout1](https://user-images.githubusercontent.com/79274212/195976328-792ca02b-f83b-4ae4-8986-1d09c100cf79.PNG)

<img scr="tugas/images/gitcheckout1.png">

    Untuk berpindah dari branch satu ke lainnya, gunakan:

    $ git checkout <branch-name>

![gitcheckout2](https://user-images.githubusercontent.com/79274212/195976329-f3dbd636-4212-43e0-bf19-244fa07bf8b1.PNG)

<img scr="tugas/images/gitcheckout2.png">

* git remote add origin [url]
    Perintah git remote akan membuat user terhubung ke remote repository. Perintah berikut ini akan menampilkan repository yang sedang dikonfigurasi:  
    
    $ git remote add origin https://github.com/abuazzam/labpy1.git

![gitremote1](https://user-images.githubusercontent.com/79274212/195976338-d2cad2ae-b0d6-46db-8048-cc489aed3c8d.PNG)

<img scr="tugas/images/gitremote1.png">

    Perintah ini membuat user bisa menghubungkan repository lokal ke remote server:   

    $ git remote add origin <93.188.160.58>

![gitremote2](https://user-images.githubusercontent.com/79274212/195976294-ea8664a8-c347-439f-8686-e0dbc0d95d69.PNG)

<img scr="tugas/images/gitremote2.png">

* git branch
    Perintah git branch bisa digunakan untuk me-list, membuat atau menghapus branch. Untuk menampilkan semua branch yang ada di repository, gunakan:

    $ git branch

![gitbranch1](https://user-images.githubusercontent.com/79274212/195976326-03c33a8c-e133-49aa-927f-6b2bb64bdaca.PNG)

<img scr="tugas/images/gitbranch1.png">

    Untuk menghapus branch:

    $ git branch -d <branch-name>

![gitbranch2](https://user-images.githubusercontent.com/79274212/195976327-e333933a-848e-460d-96b3-9ba59ef0efd0.PNG)

<img scr="tugas/images/gitbranch2.png">

* git pull
    Untuk menggabungkan semua perubahan yang ada di remote repository ke direktori lokal, gunakan perintah:

    $ git pull

![gitpull](https://user-images.githubusercontent.com/79274212/195976335-4d047d52-67e4-4203-ae54-8c9aa0a1b228.PNG)

<img scr="tugas/images/gitpull.png">

* git merge
    Perintah merge digunakan untuk menggabungkan sebuah branch ke branch aktif gunakan perintah:

    $ git merge <nama-branch>

![gitmerger](https://user-images.githubusercontent.com/79274212/195976333-629f7b3d-69e5-4f38-8dc2-9a205142def6.PNG)

<img scr="tugas/images/gitmerger.png">

### 3. Cara Penggunaan Git  

    1. Buat folder terlebih dahulu Contoh "LatihanVCS" lalu klik kanan pada folder pilih Git Bash Here

![folder](https://user-images.githubusercontent.com/79274212/195976322-39551ed8-70f9-431e-973e-813d5d5e9674.png)

<img scr="tugas/images/folder.png">

    gambar Git Bash :
![viewgitbash](https://user-images.githubusercontent.com/79274212/195976301-a4181de1-9673-4c52-97df-63d2c291e898.PNG)

<img scr="tugas/images/viewgitbash.png">

    2. Selanjutnya kita tambahkan folder baru di dalam folder "LatihanVCS" dengan menggunakan Gitbash perintahnya yang di ketik :

    $ mkdir tugas

![0](https://user-images.githubusercontent.com/79274212/195976642-13ab5f5b-4aab-4c31-9e57-e4dc3778ae77.PNG)

    $ cd tugas
![1](https://user-images.githubusercontent.com/79274212/195976302-ff61efea-105a-4361-bf98-823fd321175e.PNG)

    3.  Lalu kita akan membuat repository di file lokal perintahnya :

    $ git init
![gitinit](https://user-images.githubusercontent.com/79274212/195976332-3ba657c9-cf14-49ee-abc0-5b8192584e7a.PNG)

    4.  di sini kita akan buat satu file bernama README.md (text file) :

    $ echo "# Latihan 1" >> README.md
![2](https://user-images.githubusercontent.com/79274212/195976303-ffb32703-2994-4ab5-a673-bdeb629e5f92.PNG)

    disini file README.md berhasil dibuat :
![3](https://user-images.githubusercontent.com/79274212/195976304-513bada0-7b65-444a-aebe-be7957c88589.PNG)

    5.  Untuk menambahkan file baru saja kita buat, gunakan perintah berikut :

    $ git add README.md
![4](https://user-images.githubusercontent.com/79274212/195976305-a8a403b8-42cf-4f0f-ba13-8779efccd7d1.PNG)

    6.  Lalu untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah :

    $ git commit –m “Isi dengan keterangan untuk commit”

    perubahan berhasil disimpan :
![5](https://user-images.githubusercontent.com/79274212/195976306-e4c7f155-196f-4832-adcd-52e1ce58862c.PNG)

    7.  Kemudian untuk menambahkan remote repository server, gunakan perintah :

    $ git remote add origin [url]

    tampilanya :
![6](https://user-images.githubusercontent.com/79274212/195976307-73ba4692-1bbf-4b37-b042-33ca64b1cffa.PNG)

    8.  Untuk mengirim perubahan pada local repository ke server gunakan perintah berikut :

    $ git push -u origin master

    contoh tampilan :
![7](https://user-images.githubusercontent.com/79274212/195976308-3f91fa6f-8984-43fd-844e-af4f255b453b.PNG)

    9.  Selesai.



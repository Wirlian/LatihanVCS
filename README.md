# LatihanVCS

================Membuat Repository Lokal=====================

1. Pertama buka direktori aktif untuk membuat project git
2. klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,
	sehingga muncul git bash command
3. lalu buat direktori untuk project baru dengan perintah 
	mkdir LatihanVCS
4. lalu masuk ke direktori procect yang akan di buat dengan perintah
	cd LatihanVCS
5. setelah itu jalankan perintah 
	git init
6. dengan terbentuknya satu direktori hidden dengan nama .git pada direktori tersebut, semua perubahan pada working directory
	akan disimpan.

================Menambahkan file baru ke repository=============	

1. buka text editor untuk membuat file, dan simpan filenya di direktori aktif(repository)
2. buat file bernama README.md(text file) dengan cara
   echo "# LatihanVCS">> README.md
3. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah 
	git add README.md

===============Menyimpan Perubahan ke Database============
1. Untuk menyimpan perubahan yang ada kedalam database repository
   local, gunakan perintah
    git commit -m “Komentar Perubahan”
	
===============Membuat Repository Server==============
1. Server yang digunakan adalah http://github.com
2. Buat akun github
3. Pada laman github, klik tombol start a project, atau dari menu (icon +) klik New Repository
4. Isi nama repositorynya lalu klik tombol create repository

==============Menambahkan Remote Repository==============

1. Remote Repository merupakan repository server yang akan
   digunakan untuk menyimpan setiap perubahan pada local repository,
   sehingga dapat diakses oleh banyak user. 
2. Untuk menambahkan remote repository server, gunakan perintah
    git remote add origin [url]

==============Mengirim Perubahan Ke Server=============

1. Untuk mengirim perubahan pada local repository ke server gunakan perintah git push dengan cara
    git push -u origin master
2. Perintah ini akan meminta memasukkan username dan password pada akun github.com
3. untuk melihat hasilnya buka laman github.com, arahkan pada repositorinya.

==============Clone Repository==============

1. clone repository, pada dasarnya adalah meng-copy repository server
   dan secara otomatis membuat satu direktory sesuai dengan nama
   repositorynya (working directory).Untuk melakukan cloning, gunakan perintah git clone [url]







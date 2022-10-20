
# CARA PENGGUNAAN GIT
## APA ITU GIT?
*Git adalah salah satu sistem pengontrol versi (Version Control System)
pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.

*Pengontrol versi bertugas mencatat setiap perubahan pada file
proyek yang dikerjakan oleh banyak orang maupun sendiri.

*Git dikenal juga dengan distributed revision control (VCS terdistribusi),
artinya penyimpanan database Git tidak hanya berada dalam satu
tempat saja.

## INSTALASI GIT

• Download Git, buka website resminya Git (git-scm.com).

• Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

• Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan
buka CMD atau PowerShell, kemudian ketik perintah
![gambar 1](screenshot/1.jpg)

## MENAMBAHKAN GLOBAL CONFIG

• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user.name dan user.email

• konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository.

• apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan
saat menjalankan perintah git commit

### Config Global Repository
![gambar 2](screenshot/2.jpg)


## PERINTAH DASAR GIT

• git init, perintah untuk membuat repository local

• git add, perintah untuk menambahkan file baru, atau perubahan pada file
pada staging sebelum proses commit.

• git commit, perintah untuk menyimpan perubahan kedalam database git.

• git push -u origin master, perintah untuk mengirim perubahan pada
repository local menuju server repository.

• git clone [url], perintah untuk membuat working directory yang diambil dari
repositry sever.

• git remote add origin [url], perintah untuk menambahkan remote
server/repository server pada local repositry (working directory)

• git pull, perintah untuk mengambil/mendownload perubahan terbaru dari
server repository ke local repository

## Membuat Reposiory Local

• Buka direktory aktif, misal: d:\labs_pemrograman1 (buka
menggunakan Windows Explorer)

• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,
sehingga muncul git bash commad

• Buat direktory project praktikum pertama dengan nama latihan1
![gambar 3](screenshot/3.jpg)

• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya
masuk kedalam direktori tersebut dengan perintah cd (change
directory)

• direktory aktif menjadi: d:\labs_pemrograman1\latihan1

## Membuat Reposiory Local

• Jalankan perintah git init, untuk membuat repository local.
![gambar 4](screenshot/4.jpg)

• Repository baru berhasil di inisialisasi, dengan terbentuknya satu
direktori hidden dengan nama .git

• Pada direktori tersebut, semua perubahan pada working directory
akan disimpan.

## Menambahkan File baru pada repository

• Untuk membuat file dapat menggunakan text editor, lalu menyimpan
filenya pada direktori aktif (repository)

• disini kita akan coba buat satu file bernama README.md (text file)
![gambar 5](screenshot/5.jpg)

• File README.md berhasil dibuat.
![gambar 6](screenshot/6.jpg)

## Menambahkan File baru pada repository

• Untuk menambahkan file yang baru saja dibuat tersebut gunakan
perintah git add.
![gambar 7](screenshot/7.jpg)

• File README.md berhasil ditambahkan.
![gambar 8](screenshot/8.jpg)

## Commit (Menyimpan perubahan ke database)

• Untuk menyimpan perubahan yang ada kedalam database repository
local, gunakan perintah git commit -m “komentar commit”
![gambar 9](screenshot/9.jpg)


## Membuat repository server

• Server reopsitory yang akan kita gunakan adalah http://github.com
• Anda harus membuat akun terlebih dahulu.

• Pada laman github, klik tombol start a project, atau

• Dari menu (icon +) klik New Repository
![gambar 10](screenshot/10.jpg)
![gambar 11](screenshot/11.jpg)

## Membuat repository server

• Isi nama repositorynya, misal: labpy1.

• lalu klik tombol Create repository
![gambar 12](screenshot/12.jpg)

## Menambahkan Remote Repository

• Remote Repository merupakan repository server yang akan
digunakan untuk menyimpan setiap perubahan pada local repository,
sehingga dapat diakses oleh banyak user.

• Untuk menambahkan remote repository server, gunakan perintah
git remote add origin [url]
![gambar 13](screenshot/13.jpg)

## Push (Mengirim perubahan ke server)

• Untuk mengirim perubahan pada local repository ke server gunakan
perintah git push.
![gambar 14](screenshot/14.jpg)

• Perintah ini akan meminta memasukkan username dan password
pada akun github.com
![gambar 15](screenshot/15.jpg)

## Melihat hasilnya pada server repository

• Buka laman github.com, arahkan pada repositorinya.

• Maka perubahan akan terlihat pada laman tersebut.
![gambar 16](screenshot/16.jpg)

## Clone Repository

• Clone repository, pada dasarnya adalah meng-copy repository server
dan secara otomatis membuat satu direktory sesuai dengan nama
repositorynya (working directory).

• Untuk melakukan cloning, gunakan perintah git clone [url]
![gambar 17](screenshot/17.jpg)

## Kegunaan file README.md

• Apabila kita menggunakan github, untuk memberikan penjelasan
awal pada project yang kita buat, maka dapat menggunakan sebuah
file yang bernama README.md

• Pada file tersebut kita dapat membuat dokumentasi awal dari setiap
project yang kita buat untuk memberikan penjelasan atau sekedar
cara penggunaan dari aplikasi yang kita kembangkan.

• Penulisan file README.md berbasis teks, dan untuk pemformatannya
menggunakan Markdown format.

• untuk lebih jelasnya, dapat anda pelajari cara penggunaan markdown



 ## SEKIAN DAN TERIMA KASIH


[def]: screenshot/1.jpg
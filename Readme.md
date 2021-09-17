## Excercise-Git

ini adalah latihan Git

### Soal 1

Sebutkan step-step dan command line saat menginisasi project untuk menggunakan git hingga sampai push ke github

```
#Inisialisasi Project

git init . #initialisasi existing project
git init skilvul #inisialisasi

git remote add [name-origin] [link-https]

git add . #seluruh file yang mengalami perubahan dikirim kondisi stage
git add index.html #file html yang mengalami perubahan dan dikirimkan ke kondisi stage

git commit -m "[Message]" #Memberikan informasi perubahan untuk developer

git push -u [name-origin] [name-branch] #master/main
```

### Soal 2

Perbedaan Git Reset dan Git Revert

Git Reset mengembalikan file ke versi sebelumnya dan menghapus versi sebelumnya,
Git Revert mengembalikan ke versi sebelumnya tanpa menghapus

*Git Reset harus hati-hati dalam penggunaannya

### Soal 3
Perbedaan Git dan Githu

Git itu merupakan Sistem Versionnya
Github Penyedianya
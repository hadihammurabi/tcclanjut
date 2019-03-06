# Instalasi Git di Ubuntu

Terdapat 2 kondisi untuk melakukan instalasi Git di Ubuntu, yaitu:
1. Paket Git sudah terdaftar di repository APT (package manager)
2. Paket Git belum terdaftar di repository APT

Ada langkah yang berbeda untuk melakukan keduanya.
Berikut ini adalah langkah-langkah yang dapat diikuti.

## 1. Paket Git sudah terdaftar di repository APT
1. Buka terminal emulator
2. Pastikan user yang digunakan memiliki akses **sudo**
3. Jalankan perintah `sudo apt install git`


## 2. Paket Git belum terdaftar di repository APT
Hal ini dapat dilakukan dengan menggunakan PPA. Berikut ini langkah-langkahnya.
1. Buka terminal emulator
2. Pastikan user yang digunakan memiliki akses **sudo**
3. Jalankan perintah berikut `sudo apt install software-properties-common python-software-properties`
4. Jalankan perintah berikut `sudo add-apt-repository ppa:git-core/ppa`
5. Lakukan update dengan menjalankan perintah berikut `sudo apt update`
6. Sampai di sini, Git sudah terdaftar di repository APT. Selanjutnya Anda dapat melakukan langkah yang ada pada [kondisi pertama](#1-paket-git-sudah-terdaftar-di-repository-apt)

### Selamat, sekarang, Git sudah berhasil diinstal

# Membuat dan Mengintegrasikan Pull Request

## Pengertian
Pull Request adalah suatu cara untuk melakukan kolaborasi dalam sebuah proyek.

Hal ini dilakukan dengan langkah sebagai berikut.
1. Masuk ke halaman repository yang dituju.
2. Kemudian klik tombol `fork`.
![Tombol Fork](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/forkbtn.png)
3. Maka tampil dialog untuk memilih dimana akan diletakkan salinan repository tersebut.
![Dialog Fork](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/forkpopup.png)
4. Setelah lokasi dipilih, maka akan terdapat sebuah repository baru yang merupakan salinan dari repository yang di-fork tadi.
![Hasil Fork](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/forkresult.png)
5. Sekarang, repository salinan ini sudah siap untuk dilakukan pengeditan dengan melakukan `clone` dan operasi lainnya.
6. Setelah melakukan perubahan, jangan lupa untuk `commit` dan `push`.
7. Apabila perubahan sudah selesai dan siap untuk digabungkan dengan repository asli, selanjutnya klik tombol `New pull request`.
![Tombol New pull Request](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prbtn.png)
8. Maka akan tampil halaman pengiriman pull request, kemudian pilih repository dan branch mana yang akan dikirim 
![Pemilihan repository dan branch](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prconfig.png)
9. Setelah itu, klik tombol `Create pull request`.
![Tombol Create pull request](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prsendbtn.png)
10. Kemudian akan tampil form untuk mengisi pesan yang akan dikirim bersama dengan pull request.
![Form pesan pull request](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prmsg.png)
11. Setelah pull request berhasil dikirim, maka akan tampil halaman seperti di bawah ini.
![Pull request result](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prresult.png)

Langkah-langkah di atas sudah cukup untuk melakukan kontribusi ke sebuah proyek.
Lalu, sekarang, saatnya menunggu Pull Request tadi diterima dan direspon oleh pemilik proyek tersebut.

Dari sisi pemilik, berikut ini langkah-langkah untuk menerima dan memasukkan hasil perubahan dari sebuah Pull Request.

1. Apabila ada pull request yang masuk, maka nilai pada tab pull request tidak lagi 0 (nol).
![Pull request notification](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prcoming.png)
2. Kemudian klik tab pull request untuk melihat list pull request.
![Pull request list](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prlist.png)
3. Klik salah satu pull request untuk dicek dan dilihat detailnya.
![Pull request merge](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prmerge.png)
4. Klik merge pull request untuk menerima perubahan yang datang.
5. Tambahkan catatan ketika menerima perubahan dari sebuah pull request, lalu klik `confirm merge`.
![Pull request merge confirm](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prmergeconfirm.png)
6. Akan tampil halaman seperti di bawah ini, yang menunjukkan bahwa pull request sudah berhasil di-merge.
![Pull request merge done](https://github.com/hadihammurabi/tcclanjut/raw/master/minggu-02/prdone.png)
 
Pull request sudah berhasil diterima dan digabungkan dengan project utama.

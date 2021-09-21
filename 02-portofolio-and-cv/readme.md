## Hasil Pengerjaan
1. membuat sebuah folder kosong dengan namamu sendiri   -   **mkdir salman**
2. membuat sebuah file dengan nama `README.md`, isi file tersebut dengan kalimat<br>`"Halo perkenalkan aku halaman utama"`   -   **vim README.md, tulis kalimat**
3. insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan `commit` dengan pesan<br>`"Inisialisasi Git Repository"`   -   **git init ., git commit -m "Inisialisasi Git Repository"**
4. buat `branch` baru dengan nama `cv`, hal ini berguna agar histori kita tidak tercampur   -   **git branch cv**
5. pindah `branch` kedalam `cv`, kemudian buat file dengan nama `cv.txt` dan isi file tersebut dengan kalimat:<br>`"Ini adalah file CV"`   -   **git checkout cv, vim cv.txt, tulis kalimat**
6. kemudian dokumentasikan menggunakan `commit` dengan pesan<br>`"Inisialisasi CV"`   -   **git commit -m "Inisialisasi CV"**
7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan `commit`   -   **vim cv.txt, git commit -m "nama perusahaan"**
8. kembali ke `branch master`   -   **git checkout master**
9. ubah file `README.md` menjadi  
    ```
    Halo perkenalkan aku halaman utama

    Ini adalah update pertama pada branch master
    ```
    jangan lupa untuk mendokumentasikannya menggunakan `commit` dengan pesan<br>`"update master pertama"`   -   **vim README.md, git commit -m "update master utama"**
10. gabungkan `branch cv` kedalam `branch master` menggunakan perintah `git merge`   -   **git merge cv**
11. unggah Git Repository tersebut kedalam GitHub   -   **git push origin master**

## Hasil Log
berikut adalah hasil log yang sudah saya kerjakan

![screenshot](https://github.com/salman-setiawan/tugas-git/blob/main/02-portofolio-and-cv/ScreenShot_20210917190153.png)
![screenshot](https://github.com/salman-setiawan/tugas-git/blob/main/02-portofolio-and-cv/ScreenShot_20210917190127.png)

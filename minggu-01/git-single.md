**Modul 1**

**SCM: Git dan GitHub**

**LATIHAN**

1. **Instalasi Git**

Sebelum install Git di Windows, anda harus sudah mempunyai editor teks yang didukung oleh Windws. Editor yang bisa dipilih banyak, tetapi disarankan menggunakan [Notepad++](https://notepad-plus-plus.org/) atau [Visual Studion Code](https://code.visualstudio.com/) atau [Vim](https://www.vim.org/). Keberadaan editor teks ini akan menentukan keberhasilan instalasi (lihat langkah e).

1. Setelah download Git, double click pada file yang di-download. Akan dimunculkan lisensi. Klik **Next** untuk lanjut.

![](images/latihan/001.png)

1. Setelah itu, pilih lokasi instalasi. Secara default akan terisi *C:\Program Files\Git*. Ganti lokasi jika memang anda menginginkan lokasi lain, klik **Next**

![](images/latihan/002.png)

1. Pilih komponen. Tidak perlu diubah-ubah, sesuai dengan default saja. Klik pada **Next**.

![](images/latihan/003.png)

1. Mengisi shortcut untuk menu Start. Gunakan default (Git), ganti jika ingin mengganti - misalnya Git VCS.

![](images/latihan/004.png)

1. Pilih editor yang akan digunakan bersama dengan Git. Pada pilihan ini, digunakan Vim.

![](images/latihan/005.png)

1. Pada saat instalasi, Git menyediakan akses git melalui Bash maupun command prompt. Pilih pilihan kedua supaya bisa menggunakan dari dua antarmuka tersebut. Bash adalah shell di Linux. Dengan menggunakan bash di Windows, pekerjaan di command line Windows bisa dilakukan menggunakan bash - termasuk ekskusi dari Git.

![](images/latihan/006.png)

1. Pilih OpenSSL untuk HTTPS. Git menggunakan https untuk akes ke repo GitHub atau repo-repo lain (GitLab, Assembla).

![](images/latihan/007.png)

1. Pilih pilihan pertama untuk konversi akhir baris (CR-LF).

![](images/latihan/008.png)

1. Pilih PuTTY untuk terminal yang digunakan untuk mengakses Git Bash.

![](images/latihan/009.png)

1. Pilih credentials helper.

![](images/latihan/010.png)

1. Setelah itu proses instalasi akan dilakukan.

![](images/latihan/003.png)

1. Jika selesai akan muncul dialog pemberitahuan. Klik pada **Finish**.

![](images/latihan/011.png)

1. Untuk menjalankan, dari Start menu, ketikkan "Git", akan muncul beberapa pilihan. Pilih "Git Bash" atau "Git GUI".

![](images/latihan/012.png)

1. Tampilan jika akan menggunakan "Git Bash"

![](images/latihan/013.png)

1. Tampilan jika akan menggunakan "Git GUI"

![](images/latihan/014.png)

1. Untuk mencoba dari command prompt, masuk ke command prompt, setelah itu eksekusi "git --version" untuk melihat apakah sudah terinstall atau belum. Jika sudah terinstall dengan benar, makan akan muncul hasil berikut:

![](images/latihan/015.png)

1. **Konfigurasi Git**

Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Linux atau sejanis (UNIX), konfigurasi ini nantinya akan disimpan di **$HOME/.gitconfig**. Untuk sistem operasi Windows, konfigurasi ini akan disimpan di **C:\Document and Settings\NamaUser** dengan nama file **.gitconfig**. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. Gunakan perintah berikut:

![](images/latihan/016.png)

Isian di atas harus disesuaikan dengan nama serta email yang digunakan untuk mendaftar di GitHub. Untuk melihat konfigurasi yang sudah ada:

![](images/latihan/017.png)

Langkah ini cukup dilakukan sekali saja, kecuali jika ingin melakukan perubahan nama dan email.

1. **Mengelola Repo Sendiri di Account Sendiri**

Langkah-langkah

Setiap orang yang telah mempunyai account di GitHub bisa membuat repo dengan. Secara umum, langkah-langkahnya adalah sebagai berikut:

1. Buat repo kosong di GitHub, bisa *public* maupun *private*.
1. Cloe repo kosong tersebut di komputer lokal
1. Perintah berikutnya terkait dengan perubahan repo serta sinkronisasi antara GitHub dengan lokal.

Membuat Repo

Untuk membuat repo, gunakan langkah-langkan berikut:

1. Klik tanda **+** pada bagian atas setelah login, pilih **New repository**

![](images/latihan/018.png)

1. Isikan nama, keterangan, serta lisensi. Jika dikehendaki, bisa membuat repo Private

![](images/latihan/019.png)

Disini saya memberi nama repository tekn-cloud-computing dengan deskripsi cloud computing technology. Saya centang untuk menambahkan README.md.

1. Klik Create Repository

Setelah langkah-langkah tersebut, repo akan dibuat dan bisa diakses menggunakan pola https://github.com/username/reponame. Pada repo tersebut, hanya akan muncul 1 file, yaitu LICENSE. Jika memilih membuat README pada saat langkah ke 2, juga akan muncul README.md. Ada atau tidak ada README.md tidak mempunyai efek apapun pada langkah ini.

![](images/latihan/020.png)

Clone Repo

Proses clone adalah proses untuk menduplikasikan remote repo di GitHub ke komputer lokal. Untuk melakukan proses clone, gunakan perintah berikut:

![](images/latihan/021.png)

Setelah perintah ini, di direktori tekn-cloud-computing akan disimpan isi repo yang sama dengan di GitHub. Perbedaannya, di komputer lokal terdapat direktori .git yang digunakan secara internal oleh Git.

Mengelola Repo

Setelah clone ke komputer lokal, semua manipulasi konten dilakukan di komputer lokal dan hasilnya akan di-*push* ke remote repo di GitHub. Dengan demikian, jangan berganti-ganti remote lokal, sekali dibuat disitu, tetap berada disitu. Jika kehilangan repo lokal, clone ulang ke direktori yang bersih (kosong) setelah itu baru lakukan pengelolaan repo. Beberapa hal yang biasanya dilakukan akan diuraikan berikut ini.

- Mengubah Isi - Push Tanpa Branching dan Merging

Perubahan isi bisa terjadi karena satu atau kombinasi beberapa hal berikut:

1. File dihapus
1. File diedit
1. Membuat file / direktori baru
1. Menghapus direktori

Untuk kasus-kasus tersebut, lakukan perubahan di komputer lokal, setelah itu push ke repo.

![](images/latihan/022.png)

![](images/latihan/023.png)

Cara ini lebih mudah tetapi mempunyai resiko jika terjadi kesalahan dalam edit. Cara yang lebih aman tetapi memerlukan langkah yang lebih panjang adalah branching and merging

- Mengubah Isi dengan Branching and Merging

Dengan menggunakan cara ini, setiap kali akan melakukan perubaham, perubahan itu dilakukan di komputer lokal dengan membuat suatu cabang yang nantinya digunakan untuk menampung perubahan-perubahan tersebut. Setelah itu, cabang itu yang akan dikirim ke repo GitHub untuk dimintai review kemudian digabungkan (merge) ke master. Secara umum, repo yang dibuat biasanya sudah mempunyai satu branch yang disebut dengan master. Cara ini lebih aman, terstruktur, terkendali, dan mempunyai history yang lebih baik. Jika perubahan yang kita buat sudah terlalu kacau dan kita menyesal, maka ada cara untuk "membersihkan" repo lokal kita. Secara umum, langkahnya adalah sebagai berikut:

1. Buat branch untuk menampung perubahan-perubahan
1. Lakukan perubahan-perubahan
1. Add dan commit perubahan-perubahan tersebut ke branch
1. Kembali ke repo master
1. Buat pull request di GitHub
1. Merge pull request di GitHub
1. Merge branch untuk menampung perubahan-perubahan tersebut ke master.
1. Selesai.

![](images/latihan/024.png)

![](images/latihan/025.png)

![](images/latihan/026.png)

Setelah itu, kirim pull request (PR):

![](images/latihan/027.png)

Setelah membuat PR, PR tersebut bisa di-merge

Setelah itu, Confirm Merge, branch yang kita kirimkan tadi sudah dimasukkan ke branch master. Setelah itu, merge di komputer lokal:

![](images/latihan/028.png)

- Sinkronisasi

Suatu saat, bisa saja terjadi kita menggunakan komputer lain dan mengedit repo melalui repo lokal di komputer lain, setelah itu pindah ke kamputer lain lagi. Saat itu, kita perlu melakukan sinkronisasi ke kemputer lokal. Perintah untuk sinkronisasi adalah:

![](images/latihan/029.png)Perintah ini dikerjakan di direktori tempat repo lokal kita berada.

- Membatalkan Perubahan

Praktik yang baik adalah membuat *branch* pada saat kita akan melakukan perubahan-perubahan. Jika perubahan-perubahan yang kita lakukan sudah sedemikian kacaunya, maka kita bisa membuat supaya perubahan-perubahan yang kacau tersebut hilang dan kembali ke kondisi bersih seperti semula.

![](images/latihan/030.png)

- Undo Commit Terakhir

Suatu saat, mungkin kita sudah terlanjur mem-*push* perubahan ke repo GitHub, setelah itu kita baru menyadari bahwa perubahan tersebut salah. Untuk itu, kita bisa melakukan git revert.

![](images/latihan/031.png)




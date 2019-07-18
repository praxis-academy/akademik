# Kemampuan Dasar

## Memahami Ruang Lingkup Pengembangan Software

1. Teknologi informasi dan teknologi software
2. Metodologi Pengembangan Software

### Tujuan

1. Memahami teknologi informasi secara umum dan kaitannya dengan software.
2. Memahami ranah pendidikan yang terkait dengan teknologi informasi: istilah teknik informatika / *informatics*, ilmu komputer / *computer science*.
3. Memahami arti penting dari metodologi pengembangan software
4. Memahami Agile Software Development secara umum
5. Memahami dasar yang kuat dari praktik Agile Software Development: Extreme Programming dan Scrum 

### Pembahasan

1. Teknologi informasi dan teknologi software
2. Metodologi pengembangan software
3. Extreme Programming dan Scrum

### Pembelajaran

```
Materi dan Penjelasan
```

1. Halaman [Wikipedia - Information Technology](https://en.wikipedia.org/wiki/Information_technology), serta komponen-komponen dari TI dengan penekanan lebih pada [software](https://en.wikipedia.org/wiki/Software).
2. Halaman [StackExchange tentang perbedaan informatics dengan computer science](https://cs.stackexchange.com/questions/81408/whats-the-difference-between-computer-science-and-informatics).
3. Halaman [Wikipedia - Software Development](https://en.wikipedia.org/wiki/Software_development) memberikan penjelasan umum tentang aktivitas, model, serta hal-hal lain yang terkait dengan *software development*. Dengan mempelajari bagian ini, siswa diharapkan memahami bahwa *software development* merupakan aktivitas yang kompleks dan memerlukan berbagai macam *roles* / peran.
4. Halaman [Wikipedia - Agile Software Development](https://en.wikipedia.org/wiki/Agile_software_development) membahas hal yang lebih spesifik dari *software development*, yaitu salah satu model / metodologi yang digunakan untuk membangun software.
5. Halaman [Wikipedia - Scrum](https://en.wikipedia.org/wiki/Scrum_(software_development)) membahas tentang salah satu *process framework* yang termasuk dalam metodologi Agile. 
6. Halaman [Wikipedia - XP](https://en.wikipedia.org/wiki/Extreme_programming) membahas tentang salah satu *process framework* yang termasuk dalam metodologi Agile.

## Kemampuan Teknis Dasar 1: Sistem Operasi

1. Sistem Operasi: UI, shell, utilities, shell script

### Tujuan 

1. Memahami software paling mendasar: *operating system*
2. Memahami ekosistem sistem operasi saat ini
3. Memahami komponen-komponen sistem operasi - khususnya berbasis Linux
4. Memahami UI di Linux (*GUI* dan *text mode* / *shell*)
5. Memahami dan bisa menggunakan berbagai utilitas dasar dalam Linux
6. Mehamami dasar-dasar dari *shell script*.

### Pembahasan

1. Cara software bekerja
2. Ekosistem sistem operasi saat ini
3. Komponen-komponen SO dan SO Linux
4. Windowing System di Linux
5. Linux *console* dan terminal
6. Utilitas dasar Linux
7. Shell Script

### Pembelajaran

1. Cara [software](https://en.wikipedia.org/wiki/Software) menempati komputer kita serta bagaimana user berinteraksi dengan *tasks* komputasi. Tekankan pemahaman pada bagaimana [sistem operasi](https://en.wikipedia.org/wiki/Operating_system) bekerja.
2. *Overview* dari [daftar sistem operasi](https://en.wikipedia.org/wiki/List_of_operating_systems) yang ada di dunia ini. 
3. [Komponen-komponen SO Linux](https://en.wikipedia.org/wiki/Linux).
4. [Windowing System](https://en.wikipedia.org/wiki/Windowing_system) yang berfungsi sebagai antarmuka grafis (GUI) di Linux serta impelementasinya di Linux menggunakan [X Window System](https://en.wikipedia.org/wiki/X_Window_System).
5. Keterkaitan X Window System dengan [Display Manager](https://en.wikipedia.org/wiki/X_display_manager_(program_type)), [Window Manager](https://en.wikipedia.org/wiki/Window_manager), serta [Desktop Environment](https://en.wikipedia.org/wiki/Desktop_environment).
6. [Linux console](https://en.wikipedia.org/wiki/Linux_console) dan keterkaitannya dengan [Linux shell](https://en.wikipedia.org/wiki/Shell_(computing)). 
7. Ringkasan dari [berbagai command shell](https://en.wikipedia.org/wiki/Comparison_of_command_shells) terutama yang digunakan di Linux.
8. Beberapa utilitas yang biasanya digunakan pada saat berada di *console* / *shell*. Beberapa utilitas tersebut biasanya berada dalam kelompok [GNU Core Utilities](https://www.gnu.org/software/coreutils/) dan [util-linux](https://en.wikipedia.org/wiki/Util-linux). Beberapa petunjuk lainnya adalah [Guru99](https://www.guru99.com/must-know-linux-commands.html) dan [E-Guide - format PDF](https://cse.yeditepe.edu.tr/~ayildiz/attachments/linux_commands_eguide.pdf).
9. Cara membuat [shell script](https://en.wikipedia.org/wiki/Shell_script).


```
Latihan
```

1. Boot laptop masing-masing, perhatikan proses booting dari awal, jika muncul Grub, usahakan melihat parameter dari Grub tersebut. Cari informasi di Internet tentang parameter Grub tersebut.
2. Cari informasi tentang software yang ada di laptop anda: display manager yang digunakan, window manager yang digunakan, desktop environment yang digunakan, serta shell apa yang digunakan. Dari mana bisa mengetahui informasi tersebut?
3. Cari lokasi dari kernel Linux, sebutkan file-file yang terkait dan kegunaannya.
4. Masuk ke *terminal / comsole* dan kerjakan beberapa perintah berikut melalui *command line / shell*: 
    * buat direktori $HOME/praxis/minggu-01/hari-01
    * silahkan coba beberapa perintah di [Guru99](https://www.guru99.com/must-know-linux-commands.html) dan [E-Guide - PDF](https://cse.yeditepe.edu.tr/~ayildiz/attachments/linux_commands_eguide.pdf).
    * tulis hasil dari masing-masing perintah tersebut ke dalam file `cmdline.txt` (gunakan copy paste dari shell)
5. Silahkan coba [30 contoh shell script](https://linuxhint.com/30_bash_script_examples/), masukkan semua file-file yang dihasilkan di direktori $HOME/praxis/minggu-01/hari-01/30shellscript.

```
Kasus
```

Referensi:
1. [Wikibooks - Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
2. [Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html)
3. [Bash Handbook](https://github.com/denysdovhan/bash-handbook)

Selesaikan kasus-kasus berikut.

0. Semua hasil disimpan pada $HOME/praxis/kemampuan-dasar-1/kasus
1. Buat shell script untuk melihat daftar file pada suatu direktori (termasuk direktori anak-anaknya) dan jika terdapat file dengan ekstensi .java - tampilkan tulisan "Ada file Java pada direktori {nama direktori}". Hasil eksekusi (misalnya):

```bash
$ cari.sh $HOME/src
Ada file Java pada direktori /home/bpdp/src/hari-01
```

2. Buat shell script untuk menanyakan suatu nama program (misalnya `firefox`), setelah itu mencari PID dari program tersebut dan jika PID program tersebut ada, maka program tersebut akan dimatikan. Saran: gunakan perintah-perintah `ps`, `grep`, `awk`, dan `kill`.

## Kemampuan Teknis Dasar 2: Source Code Management - Git dan GitHub

1. Source Code Management: Git dan GitHub

### Tujuan

1. Memahami aktivitas pada metodologi agile serta kaitannya dengan source code management
2. Memahami dan mampu menggunakan Git untuk mengelola *repository*.
3. Memahami dan mampu menggunakan Git untuk mengelola *remote repository* di GitHub.
4. Memahami dan mampu menggunakan Git dan GitHub, baik untuk *single person* maupun *team development*.

### Pembahasan

1. Software engineering, software configuration management, version control, dan distributed version control.
2. Git dan perintah-perintah dasarnya
3. *Markdown* sebagai format untuk dokumentasi
4. Git dan *remote repository* (GitHub, GitLab, Assembla, BitBucket)
5. Git untuk single person development
6. Git untuk tim pengembang aplikasi

### Pembelajaran

```
Materi dan Penjelasan
```

1. Ruang lingkup [software engineering](https://en.wikipedia.org/wiki/Software_engineering).
2. Keterkaitan software engineering dengan [SCM - Software Configuration Management](https://en.wikipedia.org/wiki/Software_configuration_management).
3. Keterkaitan SCM dengan [Version Control](https://en.wikipedia.org/wiki/Version_control) dan [Distributed Version Control](https://en.wikipedia.org/wiki/Distributed_version_control).
4. [Git](https://en.wikipedia.org/wiki/Git) dan keterkaitannya dengan Distributed Version Control
5. [Men-*setup* Git - Chapter 1 - Getting Started](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).
6. [Membuat account GitHub](https://git-scm.com/book/en/v2/GitHub-Account-Setup-and-Configuration) serta [membuat repo di GitHub](https://help.github.com/en/articles/creating-a-new-repository). 
7. [README.md](https://www.quora.com/What-is-README-MD-file-and-why-do-I-need-it) serta [mampu menggunakan pemformatan file markdown untuk menuliskan dokumentasi](https://help.github.com/en/articles/basic-writing-and-formatting-syntax). 
8. Penggunaan `git status`, `git add`, `git commit`, `git push` untuk menyimpan ke *remote repo*
9. Penggunaan [branching and merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging).
10. [Pull request](https://help.github.com/en/articles/about-pull-requests) untuk repo di GitHub milik sendiri, [merging](https://help.github.com/en/articles/merging-a-pull-request), kemudian sinkronisasi ke lokal repo di komputer.
11. [Menggunakan Github untuk kolaborasi tim](https://dev.acquia.com/blog/getting-started-collaborative-development-git).

```
Latihan
```

1. Buat repo sesuai keterangan pada [panduan umum Praxis Academy](https://github.com/praxis-academy/akademik/blob/master/panduan-umum/isi/01.md). Untuk keperluan ini, buat direktori di repo lokal dengan nama `kemampuan-dasar`. Masukkan hasil pekerjaan di direktori `kemampuan-dasar-1` pada materi **Kemampuan Teknis Dasar 1** di atas ke dalam direktori `kemampuan-dasar` sehingga pada repo lokal anda akan terdapat 2 direktori. Setelah itu, push ke *remote repo* di GitHub. Dua direktori yang harus ada pada posisi ini adalah:

```
kemampuan-dasar/
└── kemampuan-dasar-1
```

2. Untuk praktik berikut ini, kerjakan semuanya di dalam direktori `kemampuan-dasar-2` di bawah `kemampuan-dasar`. Cara mengerjakannya adalah dengan mempraktikkan dan kemudian meng-capture / meng-copy hasil dari praktik tersebut ke dalam file markdown. Untuk praktik pertama, beri nama `praktik-1.md`, sedangakan untuk praktik kedua, beri nama `praktik-2.md`. Jika di praktik tersebut diminta untuk membuat repo, buatlah juga di account anda, tidak perlu berada dalam repo praxis-academy. Buat file `README.md` yang berisi nama-nama repo di account GitHub anda yang berhubungan dengan praktik-praktik tersebut. Praktik yang harus dikerjakan adalah: 
    * Praktik 1: [Getting Started ini](https://dev.acquia.com/blog/getting-started-collaborative-development-git) bersama rekan. 
    * Praktik 2: [Team Collaboration with GitHub](https://code.tutsplus.com/articles/team-collaboration-with-github--net-29876) bersama rekan.

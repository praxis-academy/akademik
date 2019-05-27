# Kurikulum dan Proses Pendidikan

## Pendahuluan

Dunia software dan pemrograman merupakan dunia yang luas. Tidak memungkinkan untuk mengajarkan dan memberikan bekal ke siswa tentang semua hal. Oleh karena itu, sekolah ini lebih menekankan pada kekuatan konsep sehingga memudahkan adaptasi siswa ke dunia industri. Konsep yang kuat tidak dilakukan dengan cara memberikan kuliah-kuliah seperti pada perguruan tinggi tetapi melalui latihan dan pembelajaran praktik yang intensif dengan pemahaman ke arah konsep.

## Ketentuan Umum

- Pendidikan dilaksanakan pada hari kerja (senin - jumat), dari jam 09:00 - 16:00.
- Peserta harus membawa laptop sendiri, disarankan memory minimal 8 GB, OS yang didukung hanya Linux (terutama Ubuntu), siswa boleh menggunakan OS apapun, tetapi jika tidak sesuai dengan yang didukung (Ubuntu), tugas siswa sendiri untuk mengelola dan mencari resources serta solusi sendiri terkait OS tersebut (misalnya untuk instalasi software, dan lain-lain).
- Kehadiran sifatnya mutlak. Ketidakhadiran yang ditolerir hanya sebesar 10% dari total hari aktif dalam 2 bulan). Ketidakhadiran akan dihukum dalam bentuk tugas akademik dan harus di-push ke repo. Jika tidak dikerjakan, maka akan dianggap tidak hadir dan akan mempengaruhi kelulusan.
- Waktu untuk beribadah tidak boleh diganggu. Siswa dipersilahkan meninggalkan kelas untuk mengerjakan ibadah. Jam untuk ibadah ini tidak ditulis secara khusus tetapi siswa dipersilahkan melaksanakan sesuai dengan jam masing-masing.

## Materi

Materi pendidikan ada 3 tahap:

- Tahap *novice*: siswa dianggap mempunyai cukup dasar untuk masuk ke proses. Tahap ini berisi pemberian teori, praktik, dan latihan intensif (1 bulan pertama) dengan tujuan untuk membentuk mental dan skill *developer*.
- Tahap *initiator*: siswa dianggap mempunyai kemampuan teknis yang mencukupi dan siap untuk mempunyai inisiatif dalam membuat software tertentu. Tahap ini dilakukan dengan membuat software sesuai dengan skill siswa bagi masing-masing siswa (2 minggu). 
- Tahap *team player*: siswa dianggap mempunyai kemampuan individual yang memadai dan bisa menggunakan kemampuan individual mereka untuk pembuatan software secara berkelompok (2 minggu). Pada tahap ini, siswa juga mulai diminta untuk mulai berkontribusi ke proyek-proyek open source yang ada di GitHub.

### Novice

_Tujuan_

Memberikan dasar teori dan praktik yang kuat terhadap materi

_Aktivitas Harian_

Setiap hari, akan dilakukan pemberian materi serta latihan intensif dengan alokasi waktu sebagai berikut:

- Jam 9 - 10: pemberian materi, penjelasan serta contoh-contoh oleh mentor.
- Jam 10 - 12: latihan materi dari mentor.
- Jam 13 - 16: latihan kasus lebih kompleks.

Setelah selesai, hasil untuk setiap hari di-push ke repo GitHub dengan pola penamaan repo:

``Tahap-Minggu-Hari``

- Tahap: Tahap dari pendidikan.
- Minggu: Minggu saat pengerjaan (2 digit)
- Hari: Hari saat pengerjaan (2 digit)

Contoh:

``novice-02-03``: repo untuk tahap `novice`, minggu ke `2`, hari ke `3 (rabu)`.

Pada repo tersebut, buat `README.md` dengan isi minimal:

- Judul: tentang materi hari tersebut
- Oleh: nama siswa
- Tanggal
- Ringkasan materi
- Penjelasan tentang isi repo
- Lisensi

Pada akhir bulan, 1 hari terakhir di tahap ini digunakan untuk evaluasi metriks penilaian. Ada proses untuk menguji pemahaman dan penguasaan siswa terhadap materi:

- Semua materi GitHub

Mentor melakukan proses pengujian menggunakan mekanisme:

- Ujian teori (tes lisan terkait pemahaman siswa).
- Ujian praktik (tes coding / programming).
- Hasil dari pengujian ini adalah kelanjutan siswa di tahap berikutnya: melanjutkan atau gagal.

Pengujian ini dilaksanakan pada hari Sabtu.

Adapun isi materi akan diuraikan berikut ini.

_Minggu 01_


Hari | Materi
--- | ---
1 | <ul><li>Teknologi Software</li><li>Sistem Operasi: UI, shell, utilities</li></ul>
2 | <ul><li>Git dan GitHub</li><li>Git untuk single user</li><li>Git untuk team</li></ul>
3 | <ul><li>Development tools dan ekosistemnya</li><li>Dasar-dasar Java</li></ul>
4 | <ul><li>Package di Java</li><li>Dynamic typing dan static typing</li><li>Variabel, konstanta, operator, ekspresi, statement, dan tipe data di Java</li><li>Penanganan error / exception</li></ul>
5 | <ul><li>Dasar-dasar Pemrograman Berorientasi Obyek di Java</li><li>Alur kendali program di Java</li><li>Algoritma, pseudocode, dan implementasi algoritma ke Java</li></ul>

_Minggu 02_

Hari | Materi
--- | ---
1 | <ul><li>Annotations</li><li>Object Oriented Programming Lanjut di Java</li></ul>
2 | <ul><li>Generics</li><li>Functional Programming di Java</li></ul>
3 | <ul><li>Unit Testing di Java</li></ul>
4 | <ul><li>Serialisasi data: XML, JSON, dll.</li><li>Struktur data di Java</li></ul>
5 | <ul><li>Concurrent Programming di Java</li></ul>

_Minggu 03_

Hari | Materi
--- | ---
1 | <ul><li>Pustaka standar dan pustaka pihak ketiga di Java</li><li>Proses *build* dan pengelolaan paket pustaka di Java: Gradle</li></ul>
2 | <ul><li>Database management system</li><li>Akses ke database menggunakan Java: JDBC dan ORM</li></ul>
3 | <ul><li>NoSQL dan NewSQL</li></ul>
4 | <ul><li>RESTful endpoint</li><li>GraphQL</li></ul>
5 | <ul><li>Arsitektur Software: microservices dan fullstack application</li><li>Framework: Dasar-dasar Micronaut</li></ul>

_Minggu 04_

Hari | Materi
--- | ---
1 | <ul><li>Berpindah development tools: step-by-step</li><li>Studi kasus perpindahan development tools: dari Java ke peranti pengembangan lainnya (JavaScript, Kotlin, Go, PHP)</li><li>Dasar-dasar JavaScript dan Node.js</li></ul>
2 | <ul><li>JavaScript</li></ul>
3 | <ul><li>Vue.js</li></ul>
4 | <ul><li>Aplikasi Fullstack: Micronaut + Vue.js</li></ul>
5 | <ul><li>Aplikasi Fullstack: Micronaut + Vue.js + Database</li></ul>

### Initiator

_Tujuan_

Siswa membuat software. Hasil akhir dari proses ini adalah software open source yang diletakkan pada repo Git (GitHub) serta deployment dari software tersebut (di Google PlayStore untuk aplikasi Android, di DockerHub untuk image Docker, binary release di Github Releases, dan lain-lain). Software harus direncanakan dengan baik dalam bentuk milestones dan tiket-tiket untuk milestones (dari awal sampai rilis). File README.md diletakkan pada repo untuk menjelaskan tentang isi dari repo. Arsitektur software, milestones, dan dokumentasi tentang software tersebut diletakkan di berbagai file berformat Markdown di direktori docs.

_Minggu pertama_

- Hari 1 dan 2: siswa mencari tema dari proyek software yang akan dibuat.
- Hari 3: siswa mendiskusikan dengan mentor terkait software yang akan dibuat, fitur-fitur, serta milestones untuk menyelesaikan software tersebut. Siswa (dengan bantuan mentor) menyiapkan infrastruktur untuk pembuatan software. 
- Akhir hari 3: dibuat repo dan dalam repo tersebut dibuat README terkait no 2 di atas.
- Hari 4: siswa mulai mengerjakan pembuatan software.

_Minggu 2_

Mengerjakan pembuatan software dan melengkapi dokumentasi. GitHub releases berisi berbagai rilis (versi Beta, RC1, RC2, dan seterusnya sampai dengan rilis).

_Hari Terakhir Minggu 2_

Siswa mempresentasikan pekerjaan pembuatan software ini. Tim akademik dan mentor melakukan penilaian serta pengujian terhadap software yang dibuat tersebut. Hasil penilaian ini menentukan apakah siswa berhasil masuk ke tahap berikutnya atau gagal.

### Tahap Team Player

_Tujuan_

Tahap ini digunakan untuk melatih kemampuan bekerjasama antar siswa. Team ditentukan oleh akademik dan terdiri atas 3-5 siswa. Tim telah dibentuk sebelum memasuki tahap ini. Pada tahap ini, tim membuat software untuk dinilai.

_Minggu 1_

- Hari 1 dan 2: tim melakukan brainstorming untuk menentukan software apa yang akan dibuat.
- Hari 2: pemberian materi tentang software development methodology serta penggunaan GItHub untuk mengelola proyek bersama.
- Hari 3: tim mendiskusikan dengan mentor terkait software yang akan dibuat, fitur-fitur, serta milestones untuk menyelesaikan software tersebut. tim (dengan bantuan mentor) menyiapkan infrastruktur untuk pembuatan software. 
- Akhir hari 3: dibuat repo dan dalam repo tersebut dibuat README terkait no 2 di atas.
- Hari 4: siswa mulai mengerjakan pembuatan software.Hari 3: 

_Hari-hari berikutnya sampai akhir minggu ke 3 dan minggu 4_

- Iterasi pengerjaan proyek
- Siswa mengikuti ritme pengerjaan proyek, termasuk mengalami deadline, pull request ditolak (jika ada), stand up meeting, dan lain-lain.

_Akhir Minggu 4_

- Hari Jumat, bagian akademik serta mentor melakukan evaluasi komprehensif terhadap kemampuan dari siswa dengan melihat hasil GitHub personal maupun tim. Pada hari ini, tim mempresentasikan hasil kerja kelompok.
- Siswa menjalani proses ujian terkait tahap newbie, singledev, dan teamwork.
- Bagian akademik serta para mentor memutuskan siswa yang berhasil lulus dari Praxis Academy serta
  siswa yang tidak berhasil lulus dari Praxis Academy.


# Day-1--Roblox_24-_Kaila-Nisrina-Qurratu-ain
Dokumentasi kegiatan Workshop Day 1 yang berisi rangkuman materi, catatan pembelajaran, dan pengalaman selama workshop
# RANGKUMAN MATERI

### 1. Prompt Engineering

Prompt Engineering adalah teknik merancang instruksi atau perintah kepada AI agar menghasilkan jawaban yang tepat, relevan, dan sesuai dengan kebutuhan pengguna. Prompt merupakan masukan yang diberikan kepada model AI, baik berupa pertanyaan sederhana, kata kunci, instruksi kompleks, maupun potongan kode.

Prompt Engineering memiliki beberapa manfaat, yaitu meningkatkan kualitas hasil AI, mengurangi bias dan respons yang tidak sesuai, meningkatkan kontrol terhadap jawaban AI, serta memberikan pengalaman penggunaan yang lebih baik.

### 2. Pentingnya Context dalam Prompt

Context merupakan informasi atau latar belakang yang diberikan kepada AI agar dapat memahami tujuan dan kebutuhan pengguna. Pemberian konteks yang jelas dapat membantu AI menghasilkan jawaban yang lebih akurat dan sesuai dengan permintaan.

Sebagai contoh, perintah membuat aplikasi akan menghasilkan jawaban yang lebih terarah apabila disertai penjelasan mengenai tujuan aplikasi, target pengguna, fitur yang dibutuhkan, dan teknologi yang digunakan. Oleh karena itu, semakin lengkap konteks yang diberikan, semakin baik pula hasil yang diperoleh.

### 3. Struktur Prompt yang Baik

Dalam membuat prompt, terdapat empat komponen utama yang perlu diperhatikan, yaitu:

- Role: Menentukan peran yang harus dijalankan oleh AI.
- Task: Menjelaskan tugas yang harus dilakukan oleh AI.
- Context: Memberikan informasi dan latar belakang yang diperlukan.
- Format: Menentukan bentuk hasil atau jawaban yang diinginkan.

Keempat komponen tersebut membantu AI memahami instruksi secara lebih terstruktur sehingga hasil yang diberikan sesuai dengan kebutuhan pengguna.

### 4. Pengertian Git

Git adalah Version Control System (VCS) yang digunakan untuk melacak, mencatat, dan mengelola perubahan pada file atau kode program. Git diciptakan oleh Linus Torvalds pada tahun 2005.

Git memungkinkan pengguna mengetahui siapa yang melakukan perubahan, kapan perubahan dilakukan, dan bagian apa saja yang mengalami perubahan. Dengan demikian, pengguna dapat mengelola berbagai versi proyek serta melihat riwayat pengerjaannya.

### 5. Git Workflow

Git Workflow merupakan proses pengelolaan perubahan file dalam sebuah proyek. Terdapat tiga bagian utama dalam Git Workflow, yaitu:

a. Working Directory

Working Directory merupakan tempat pengguna menyimpan, membuka, dan mengedit file proyek. Bagian ini berisi salinan proyek yang sedang dikerjakan dan dapat mengalami perubahan.

b. Staging Area

Staging Area merupakan tempat untuk menyiapkan perubahan file yang akan disimpan ke dalam commit berikutnya. Bagian ini digunakan untuk menentukan perubahan mana saja yang akan dimasukkan ke repository.

c. Git Directory

Git Directory merupakan tempat Git menyimpan metadata dan object database proyek. Bagian ini menyimpan informasi penting yang dibutuhkan Git untuk mengelola proyek, termasuk riwayat perubahan.

### 6. Perbedaan Git dan GitHub

Git dan GitHub merupakan dua hal yang saling berkaitan, tetapi memiliki fungsi berbeda. Git adalah sistem version control yang digunakan untuk melacak dan mengelola perubahan kode secara lokal. Sementara itu, GitHub adalah platform berbasis web yang digunakan untuk menyimpan repository Git secara online serta mendukung kolaborasi antar pengguna.

Dengan menggunakan Git dan GitHub, pengguna dapat mengelola perkembangan proyek, menyimpan kode secara daring, dan bekerja sama dengan orang lain.

### 7. Perintah Dasar Git

Git memiliki beberapa perintah dasar yang digunakan untuk mengelola repository dan perubahan proyek.

Perintah `git init` digunakan untuk membuat atau menginisialisasi repository Git baru. Perintah `git add .` digunakan untuk memasukkan perubahan file ke staging area. Selanjutnya, `git commit -m "message"` digunakan untuk menyimpan perubahan ke repository dengan memberikan pesan atau keterangan mengenai perubahan tersebut.

Selain itu, terdapat perintah `git remote add origin URL` untuk menghubungkan repository lokal dengan repository GitHub. Perintah `git push origin main` digunakan untuk mengirim perubahan dari komputer ke GitHub, sedangkan `git pull origin main` digunakan untuk mengambil dan menggabungkan perubahan dari GitHub ke repository lokal.

Perintah `git clone URL` digunakan untuk menyalin repository yang tersedia di GitHub ke komputer lokal.

### 8. Git Setup

Sebelum menggunakan Git, pengguna perlu melakukan instalasi Git terlebih dahulu. Instalasi dapat dilakukan dengan mengunduh versi Git yang sesuai dengan perangkat melalui situs resminya.

Setelah instalasi selesai, pengguna dapat membuka Terminal atau Command Prompt untuk memeriksa apakah Git sudah terpasang dengan menggunakan perintah `git --version`.

Selanjutnya, pengguna perlu mengatur identitas Git berupa nama dan alamat email. Pengaturan tersebut dilakukan menggunakan perintah `git config --global user.name` dan `git config --global user.email`.

Untuk melihat konfigurasi yang telah dibuat, pengguna dapat menjalankan perintah `git config --global --list`.

### 9. Visual Studio Code Setup

Visual Studio Code atau VS Code merupakan aplikasi editor kode yang digunakan untuk membuat dan mengembangkan program. Sebelum digunakan, pengguna perlu menginstal VS Code pada perangkat.

Setelah instalasi, pengguna dapat membuka VS Code dan menekan kombinasi tombol Ctrl + Shift + P pada Windows untuk mencari perintah Shell Command: Install 'code' command in PATH. Setelah itu, pengguna dapat membuka terminal dan menjalankan `code --version` untuk memastikan VS Code sudah dapat diakses melalui terminal.

### 10. Menambahkan Repository ke Git

Terdapat dua cara untuk menambahkan proyek ke Git.

Cara pertama adalah menggunakan perintah `git init` pada folder proyek yang ingin dikelola. Perintah tersebut akan menginisialisasi folder menjadi repository Git lokal.

Cara kedua adalah melalui GitHub. Pengguna dapat membuka GitHub, membuat repository baru, kemudian memilih tombol Code untuk menyalin URL repository. Setelah URL diperoleh, pengguna dapat membuka terminal dan menjalankan perintah `git clone URL` untuk menyalin repository tersebut ke komputer lokal.

### 11. Working Area ke Staging Area

Untuk memasukkan perubahan file ke staging area, Git menyediakan beberapa perintah, yaitu `git add --all`, `git add -A`, `git add .`, dan `git add *`.

Perintah `git add --all` dan `git add -A` digunakan untuk memasukkan seluruh perubahan file ke staging area, termasuk file baru, file yang dimodifikasi, dan file yang dihapus.

Perintah `git add .` digunakan untuk memasukkan perubahan file dalam direktori proyek beserta direktori di dalamnya. Sementara itu, `git add *` digunakan untuk memasukkan file baru dan file yang dimodifikasi, tetapi tidak memasukkan file yang telah dihapus.

### 12. Generate New SSH Key

SSH Key merupakan metode autentikasi yang digunakan untuk menghubungkan komputer dengan GitHub secara aman. Dalam materi ini, algoritma yang digunakan adalah Ed25519.

Ed25519 merupakan algoritma tanda tangan digital berbasis kurva eliptik yang dirancang untuk memberikan keamanan dan performa tinggi.

Pembuatan SSH Key dilakukan menggunakan perintah `ssh-keygen -t ed25519 -C "email@domain.com"`. Setelah menjalankan perintah tersebut, pengguna dapat menentukan lokasi penyimpanan dan mengatur passphrase untuk melindungi kunci yang dibuat.

### 13. Menghubungkan SSH Key ke GitHub

Setelah SSH Key berhasil dibuat, langkah selanjutnya adalah menghubungkannya dengan GitHub.

Proses ini diawali dengan menjalankan SSH Agent menggunakan perintah `eval "$(ssh-agent -s)"`. Selanjutnya, pengguna membuat file konfigurasi SSH menggunakan `touch ~/.ssh/config` dan menambahkan konfigurasi host GitHub.

Setelah konfigurasi selesai, SSH Key ditambahkan ke SSH Agent. Public Key kemudian disalin dan dimasukkan melalui pengaturan SSH and GPG Keys pada akun GitHub dengan memilih menu New SSH Key.

Setelah berhasil ditambahkan, koneksi dapat diperiksa menggunakan perintah `ssh -T git@github.com`. Jika berhasil, terminal akan menampilkan pesan bahwa autentikasi telah berhasil dilakukan.

### 14. Memeriksa Setup Git dan GitHub

Setelah proses instalasi dan konfigurasi selesai, pengguna perlu melakukan pemeriksaan untuk memastikan semua komponen sudah berjalan dengan baik.

Pemeriksaan Git dilakukan menggunakan `git --version`. Identitas pengguna dapat diperiksa melalui `git config --global user.name` dan `git config --global user.email`. Selanjutnya, VS Code dapat diperiksa menggunakan `code --version`, sedangkan koneksi GitHub diperiksa dengan `ssh -T git@github.com`.

Pemeriksaan ini bertujuan memastikan Git, VS Code, identitas pengguna, dan koneksi GitHub telah dikonfigurasi dengan benar.

### 15. Praktik Membuat Student Task Planner

Pada akhir workshop, peserta diarahkan untuk membuat aplikasi sederhana bernama Student Task Planner. Aplikasi ini bertujuan membantu mahasiswa mengatur daftar tugas dan tenggat waktu pengerjaan.

Proses pembuatannya dimulai dengan menginstal platform AI-assisted seperti ChatGPT, Claude, atau Antigravity. Setelah itu, pengguna membuat prompt untuk meminta AI menghasilkan aplikasi sesuai kebutuhan.

Proyek yang telah dibuat kemudian dimasukkan ke Git menggunakan perintah `git init`. Selanjutnya, perubahan disimpan menggunakan commit dan dikirim ke GitHub melalui push.

Apabila terdapat perubahan atau pengembangan pada aplikasi, pengguna perlu melakukan commit dan push kembali agar versi terbaru proyek tersimpan di GitHub.

Dengan memahami kedua materi tersebut, pengguna dapat memanfaatkan AI untuk membantu membuat aplikasi, kemudian menggunakan Git dan GitHub untuk menyimpan, memperbarui, serta mendokumentasikan perkembangan proyek secara terstruktur.

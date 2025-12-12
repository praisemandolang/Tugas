# Judul Program
Snake Game

# Pendahuluan
Snake Game adalah permainan klasik ular (Snake Game) yang dibuat menggunakan bahasa pemrograman Python dan modul turtle.
Game ini dirancang untuk memberikan pengalaman bermain yang sederhana namun menarik, di mana pemain mengendalikan seekor ular untuk mengumpulkan makanan. Setiap makanan yang dimakan akan menambah skor pemain serta menambah panjang tubuh ular.
Proyek ini dikembangkan sebagai bagian dari Tugas Proyek Kelompok – Version Control System, dengan tujuan melatih kolaborasi menggunakan Git & GitHub, termasuk pengelolaan branch, commit, dan penyelesaian merge conflict.

# Fitur Utama
- Antarmuka berbasis Turtle Graphics
- Makanan muncul secara acak dengan warna dan bentuk berbeda
- Pertumbuhan ular setiap kali makan
- Sistem skor dan high score
- Deteksi tabrakan dengan dinding dan tubuh sendiri
- Pergerakan ular menggunakan tombol panah (keyboard)
- Layar Game Over ketika pemain kalah

# Panduan Instalasi
1. Clone Repository
Pastikan perangkat sudah terpasang Git.
git clone <https://github.com/praisemandolang/Tugas>
2. Masuk ke direktori proyek
cd REPO-NAME
3. Instalasi Library (Jika diperlukan)
Library turtle sudah tersedia secara default pada Python, sehingga:
 Tidak perlu instalasi tambahan
 Tidak diperlukan pip install

# Panduan Menjalankan Program
Jalankan program menggunakan terminal/command prompt:
python projekkelompok.py
File projekkelompok.py harus berada di folder yang sama dengan repository yang kamu clone.

# Dokumentasi Teknis
![GAMBAR FLOWCHART](<Flowchart.drawio.png>)

Flowchart di atas menggambarkan alur kerja program Snake Game mulai dari inisialisasi hingga permainan berakhir. Program dimulai dengan menyiapkan variabel, membuat window game, border, kepala ular, makanan, dan scoreboard. Setelah itu, tombol kontrol diaktifkan dan game masuk ke loop utama. Di dalam loop, program terus memeriksa apakah ular menabrak dinding, memakan makanan, atau menabrak tubuhnya sendiri. Jika ular memakan makanan, skor bertambah dan segmen baru ditambahkan. Jika terjadi tabrakan dengan dinding atau tubuh, permainan dihentikan dan pesan Game Over ditampilkan. Proses ini berlangsung terus hingga kondisi game over terpenuhi.

# Contributor
Nama|NIM|Link Akun Github
:---|:---|:---
Joy Naysha Lourdess Pua|250211060120|<https://github.com/Joy-pua>
Praise Honesty Mandolang|250211060123|<https://github.com/praisemandolang>
Junior Palilingan Jacobis|250211060129|<https://github.com/juniorjac496-max/jun>

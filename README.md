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
git clone https://github.com/USERNAME/REPO-NAME.git
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
Flowchart Sistem
       ┌────────────────────┐
       │      Mulai Game     │
       └───────────┬────────┘
                   │
        ┌──────────▼──────────┐
        │ Inisialisasi layar   │
        │ + ular + makanan     │
        └──────────┬──────────┘
                   │
        ┌──────────▼──────────┐
        │ Input arah ular      │
        └──────────┬──────────┘
                   │
     ┌─────────────▼─────────────┐
     │ Update posisi + tampilan   │
     └──────────┬──────────┬──────┘
                │          │
      ┌─────────▼───┐   ┌──▼───────────┐
      │ Makan?       │   │ Tabrakan?    │
      └───────┬──────┘   └─────┬────────┘
              │                │
   ┌──────────▼──────┐   ┌─────▼─────────┐
   │ Tambah skor +    │   │   Game Over   │
   │ tambah segmen    │   └─────┬─────────┘
   └──────────┬───────┘         │
              │                 │
              └───────► Kembali ke loop

Penjelasan Teknis
- Program menggunakan modul turtle untuk membuat tampilan serta objek ular dan makanan.
- Input direction dikendalikan dengan event keyboard (wn.onkeypress()).
- Program berjalan dalam loop utama, melakukan:
    - Update posisi ular
    - Deteksi tumbukan
    - Deteksi makanan
    - Pembaruan skor
- Jika ular menabrak dinding atau tubuhnya sendiri, permainan berhenti dan layar Game Over ditampilkan.

# Daftar Kontributor
Nama Lengkap	NIM	Link Akun GitHub	Peran dalam Dokumentasi
Joy Naysha Lourdess Pua  250211060120  https://github.com/Joy-pua
	Contributors
Praise Honesty Mandolang  250211060123  https://github.com/praisemandolang
	Project Maintainer
Junior Palilingan Jacobis  250211060129  https://github.com/juniorjac496-max/jun
	Contributors

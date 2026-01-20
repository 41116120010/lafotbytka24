# Laporan Formatter by TKA24 ⚡

> **"Capek begadang cuma buat benerin margin 4-3-3-3? Chill, Biar script satu ini yang kerjain."**

**Laporan Formatter by TKA24 (lafotbytka24)**. Tools produktivitas berbasis desktop native Linux (Ubuntu/Debian) yang dirancang khusus buat mahasiswa Politeknik/Vokasi yang pengen idupnya tenang pas nyusun Laporan Praktikum atau Tugas Akhir. No more drama formatting berantakan, no more "margin kiri kurang geser dikit".

Sekali klik, format **DOCX** atau **ODT** lo langsung jadi, rapi, valid, dan siap kumpul. *Less effort, maximum result.*

---

## Fitur Utama

* **Format Kampus Ready:** Margin (4-3-3-3), Font Times New Roman, Spasi 1.5, dan Indentasi Paragraf otomatis tersetting dari template.
* **Dynamic Chapter Injection:** Mau nambah Sub-Bab (1.1) atau Sub-Sub-Bab (1.1.1)? Tinggal klik, gak perlu pusing mikirin style heading.
* **Smart Suggestions:** Males ngetik "Latar Belakang"? Ada dropdown saran otomatis per Bab.
* **Linux Native:** Installer `.deb` yang solid. Install sekali, pake offline selamanya.
* **Hybrid Output:** Support export ke `.docx` (Word) dan `.odt` (LibreOffice).

---

## 📦 Cara Install (Debian/Ubuntu/Mint)
Gak perlu compile manual, gue udah siapin paket `.deb`-nya. Buka terminal lo (`Ctrl+Alt+T`) dan ikuti langkah sat-set ini:

### 1. Download Installer
Download file `lafotbytka24_1.0_amd64.deb` dari menu [Releases](#) di kanan repo ini.

### 2. Install via Terminal
Masuk ke folder download, lalu jalankan perintah ini:
sudo dpkg -i lafotbytka24_1.0_amd64.deb

Jika ada error dependency (jarang terjadi), fix dengan:
sudo apt install -f

### 3. Fix Permission (Wajib!)
Agar aplikasi bisa menulis file output dengan lancar di folder sistem, jalankan "mantra" ini sekali saja setelah install:
sudo chmod -R 755 /opt/lafotbytka24

### Cara Pakai
Buka menu aplikasi (Super Key), ketik "Laporan Formatter by TKA24".
Dashboard: Klik "Buat Laporan".
Wizard Step:
Tab Cover: Isi data diri (Nama, NIM, Matkul, dll).
Tab Bab I - V: Gunakan tombol "+ Tambah Sub-Bab" untuk mengisi konten. Gunakan Smart Suggestions untuk mempercepat penulisan judul.
Placeholder: Gunakan opsi "Placeholder Gambar/Tabel" untuk menandai area yang akan diisi visual nanti.
Finalisasi: Pilih format output (DOCX/ODT), lalu klik Generate Laporan.

### Dimana File Hasilnya?
Secara default, aplikasi akan menyimpan file hasil_laporan.docx (atau .odt) di lokasi instalasi karena berjalan sebagai native app.
Cek file hasil generate di folder ini:
/opt/lafotbytka24/
atau di
/home/

### Tech Stack
Dibuat dengan cinta dan kopi hitam menggunakan:
Python 3.10+ (The Brain)
Flet (The Beauty / UI Framework)
Python-Docx (The Engine)
PyInstaller (The Freezer)

### License
Project ini open source. Bebas lo pake, modif, atau jadiin bahan belajar. Copyright © 2026 - Mahasiswa D3 Tekom A PNP.
Made with ❤️ in Padang, ID.

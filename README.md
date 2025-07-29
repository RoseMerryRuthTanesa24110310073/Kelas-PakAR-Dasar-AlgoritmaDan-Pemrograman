# Kelas-PakAR-Dasar-AlgoritmaDan-Pemrograman
UAS ROSE MERRY RUTH TANESA 2411030073 Kumpulan tugas Python untuk mata kuliah Dasar Algoritma dan Pemrograman - Bisnis Digital
3. User Manual (Panduan Pengguna)
▶️ Panduan Menjalankan Aplikasi
Buka Google Colab dan jalankan seluruh sel dari atas ke bawah.

Setelah dijalankan, program akan menampilkan menu interaktif (pilihan 1 sampai 8).

Masukkan angka sesuai fitur yang ingin kamu jalankan (contoh: 1 untuk tambah barang).
# 📦 Aplikasi Inventori Barang (Python)

Aplikasi ini dibuat menggunakan bahasa pemrograman Python di Google Colab, dengan tujuan untuk membantu pencatatan dan pengelolaan data inventori barang sederhana.

## 🔧 Fitur Utama
1. Menambahkan barang
2. Menampilkan daftar barang
3. Mengedit data barang
4. Menghapus data barang
5. Mencari barang berdasarkan nama
6. Mengekspor data ke file CSV
7. Menampilkan laporan ringkas
8. Keluar dari aplikasi

## 🧩 Struktur Program
- `data_barang`: List kosong untuk menyimpan data barang
- Fungsi-fungsi utama:
  - `tampilkan_menu()`: Menampilkan menu utama
  - `tambah_barang()`: Menambah data barang
  - `tampilkan_barang()`: Menampilkan seluruh barang
  - `edit_barang()`: Mengedit data berdasarkan indeks
  - `hapus_barang()`: Menghapus barang berdasarkan indeks
  - `cari_barang()`: Mencari barang berdasarkan nama
  - `ekspor_ke_file()`: Menyimpan data ke file CSV
  - `laporan_ringkas()`: Menampilkan total jenis barang, stok, dan nilai inventori
  - `keluar()`: Mengakhiri program

## 📚 Library yang Digunakan
- `csv`: Untuk mengekspor data ke file CSV

## 🔄 Diagram Alur Aplikasi
Pengguna ➜ Pilih Menu ➜ Proses (Tambah/Edit/Hapus/Cari) ➜ Output ditampilkan ➜ Kembali ke Menu

---

## 🧑‍💻 User Manual

### ▶️ Cara Menjalankan
1. Jalankan kode di Google Colab sel.
2. Akan muncul menu pilihan angka 1-8.
3. Masukkan angka sesuai fitur yang ingin digunakan.

### ✍️ Contoh Input
- Nama barang: `Matcha Latte`
- Stok: `30`
- Harga: `25000`
- Setelah diinput, data akan tersimpan dan bisa dicek melalui menu Tampilkan Barang (pilihan 2).

### 🛠 Cara Edit & Hapus
- Pilih menu 3 untuk mengedit, pilih nomor barang lalu isi data baru.
  Masukkan data baru untuk nama, stok, dan harga


- Pilih menu 4 untuk hapus, pilih nomor barang yang ingin dihapus.

---

## 🧪 Pengujian & Evaluasi

Tentu bisa, Rose! Ini aku buatin **bagian README.md – Pengujian & Evaluasi (Nomor 4)** berdasarkan skenario nyata dari semua fitur 1–8 yang kamu jalankan. Bisa langsung kamu copy ke file `README.md` GitHub kamu:

---

## 🧪 4. Pengujian & Evaluasi

Berikut adalah hasil pengujian dari fitur-fitur dalam aplikasi inventori:

### ✅ Skenario 1: Tambah Barang (Menu 1)

* **Input:**

  * Nama: Beef Burger
  * Stok: 15
  * Harga: 37000
* **Hasil:**

  * Barang *Beef Burger* berhasil ditambahkan dan masuk dalam daftar inventori.

---

### ✅ Skenario 2: Tampilkan Daftar Barang (Menu 2)

* **Hasil:**

  * Menampilkan daftar barang yang telah ditambahkan:

    ```
    1. Beef Burger | Stok: 15 | Harga: Rp37000
    ```

---

### ✅ Skenario 3: Edit Barang (Menu 3)

* **Input:**

  * Edit barang nomor 1 (Beef Burger)
  * Nama baru: Beef Burger Triple Chesee
  * Stok baru: 35
  * Harga baru: 50000
* **Hasil:**

  * Data barang berhasil diubah menjadi:

    ```
    1. Beef Burger Triple Chesee | Stok: 35 | Harga: Rp50000
    ```

---

### ✅ Skenario 4: Hapus Barang (Menu 4)

* **Input:**

  * Hapus barang nomor 
* **Hasil:**

  * Barang *Beef Burger Triple Chesee* berhasil dihapus dari daftar.

---

### ✅ Skenario 5: Cari Barang (Menu 5)

* **Input:**

  * Cari kata kunci: "Beef Burger Triple Chesee"
* **Hasil:**

  * Barang tidak ditemukan (karena sudah dihapus sebelumnya).
  * Jika masih ada, hasil pencarian akan menampilkan barang yang cocok.

---

### ✅ Skenario 6: Ekspor ke CSV (Menu 6)

* **Hasil:**

  * Data barang berhasil diekspor ke file `data_inventory.csv` yang bisa dibuka di Excel atau Google Sheets.

---

### ✅ Skenario 7: Laporan Ringkas (Menu 7)

* **Hasil:**

  * Aplikasi menampilkan total jenis barang, total stok, dan total nilai inventori. Contoh:

    ```
    Total Jenis Barang: 0
    Total Stok Barang: 0
    Total Nilai Inventory: Rp0
    ```

---

### ✅ Skenario 8: Keluar Aplikasi (Menu 8)

* **Hasil:**

  * Program menampilkan pesan:

    ```
    Terima kasih telah menggunakan Aplikasi Inventori. Sampai jumpa!
    ```
  * Lalu aplikasi berhenti.

## ✅ Status
✅ Aplikasi berjalan lancar di Google Colab dan bisa digunakan secara offline untuk kebutuhan inventori sederhana.


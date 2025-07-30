# 📦 Inventaris Café – Aplikasi Sederhana Python

**Nama**: Sofia Merlina Yusuf  
**NIM**: 24110310082  
**Prodi**: Bisnis Digital 2B

---

## 📁 Struktur File

Program hanya terdiri dari **1 file utama**, yaitu:

- `inventori.py`: Berisi seluruh fungsi dan logika aplikasi

File data disimpan otomatis di file `menu_kopi.json` agar data tidak hilang saat aplikasi ditutup.

---

## 🧠 Fungsi-fungsi Utama

Berikut daftar fungsi utama dalam aplikasi:

- `tambah_menu()` – Menambahkan data menu baru (kode, nama, stok, harga)
- `lihat_menu()` – Menampilkan semua data menu kopi
- `edit_menu()` – Mengedit stok dan harga menu kopi berdasarkan kode
- `hapus_menu()` – Menghapus menu dari daftar berdasarkan kode
- `laporan_stok()` – Menampilkan stok dari jumlah terbanyak ke terkecil
- `ringkasan_menu()` – Menampilkan jumlah jenis dan total nilai persediaan
- `cari_menu()` – Mencari kopi berdasarkan kode
- `save_data()` & `load_data()` – Menyimpan dan memuat data dari/ke file JSON

---

## 🧰 Library yang Digunakan

- `json` → Untuk menyimpan & membaca data dari file `.json`
- `time` → Untuk mengukur waktu proses tampilan data & laporan

---

## 🚀 Cara Menjalankan Aplikasi

1. Pastikan Python sudah terinstal di komputer.
2. Simpan file kode sebagai `inventori.py`.
3. Jalankan program di terminal:

```bash
python inventori.py
```

4. Data akan otomatis disimpan dalam file `menu_kopi.json`.

---

## 🧪 Contoh Penggunaan / Output

```text
=== Menu Inventaris Café ===
1. Tambah Menu Kopi
2. Lihat Semua Menu
3. Edit Stok & Harga
4. Hapus Menu
5. Laporan Stok
6. Ringkasan Menu
7. Cari Menu Kopi
8. Simpan & Keluar
Pilih menu (1-8): 1

Kode menu: 003
Nama kopi: V60
Stok cup: 20
Harga per cup: 23000
Menu ditambahkan.

=== Menu Inventaris Café ===
Pilih menu (1-8): 1

Kode menu: 004
Nama kopi: Coffee Latte
Stok cup: 50
Harga per cup: 18000
Menu ditambahkan.

=== Menu Inventaris Café ===
Pilih menu (1-8): 3

Masukkan kode menu yang ingin diedit: 003
Stok baru: 18
Harga baru: 20000
Data menu diperbarui.

=== Menu Inventaris Café ===
Pilih menu (1-8): 4

Masukkan kode menu yang ingin dihapus: 003
Menu dihapus.

=== Menu Inventaris Café ===
Pilih menu (1-8): 5

Laporan stok kopi (dari terbanyak):
Americano - Stok: 50 cup, Harga: Rp15000
Coffee Latte - Stok: 50 cup, Harga: Rp18000
Cappucino - Stok: 35 cup, Harga: Rp18000
Waktu proses laporan: 0.000030 detik

=== Menu Inventaris Café ===
Pilih menu (1-8): 6

Total jenis kopi: 3
Total nilai persediaan: Rp2280000

=== Menu Inventaris Café ===
Pilih menu (1-8): 7

Masukkan kode menu: 8
Menu tidak ditemukan.

=== Menu Inventaris Café ===
Pilih menu (1-8): 7

Masukkan kode menu: 004
Ditemukan: 004 - Coffee Latte (Stok: 50 cup, Harga: Rp18000)

=== Menu Inventaris Café ===
Pilih menu (1-8): 8

Data disimpan. Keluar.
```

---

## ✅ Status Pengujian

| Skenario                    | Status  |
|----------------------------|---------|
| Tambah Menu                | ✅ Berhasil |
| Lihat Semua Menu           | ✅ Berhasil |
| Edit & Hapus Menu          | ✅ Berhasil |
| Laporan Stok               | ✅ Berhasil |
| Ringkasan Menu             | ✅ Berhasil |
| Cari Menu                  | ✅ Berhasil |
| Simpan & Keluar Aplikasi   | ✅ Berhasil |

---

## 📌 Catatan Tambahan

- Program ini cocok untuk keperluan dasar manajemen stok di Café kecil/UMKM.
- Bisa dikembangkan lebih lanjut dengan fitur login, laporan PDF, atau GUI.

---


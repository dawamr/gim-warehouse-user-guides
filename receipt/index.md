# 📥 Receipt Guide

Panduan menerima barang masuk dengan scan barcode.

---

## 📝 Di Halaman Ini
- [Langkah Penerimaan](#-langkah-penerimaan-barang)
- [Mengelola Daftar](#-mengelola-daftar-item)
- [Tips & Do/Don't](#-tips--dodont)
- [Troubleshooting](#️-troubleshooting)

---

## ✅ Prasyarat

| Kebutuhan | Status |
|-----------|--------|
| 🔐 Login ke aplikasi | Wajib |
| 📷 Kamera berfungsi | Wajib |
| 🌐 Koneksi internet stabil | Wajib |
| 📱 Izin kamera aktif | Wajib |

---

## 📥 Langkah Penerimaan Barang

### Step 1: Buka Modul Receipt

| Aksi | Hasil |
|------|-------|
| 👆 Ketuk **Receipt** di Beranda | Masuk ke halaman Receipt |
| 👀 Lihat daftar | Kosong jika belum ada scan |

📸 **Halaman awal:**

![Halaman kosong](./images/Penerimaan%20-%20Blank.png)

### Step 2: Scan Barcode

| Aksi | Hasil |
|------|-------|
| 👆 Ketuk tombol **Scan** (📷) | Kamera terbuka |
| 🎯 Arahkan ke barcode | Jarak 10-15 cm |
| ✅ Barcode terbaca | Item masuk ke daftar |

📸 **Mode scan:**

![Mode scan](./images/Penerimaan%20-%20Scan.png)

### Step 3: Scan Item Lainnya

| Situasi | Hasil |
|---------|-------|
| Item **berbeda** | Tampil sebagai baris baru |
| Item **sama** | Kuantitas bertambah otomatis |

📸 **Multi produk:**

![Multi produk](./images/Penerimaan%20-%20Input%20Multi%20Product.png)

📸 **Produk sejenis:**

![Produk sejenis](./images/Penerimaan%20-%20Input%20Sejenis.png)

### Step 4: Simpan Batch

| Aksi | Hasil |
|------|-------|
| 👀 Periksa daftar | Pastikan semua item benar |
| 👆 Ketuk **Simpan** | Data dikirim ke server |
| ✅ Snackbar hijau | Berhasil tersimpan |

---

## 🗑️ Mengelola Daftar Item

| Aksi | Cara | Kapan Dipakai |
|------|------|---------------|
| 🗑️ **Hapus 1 item** | Geser item ke kiri | Salah scan 1 item |
| 🔄 **Reset semua** | Ketuk tombol Reset | Mulai ulang dari awal |
| ✏️ **Edit qty** | Ketuk item (jika tersedia) | Koreksi jumlah |

> ⚠️ Reset akan menghapus **semua** item. Konfirmasi akan muncul sebelum eksekusi.

---

## 💡 Tips & Do/Don't

### ✅ Do (Lakukan)

| Tips | Alasan |
|------|--------|
| 💡 Scan di area terang | Barcode lebih cepat terbaca |
| 🧹 Bersihkan lensa | Lensa kotor = scan gagal |
| 🌐 Cek koneksi sebelum simpan | Hindari gagal simpan |
| 👀 Periksa daftar sebelum Save | Hindari duplikasi |

### ❌ Don't (Hindari)

| Hindari | Risiko |
|---------|--------|
| ❌ Tutup app saat simpan | Data tidak tersimpan |
| ❌ Simpan daftar kosong | Error / tidak ada yang disimpan |
| ❌ Abaikan snackbar | Tidak tahu berhasil/gagal |

---

## ⚠️ Troubleshooting

| Masalah | Solusi |
|---------|--------|
| 📷 Barcode tidak terbaca | Atur jarak 10-15 cm, tambah cahaya |
| ❓ Item tidak ditemukan | Pastikan barcode valid, laporkan jika yakin benar |
| 🔄 Duplikasi tidak diinginkan | Hapus item atau Reset, scan ulang |
| ❌ Gagal simpan | Cek internet, coba lagi |

> 🆘 Masih bermasalah? Ambil screenshot & laporkan via [🆘 Support](../support.md)

---

## ➡️ Navigasi

| Arah | Halaman |
|------|------|
| ⬅️ Sebelumnya | [🔐 Auth Guide](../auth/) — Login ke aplikasi |
| ➡️ Selanjutnya | [📍 Placement Guide](../placement/) — Tempatkan barang di rak |
| 🏠 Beranda | [👋 User Guides](../index.md) |

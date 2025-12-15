# 🧠 Core Concepts

Pahami istilah-istilah penting ini sebelum menggunakan GIM Warehouse V2.

---

## 📦 Packing List & Pallet

| Istilah | Penjelasan | Contoh |
|---------|------------|--------|
| **Packing List** | Daftar pengiriman berisi beberapa pallet | PL-2024-001 |
| **Pallet** | Unit fisik berisi item untuk dicek/dikirim | Pallet A1, A2, A3 |
| **ETD** | Estimated Time of Departure (jadwal kirim) | 15 Des 2024 |

> 📖 Dipakai di: [🚚 Shipping Check](./shipping-check/)

---

## 🏷️ Barcode

| Istilah | Penjelasan |
|---------|------------|
| **Barcode** | Kode unik pada item/pallet untuk dipindai |
| **SKU** | Stock Keeping Unit – kode produk internal |
| **Scan** | Proses membaca barcode dengan kamera |

> 📖 Dipakai di: [📥 Receipt](./receipt/), [🚚 Shipping Check](./shipping-check/), [📊 Stock](./stock/)

---

## 📥 Receipt (Penerimaan)

| Istilah | Penjelasan |
|---------|------------|
| **Receipt** | Proses terima & catat barang masuk |
| **Batch** | Kumpulan item yang discan dalam satu sesi |
| **Validasi** | Pengecekan otomatis apakah barcode valid |

> 📖 Panduan lengkap: [📥 Receipt Guide](./receipt/)

---

## 📍 Placement (Penempatan)

| Istilah | Penjelasan |
|---------|------------|
| **Placement** | Proses tempatkan barang di lokasi rak |
| **Lokasi** | Kode rak/area penyimpanan barang |
| **Filter** | Saring data berdasarkan tanggal/produk |

> 📖 Panduan lengkap: [📍 Placement Guide](./placement/)

---

## 📊 Stock (Stok)

| Istilah | Penjelasan |
|---------|------------|
| **Stock** | Data ketersediaan barang |
| **Quantity** | Jumlah barang tersedia |
| **Search** | Cari barang berdasarkan nama/SKU/barcode |

> 📖 Panduan lengkap: [📊 Stock Guide](./stock/)

---

## 🚚 Shipping Check (Verifikasi Kirim)

| Istilah | Penjelasan |
|---------|------------|
| **Shipping Check** | Verifikasi barang sebelum dikirim |
| **Checklist** | Daftar item yang perlu diverifikasi |
| **Progress** | Persentase item sudah dicek (0-100%) |

> 📖 Panduan lengkap: [🚚 Shipping Check Guide](./shipping-check/)

---

## 📦 BDP (Barang Dalam Proses)

| Istilah | Penjelasan |
|---------|------------|
| **BDP** | Barang yang sedang diproses, belum final |
| **Status** | Kondisi terkini barang (dalam proses/selesai) |

> 📖 Panduan lengkap: [📦 BDP Guide](./bdp/)

---

## 🔄 Status & Indikator

| Status | Tampilan | Arti |
|--------|----------|------|
| ⏳ **Loading** | Spinner berputar | Sedang memuat data |
| ✅ **Success** | Snackbar hijau | Aksi berhasil |
| ❌ **Error** | Snackbar merah | Aksi gagal |
| 🟢 **Complete** | Progress 100% | Semua item sudah dicek |
| 🟡 **In Progress** | Progress 1-99% | Sebagian sudah dicek |
| ⚪ **Not Started** | Progress 0% | Belum mulai |

---

## ➡️ Lanjutkan

| Langkah | Halaman |
|---------|------|
| Mulai terima barang | [📥 Receipt Guide](./receipt/) |
| Tempatkan barang | [📍 Placement Guide](./placement/) |
| ⬅️ Sebelumnya | [🧭 Navigation & Layout](./navigation-layout.md) |
| 🏠 Kembali ke daftar isi | [👋 User Guides](./index.md) |

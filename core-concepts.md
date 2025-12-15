# 🧠 Core Concepts

Istilah penting yang sering muncul di GIM Warehouse V2.

## 📦 Packing List & Pallet
- **Packing List**: daftar pengiriman berisi beberapa pallet.
- **Pallet**: unit fisik berisi item yang akan dicek atau dikirim.

## 🏷️ Barcode
- Kode unik pada item/pallet untuk dipindai.
- Dipakai di Receipt (masuk) dan Shipping Check (keluar).

## 📍 Placement
- Proses menempatkan barang yang baru diterima ke lokasi rak.
- Mempengaruhi visibilitas stok dan kemudahan picking.

## 📥 Receipt
- Proses penerimaan barang masuk dengan scan dan validasi.
- Menghasilkan data stok awal sebelum ditempatkan.

## 🚚 Shipping Check
- Verifikasi barang yang akan dikirim: cek per pallet, tandai progres.
- Bisa reset item/all jika perlu koreksi.

## 📊 Stock
- Data ketersediaan barang (nama/SKU/barcode/lokasi).
- Dapat dicari dan difilter.

## 📦 BDP (Barang Dalam Proses)
- Barang yang sedang diproses dan belum final; terkait receipt/placement.

## 🔄 Status & Progres
- Status memuat/menyimpan/error ditampilkan via indikator dan snackbar.
- Progres pallet (Shipping) dan daftar scan (Receipt) diperbarui otomatis.

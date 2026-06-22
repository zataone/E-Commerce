# 🛒 E-Commerce Platform Terintegrasi (C2C / B2C)

Platform toko online modern berskala besar yang mampu menangani ratusan produk dengan pengalaman pengguna yang mulus, mengadopsi arsitektur terpusat mirip seperti Tokopedia atau Shopee versi spesifik (Niche Market).

---

## 📌 Overview

Aplikasi ini dirancang untuk memberikan performa maksimal baik dari sisi pembeli maupun penjual. Dengan menggabungkan teknologi modern, platform ini memastikan proses memuat halaman berjalan instan, manajemen keranjang belanja yang responsif, serta transaksi yang aman melalui integrasi *payment gateway*.

---

## ✨ Fitur Utama

### 🛍️ Pengalaman Belanja Modern
* **Sistem Keranjang Belanja Avanos:** Manajemen *state* yang sinkron dan responsif untuk menangani penambahan, pengurangan, dan kalkulasi produk secara *real-time*.
* **Filter Produk Dinamis Berbasis URL:** Memudahkan pengguna membagikan (*share link*) hasil pencarian dan filter spesifik (kategori, harga, rating) secara akurat.
* **Halaman Ulasan & Rating:** Sistem *feedback* interaktif dari pembeli untuk meningkatkan *social proof* produk.

### 💳 Transaksi & Keamanan
* **Integrasi Payment Gateway:** Proses pembayaran otomatis, aman, dan mendukung berbagai metode pembayaran (E-Wallet, Virtual Account, Transfer Bank).

---

## 🧠 Keunggulan Sistem & Arsitektur

### ⚡ Performa Instan dengan Next.js ISR
Platform ini memanfaatkan fitur **Incremental Static Regeneration (ISR)** dari Next.js untuk mencapai performa optimal:
* **Mundur Instan (Instant Load):** Halaman detail produk dimuat secara instan karena disajikan sebagai halaman statis (HTML pra-cetak).
* **Data Selalu Aktual:** Stok barang dan perubahan harga tetap diperbarui di latar belakang (*background*) secara berkala tanpa perlu melakukan *rebuild* total seluruh aplikasi.

---

## 🛠️ Tech Stack (Rekomendasi)

| Komponen | Teknologi |
| :--- | :--- |
| **Frontend Framework** | Next.js (App Router / Pages Router) |
| **Language** | TypeScript |
| **State Management** | Zustand / Redux Toolkit / React Context |
| **Styling** | Tailwind CSS / Shadcn UI |
| **Payment Gateway** | Midtrans / Xendit / Stripe |
| **Database & ORM** | PostgreSQL & Prisma |

---

## 🚀 Memulai (Getting Started)

### 1. Clone Repositori
```bash
git clone [https://github.com/username/ecommerce-platform.git](https://github.com/username/ecommerce-platform.git)
cd ecommerce-platform

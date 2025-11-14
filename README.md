# 💳 Simulasi Alat Pembayaran QRIS (Quick Response Code Indonesian Standard)

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Flask Version](https://img.shields.io/badge/Flask-2.x-lightgray)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/Status-POC_Completed-important)](https://github.com/your-username/your-repo-name)

## 🎯 Tujuan Proyek

Proyek ini dikembangkan untuk memberikan pemahaman teknis dan praktis mengenai dua fase kritis dalam alur transaksi **QRIS Merchant Presented Mode (MPM) Dinamis** dari perspektif **Merchant Backend**:

1.  **Generasi Kode QR:** Bagaimana data transaksi (Nominal, ID Invoice, ID Merchant) di-*encode* menjadi QR Code sesuai spesifikasi PJP.
2.  **Verifikasi Callback (Server-to-Server):** Menyediakan *endpoint* aman yang berfungsi sebagai "telinga" Merchant untuk mendengarkan dan memproses notifikasi pembayaran yang dikirim oleh sistem Bank/PJP (Penyedia Jasa Pembayaran).

Aplikasi ini menggunakan data statis dan simulasi API untuk memfokuskan pada **logika integrasi** tanpa melibatkan pemrosesan keuangan aktual.

***

## 🛠️ Teknologi yang Digunakan

| Teknologi | Peran | Versi |
| :--- | :--- | :--- |
| **Python** | Bahasa pemrograman utama. | 3.8+ |
| **Flask** | *Web framework* ringan untuk membuat antarmuka kasir dan *endpoint* API. | 2.x |
| **`qrcode` & `Pillow`** | Library untuk menghasilkan gambar QR Code dari *string* data transaksi. | Terbaru |
| **Base64** | Digunakan untuk menampilkan gambar QR Code secara *inline* di HTML. | Standar |

***

## 🚀 Instalasi dan Menjalankan Proyek

### 1. Prasyarat

Pastikan Anda memiliki: Python 3.8 atau versi yang lebih baru, `git`, dan `pip`.

### 2. Klon Repositori

```bash
git clone [https://www.andarepository.com/](https://www.andarepository.com/)
cd [Nama Repositori Anda]

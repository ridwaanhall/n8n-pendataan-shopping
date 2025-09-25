# 🧾 n8n Pendataan Shopping

Bot pencatatan keuangan pribadi berbasis **n8n** dan **AI**, dirancang untuk memudahkan pengguna mencatat pengeluaran secara otomatis tanpa perlu coding rumit. Cocok untuk pemula, kreator, dan siapa pun yang ingin mengelola keuangan dengan cara yang efisien dan modern.

## 🚀 Fitur Utama

- 📸 **Upload Struk Belanja**  
  Bot membaca teks dari gambar menggunakan OCR (Gemini AI) dan mencatat detailnya ke Google Sheets.

- 💬 **Input via Telegram**  
  Kirim pengeluaran langsung lewat chat Telegram, praktis dan cepat.

- 📊 **Laporan Otomatis**  
  Dapatkan ringkasan pengeluaran harian, mingguan, dan bulanan langsung dari Google Sheets.

## 🛠️ Teknologi yang Digunakan

| Tool            | Fungsi Utama                                      |
|-----------------|---------------------------------------------------|
| `n8n`           | Workflow automation tanpa kode                    |
| `Gemini AI`     | Optical Character Recognition (OCR) dari gambar   |
| `Telegram Bot`  | Antarmuka input pengeluaran                       |
| `Google Sheets` | Penyimpanan dan laporan data pengeluaran          |

## 📚 Apa yang Akan Kamu Pelajari

- Pengenalan n8n sebagai platform otomasi visual
- Cara membuat workflow pencatatan pengeluaran
- Integrasi Gemini AI untuk membaca teks dari gambar
- Menyimpan data ke Google Sheets secara otomatis
- Membuat laporan keuangan berkala
- Tips optimasi bot agar lebih responsif dan modular

## 📦 Instalasi & Setup

1. Clone repositori ini:
   ```bash
   git clone https://github.com/ridwaanhall/n8n-pendataan-shopping.git
   ```

2. Setup n8n di lokal atau VPS (lihat [dokumentasi resmi](https://docs.n8n.io))

3. Konfigurasi:
   - API Gemini AI
   - Bot Telegram (Token & Chat ID)
   - Google Sheets (API credentials & Sheet ID)

4. Import workflow `.json` ke n8n dan sesuaikan node sesuai kebutuhan.

## 🧠 Kontribusi

Proyek ini terbuka untuk kontribusi! Jika kamu punya ide untuk fitur baru, optimasi workflow, atau integrasi tambahan (misalnya WhatsApp, Notion, atau Firebase), silakan buat pull request atau buka issue.

## 📄 Lisensi

MIT License. Bebas digunakan dan dimodifikasi untuk keperluan pribadi maupun komersial.

---

> Dibuat dengan semangat otomasi dan edukasi oleh [ridwaanhall](https://github.com/ridwaanhall) — mendukung komunitas developer Indonesia untuk membangun solusi cerdas dan berdampak.

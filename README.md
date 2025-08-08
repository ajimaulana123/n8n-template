# 📦 Kumpulan Template n8n 

Selamat datang di repositori ini! 👋  
Di sini kamu akan menemukan berbagai **template n8n** yang saya buat sendiri untuk mengotomatisasi berbagai alur kerja (workflow automation).

## 🔧 Tentang n8n

[n8n](https://n8n.io) adalah platform *workflow automation* open-source yang fleksibel, mendukung ratusan integrasi, dan bisa dikostumisasi sesuai kebutuhan. Dengan n8n, kamu bisa menghubungkan berbagai aplikasi, API, dan sistem tanpa perlu coding yang kompleks.

## 📂 Isi Repositori

Repositori ini berisi kumpulan template dalam format `.json` yang bisa langsung kamu **import ke n8n**. Setiap folder atau file biasanya mewakili satu use case atau automasi spesifik.

## 🧪 Contoh Use Case

- 🔁 **Auto-post artikel ke WordPress + Notif Telegram**  
  Otomatisasi publikasi artikel ke WordPress disertai notifikasi ke Telegram.
- 🤖 **Chatbot Telegram dengan AI Assistant (Gemini/OpenAI)**  
  Bot Telegram pintar yang dibekali AI untuk menjawab pertanyaan pengguna.
- 🔄 **Sinkronisasi data dari Google Sheet ke sistem lain**  
  Ambil dan olah data dari GSheet lalu kirim ke platform atau API eksternal.
- 📩 **Buat sistem customer support dari Gmail ke WhatsApp**  
  Email masuk ditangani dan diteruskan sebagai pesan WhatsApp otomatis.
- 📲 **Bot WhatsApp yang bisa menjawab sebagai customer**  
  Bot yang mensimulasikan perilaku customer, cocok untuk testing flow percakapan.
- 🧠 **Integrasi RAG + Chatbot untuk pertanyaan spesifik**  
  Gunakan teknik Retrieval-Augmented Generation untuk menjawab berdasarkan dokumen internal.
- 🗂️ **Upload file sederhana via backend API di n8n**  
  Endpoint upload file dengan logika backend simpel dalam satu workflow.

## 📥 Cara Menggunakan

1. Buka platform n8n kamu (cloud atau self-hosted).
2. Klik **Import Workflow** di dashboard.
3. Pilih file `.json` dari repositori ini.
4. Sesuaikan kredensial (credential) dan parameter sesuai kebutuhanmu.

> ⚠️ **Catatan:**  
> Beberapa template memerlukan konfigurasi kredensial tambahan (Google, Telegram, WordPress, dsb). Pastikan kredensial sudah disiapkan terlebih dahulu sebelum menjalankan workflow.

## 📌 Catatan Tambahan

- Template ini diuji di platform `n8n self-hosted` dan `n8n cloud`.  
  Ada kemungkinan perbedaan konfigurasi node tergantung dari platform yang digunakan.
- Gunakan template ini sebagai **dasar eksplorasi dan pengembangan**, feel free untuk modifikasi sesuai use case kamu.

## 🧑‍💻 Kontribusi & Feedback

Punya ide automasi baru atau ingin kolaborasi bareng?  
Boleh banget buka **issue** atau kirim **pull request**!

# SmaCoFit (Smart Coach Fitness)

SmaCoFit adalah sebuah aplikasi revolusioner pengganti *Personal Trainer* (PT) konvensional. 

Berawal dari masalah umum di mana menyewa jasa *Personal Trainer* sangat mahal dan sering kali jadwal latihannya bertabrakan antara klien dan pelatih, SmaCoFit hadir sebagai solusi **paket komplit** berteknologi AI.

Aplikasi ini ditenagai sepenuhnya oleh **LLM (Large Language Model)** dan algoritma **Computer Vision** canggih untuk memberikan pengalaman *personal training* yang eksklusif, fleksibel, dan terjangkau langsung dari genggaman Anda.

## 🌟 Fitur Utama

- **Penyusunan Jadwal Pelatihan Cerdas:** Jadwal *workout* pengguna akan diatur dan dipersonalisasi sepenuhnya oleh LLM berdasarkan tujuan, postur, dan rutinitas harian.
- **Analisis Exercise Real-Time:** Menggunakan kamera *smartphone*, AI dapat mendeteksi dan mengevaluasi kualitas form gerakan olahraga pengguna (seperti Plank, Squat, Push-up, dan Sit-up) secara *real-time* dan memberikan *feedback* perbaikan form.
- **Analisis Konsumsi Nutrisi:** Pemantauan dan evaluasi asupan makanan harian pengguna yang diawasi langsung oleh LLM untuk memastikan kalori dan makronutrisi sesuai dengan *goal* fisik pengguna.
- **Konsultasi Langsung dengan LLM:** Tidak perlu menunggu jadwal PT! Pengguna bisa berkonsultasi 24/7. Informasi, progres, dan keluhan pengguna akan dikirim langsung ke LLM, sehingga LLM selalu memiliki konteks menyeluruh layaknya pelatih pribadi Anda sendiri.

## 📂 Struktur Proyek

Proyek ini terdiri dari beberapa repositori/folder utama:

- **`/mobile-app`**: Aplikasi *mobile* (dibangun dengan Flutter) yang digunakan langsung oleh klien. Di dalamnya terdapat modul pendeteksi pose cerdas (*Pose Detection*) yang terintegrasi dengan Google ML Kit untuk mengevaluasi gerakan *workout* secara instan.
- **`/web-app`**: Layanan *backend* dan analitik untuk memproses data pengguna, menyimpan riwayat, dan berkomunikasi dengan API LLM.
- **`/web-admin-landing-page-app`**: *Dashboard* berbasis web untuk admin serta *landing page* promosi SmaCoFit.

## 🧪 Pengujian Performa AI (Google Colab)
Untuk mengecek, memvalidasi, dan mensimulasikan performa algoritma Pose Detection kami (seperti perhitungan akurasi, sudut sendi, *FPS tracking*, dll) di luar environment mobile, Anda dapat mengakses script Python (MediaPipe) kami di tautan berikut:
👉 **[Google Colab: SmaCoFit Pose Evaluation Engine](https://colab.research.google.com/drive/1wzyK7lfBmUAOZXMjRK5qLYARXUh28UA_?usp=sharing)**

---
*Dibuat untuk memberikan solusi kebugaran yang cerdas, hemat, dan dapat diakses siapa saja, kapan saja.*

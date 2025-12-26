# 🚀 GeminiRange: Valorant-Style Aim Trainer

**GeminiRange** adalah aplikasi latihan menembak (aim trainer) berbasis web yang ringan dan responsif. Proyek ini dibangun menggunakan **Three.js** melalui kolaborasi kreatif antara manusia dan **Gemini AI** untuk menciptakan simulasi latihan yang mendekati sensasi *tactical shooter* seperti Valorant.

---

## 🎯 Fitur Utama

* **Clean & Focused UI:** Desain antarmuka minimalis bertema Valorant untuk fokus maksimal.
* **Dynamic Difficulty:** 3 tingkat kesulitan (Easy, Medium, Hard) yang mengatur kecepatan *spawn* dan durasi target.
* **Custom Session Time:** Pilih durasi latihan Anda sendiri (10 detik, 30 detik, atau 60 detik).
* **Realistic Feedback:** * Suara tembakan Vandal.
    * Suara "Headshot Ding" saat target terkena.
    * Countdown suara khusus sebelum sesi dimulai.
    * Feedback visual target berubah warna saat tertembak.
* **Sensitivity Control:** Pengaturan sensitivitas yang presisi untuk menyesuaikan kenyamanan mouse Anda.
* **Performance Optimized:** Menggunakan Three.js Grid System yang stabil dan tidak membuat pusing/mual.

---

## 🛠️ Tech Stack

* **Engine:** [Three.js](https://threejs.org/) (3D WebGL Library)
* **Language:** JavaScript (ES6+), HTML5, CSS3
* **Assets:** GLTF/GLB Loader & Web Audio API
* **AI Partner:** Google Gemini

---

## 🚀 Cara Menjalankan Secara Lokal

1.  **Clone Repositori**
    ```bash
    git clone [https://github.com/username-kamu/gemini-aim-trainer.git](https://github.com/username-kamu/gemini-aim-trainer.git)
    ```
2.  **Masuk ke Folder**
    ```bash
    cd gemini-aim-trainer
    ```
3.  **Siapkan Aset Suara**
    Pastikan file berikut ada di dalam folder proyek:
    * `button1.mp3` (Suara tembakan)
    * `button2.mp3` (Suara klik menu)
    * `button3.mp3` (Suara countdown)
    
4.  **Jalankan dengan Live Server**
    Buka file `index.html` menggunakan ekstensi **Live Server** di VS Code atau cukup buka file langsung di browser modern.

---

## 🎮 Cara Bermain

1.  Buka aplikasi di browser.
2.  Atur **Sensitivity** sesuai keinginan.
3.  Pilih **Difficulty** dan **Duration**.
4.  Klik **"Enter Range"**.
5.  Tunggu hitungan mundur **3, 2, 1... GO!**
6.  Arahkan *crosshair* dan tembak target kuning sebanyak mungkin!

---

## 🤝 Kontribusi

Proyek ini dikembangkan sebagai eksperimen kolaborasi AI. Jika Anda ingin menambahkan fitur seperti *Leaderboard*, berbagai jenis senjata, atau statistik yang lebih detail, silakan lakukan *Pull Request* atau buka *Issue*.

---

## 📝 Lisensi

Proyek ini berada di bawah lisensi MIT. Silakan gunakan dan modifikasi sesuka Anda!

---
*Dibuat dengan ❤️ oleh Rizkya Gusnaldy & Gemini AI.*

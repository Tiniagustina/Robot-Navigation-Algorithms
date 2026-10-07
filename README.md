# 🤖 2D Grid-based A* (A-Star) Path Planning for Mobile Robots

Repositori ini berisi implementasi algoritma **A* (A-Star)** berbasis grid 2D untuk pencarian jalur terpendek (*path planning*) pada robot pemindah atau *Autonomous Mobile Robot* (AMR). Program ini dilengkapi dengan visualisasi pencarian secara *real-time* dan mempertimbangkan jari-jari fisik robot (*robot radius*) untuk menghindari tabrakan dengan rintangan.

---

## 📸 Demo Visualisasi
*(Tambahkan tangkapan layar atau GIF saat program grafik Matplotlib berjalan di sini)*

---

## 🌟 Fitur Utama
* **8-Directional Motion Model:** Robot dapat bergerak ke 8 arah (horizontal, vertikal, dan diagonal dengan penyesuaian bobot jarak $\sqrt{2}$).
* **Obstacle Inflation (Safety Margin):** Memperhitungkan `robot_radius` agar jalur yang dihasilkan tidak terlalu dekat dengan dinding rintangan.
* **Euclidean Heuristic:** Menggunakan fungsi estimasi jarak Euclidean untuk mengoptimalkan pencarian titik tujuan (*goal*).
* **Real-time Visualization:** Visualisasi animasi interaktif menggunakan `matplotlib` untuk menampilkan proses eksplorasi node hingga terbentuknya rute final (garis merah).

---

## 🛠️ Teknologi & Library
* **Bahasa Pemrograman:** Python 3.x
* **Library Utama:**
  * `matplotlib` - Untuk visualisasi grafik dan animasi jalur.
  * `math` - Untuk kalkulasi jarak Euclidean dan fungsi trigonometri.

---

## 🚀 Cara Menjalankan

1. **Clone Repositori Ini:**
   ```bash
   git clone [https://github.com/Tiniagustina/Robotics-Motion-Planning.git](https://github.com/Tiniagustina/Robotics-Motion-Planning.git)
   cd Robotics-Motion-Planning

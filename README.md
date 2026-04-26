📌 README - Queue Visualizer (Simple)

📖 Deskripsi

Program ini merupakan aplikasi visualisasi struktur data **Queue (Antrian)** yang dibuat menggunakan library **Tkinter** di Python. Aplikasi ini menampilkan beberapa simulasi kasus nyata yang berkaitan dengan konsep antrian dan struktur data lainnya secara visual dan interaktif.

## 🎯 Tujuan

* Memahami konsep **Queue (FIFO)** secara visual
* Mengenal variasi implementasi antrian dalam berbagai kasus
* Mempermudah pembelajaran algoritma seperti **BFS** dan **Priority Queue**

🧩 Fitur Utama

Program ini memiliki 5 jenis simulasi:

 1. 🖨️ Printer Queue

* Simulasi antrian printer (FIFO)
* Data masuk ke antrian dan diproses satu per satu
* Menampilkan jumlah antrian dan jumlah yang sudah diproses


 2. 🔥 Hot Potato (Game)

* Simulasi permainan dengan konsep circular queue
* Pemain akan dieliminasi secara acak
* Menampilkan jumlah pemain tersisa


3. 🏥 Rumah Sakit (Priority Queue)

* Antrian berdasarkan prioritas (darurat lebih dulu)
* Warna menunjukkan tingkat prioritas:

  * Merah = sangat darurat
  * Oranye = darurat
  * Kuning = sedang
  * Hijau = rendah


 4. 🌐 BFS (Breadth-First Search)

* Visualisasi traversal graf menggunakan BFS
* Node yang sudah dikunjungi akan berubah warna
* Menggunakan struktur queue untuk penelusuran


5. ✈️ Bandara (Multi Queue + Server)

* Simulasi antrian penumpang di bandara
* Terdapat 2 loket pelayanan
* Penumpang diproses secara paralel


🛠️ Teknologi yang Digunakan

* Python 3
* Tkinter (GUI)
* collections.deque (Queue)
* random (simulasi acak)
* math (perhitungan posisi)


▶️ Cara Menjalankan Program

1. Pastikan Python sudah terinstall
2. Jalankan file dengan perintah:

```bash
python kasus\ 1.py
```

3. GUI akan muncul


🎮 Cara Menggunakan

* Pilih mode simulasi (printer, hot, rs, bfs, bandara)
* Gunakan tombol:

  * **Enqueue** → menambahkan data
  * **Dequeue** → menghapus data (khusus printer)
  * **Start** → menjalankan simulasi
  * **Stop** → menghentikan simulasi
  * **Reset** → mengulang dari awal


📊 Tampilan Output

* Visualisasi berbasis canvas (grafis)
* Animasi berjalan otomatis saat **Start**
* Statistik ditampilkan di bagian bawah


⚠️ Catatan

* Program menggunakan animasi berbasis waktu (`after 400 ms`)
* Beberapa proses menggunakan random sehingga hasil bisa berbeda setiap dijalankan


👨‍💻 Author

Dibuat untuk keperluan pembelajaran struktur data (Queue & turunannya)# strukdat6

# Materi kuliah jejaring sosial

Repositori ini berisi materi kuliah Jejaring Sosial untuk Program Studi Teknik Informatika, Universitas Stikubank (UNISBANK) Semarang, mencakup pengantar konsep, elemen jaringan, kumpulan tautan referensi, serta notebook Jupyter berbasis Python dan NetworkX untuk analisis serta visualisasi jaringan sosial.

---

## Tujuan pembelajaran

- **Dasar teori:** Konsep jaringan sosial, elemen jaringan, dan model generatif (ER, Watts–Strogatz, Barabási–Albert).
- **Analisis kuantitatif:** Centrality, komunitas, dan metrik jaringan menggunakan Python/NetworkX.
- **Visualisasi:** Teknik visualisasi jaringan untuk eksplorasi dan komunikasi temuan.
- **Praktik reproducible:** Notebook Colab untuk eksekusi cepat tanpa setup lokal.

---

## Struktur repositori

- **Pendahuluan:** Ringkasan materi dan konteks kuliah pada UNISBANK Semarang.
- **Elemen Jaringan:** Konsep node, edge, degree, path, dan metrik dasar.
- **Kumpulan URL:** Tautan referensi pendukung.
- **Notebook Jupyter:** Implementasi dan analisis dengan Python/NetworkX, siap dijalankan di Google Colab.

---

## Daftar notebook

| Notebook | Topik | Ringkas |
|---|---|---|
| js_Analisis_Menggunakan_NetworkX.ipynb | Analisis jaringan | Penggunaan NetworkX untuk metrik dan struktur dasar |
| js_visualisasi_jaringan.ipynb | Visualisasi | Teknik visualisasi graf untuk eksplorasi jaringan |
| js_Implementasi_Python_Murni_Model_ER.ipynb | Model ER | Simulasi graf acak Erdős–Rényi tanpa pustaka tingkat tinggi |
| js_Implementasi_Python_Murni_Model_Watts–Strogatz.ipynb | Model WS | Small-world networks dan properti clustering |
| js_Model_Barabási–Albert_(BA)_Tanpa_NetworkX.ipynb | Model BA | Preferential attachment dan distribusi derajat |
| js_🐍_Analisis_Centrality_dengan_Python_(NetworkX).ipynb | Centrality | Degree, betweenness, closeness, eigenvector centrality |
| js_🐍_Implementasi_Komparatif_Deteksi_Komunitas.ipynb | Komunitas | Perbandingan algoritma deteksi komunitas |
| js_🐬_Analisis_Centrality_pada_Dataset_Jaringan_Sosial_Lumba_lumba.ipynb | Studi kasus | Centrality pada dataset “dolphins” |

> Sources: 

---

## Cara penggunaan

1. **Buka di Colab:** Klik notebook yang diinginkan, lalu pilih “Open in Colab” (atau unduh dan jalankan di lingkungan lokal). Sebagian notebook ditandai “Dibuat menggunakan Colab,” sehingga kompatibel langsung dengan eksekusi cloud.
2. **Eksekusi sel berurutan:** Jalankan dari atas ke bawah untuk memuat dependensi, menghasilkan graf, dan menampilkan visualisasi.
3. **Eksperimen parameter:** Ubah ukuran jaringan, probabilitas koneksi (ER), rewiring (WS), atau jumlah node baru per langkah (BA) untuk melihat dampaknya pada metrik dan struktur.

---

## Prasyarat

- **Python 3.x** dan **Jupyter** (jika menjalankan lokal).
- **NetworkX** dan pustaka plotting (mis. Matplotlib).
- **Google Colab** untuk eksekusi tanpa instalasi, sesuai penyiapan notebook di repositori.

---

## Kontribusi

- **Isu dan pull request:** Silakan ajukan perbaikan, penambahan contoh, atau pembaruan referensi melalui Issues/PR di GitHub.
- **Standar gaya:** Jaga konsistensi penamaan notebook dan dokumentasi singkat di bagian atas setiap notebook.
- **Data & etika:** Pastikan dataset yang digunakan memiliki lisensi yang sesuai dan anonim jika memuat data sensitif.

---

## Lisensi

Belum ada rilis atau paket yang dipublikasikan. Jika Anda berencana menggunakan materi ini untuk tujuan lain, mohon cantumkan atribusi yang memadai dan periksa izin yang relevan pada masing-masing file.

---

## Kredit

- **Pengelola repositori:** hyulianton.
- **Institusi:** Program Studi Teknik Informatika, Universitas Stikubank (UNISBANK) Semarang.
- **Bahasa:** Jupyter Notebook sebagai bahasa utama konten teknis dalam repositori.

Jika ada konteks tambahan yang ingin Anda tonjolkan (misalnya silabus per minggu, rubrik penilaian, atau tugas proyek), beri tahu saya, dan saya akan menyesuaikan README ini agar lebih pas dengan kebutuhan kelas Anda.

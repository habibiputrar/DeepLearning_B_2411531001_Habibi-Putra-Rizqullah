# Praktikum Deep Learning

Kumpulan notebook, tugas, dan laporan praktikum **Deep Learning** menggunakan **Python** dan **PyTorch**. Materi mencakup jaringan saraf untuk klasifikasi, pengolahan citra, serta prediksi data sekuensial dan deret waktu.

| Identitas | Keterangan |
| --- | --- |
| Nama | Habibi Putra Rizqullah |
| NIM | 2411531001 |
| Kelas | B |
| Mata Kuliah | Deep Learning |
| Repository | [DeepLearning_B_2411531001_Habibi-Putra-Rizqullah](https://github.com/habibiputrar/DeepLearning_B_2411531001_Habibi-Putra-Rizqullah) |

## Daftar Praktikum

| Praktikum | Materi | Dataset | Implementasi dan Eksperimen |
| --- | --- | --- | --- |
| [1](Praktikum1/) | Artificial Neural Network (ANN) | Iris | Standardisasi fitur, klasifikasi spesies bunga, evaluasi akurasi, visualisasi loss, serta perbandingan arsitektur jaringan. |
| [2](Praktikum2/) | Convolutional Neural Network (CNN) | MNIST | Klasifikasi digit tulisan tangan, pelatihan dan evaluasi model, visualisasi prediksi, serta perbandingan CNN dengan dua dan tiga lapisan konvolusi. |
| [3](Praktikum3/) | Recurrent Neural Network (RNN) | Deret sinus dan cosinus sintetis | Pembentukan sequence, prediksi nilai berikutnya, visualisasi hasil, serta eksperimen ukuran hidden state. |
| [4](Praktikum4/) | Long Short-Term Memory (LSTM) | Deret sinus dan cosinus sintetis | Perbandingan RNN dan LSTM, evaluasi Mean Squared Error (MSE), serta eksperimen hidden size dan jumlah layer. |

## Notebook dan Laporan

Repository memuat **6 notebook** dan **4 laporan PDF**. Pada Praktikum 1 dan 2, notebook tugas terpisah dari notebook praktikum. Pada Praktikum 3 dan 4, keduanya disusun dalam satu notebook melalui bagian **Praktikum** dan **Tugas Individu**.

| Praktikum | Notebook Praktikum | Tugas Individu | Laporan |
| --- | --- | --- | --- |
| 1 | [Praktikum1_DeepLearning.ipynb](Praktikum1/Praktikum1_DeepLearning.ipynb) | [Tugas_Praktikum1_DeepLearning.ipynb](Praktikum1/Tugas_Praktikum1_DeepLearning.ipynb) | [Laporan 1](Praktikum1/Habibi_Putra_Rizqullah-2411531001-Deep_Learning-B-Laporan1.pdf) |
| 2 | [Praktikum2_DeepLearning.ipynb](Praktikum2/Praktikum2_DeepLearning.ipynb) | [Tugas_Praktikum2_DeepLearning.ipynb](Praktikum2/Tugas_Praktikum2_DeepLearning.ipynb) | [Laporan 2](Praktikum2/Habibi_Putra_Rizqullah-2411531001-Deep_Learning-B-Laporan2.pdf) |
| 3 | [Praktikum3_DeepLearning.ipynb](Praktikum3/Praktikum3_DeepLearning.ipynb) | Bagian II pada notebook yang sama | [Laporan 3](Praktikum3/Habibi_Putra_Rizqullah-2411531001-Deep_Learning-B-Laporan3.pdf) |
| 4 | [Program4.ipynb](Praktikum4/2411531001_Habibi_Putra_Rizqullah_Program4.ipynb) | Bagian II pada notebook yang sama | [Laporan 4](Praktikum4/2411531001_Habibi%20Putra%20Rizqullah_Laporan4.pdf) |

## Struktur Repository

```text
.
├── Praktikum1/
│   ├── Praktikum1_DeepLearning.ipynb
│   ├── Tugas_Praktikum1_DeepLearning.ipynb
│   └── Laporan 1 (.pdf)
├── Praktikum2/
│   ├── Praktikum2_DeepLearning.ipynb
│   ├── Tugas_Praktikum2_DeepLearning.ipynb
│   └── Laporan 2 (.pdf)
├── Praktikum3/
│   ├── Praktikum3_DeepLearning.ipynb
│   └── Laporan 3 (.pdf)
├── Praktikum4/
│   ├── 2411531001_Habibi_Putra_Rizqullah_Program4.ipynb
│   └── Laporan 4 (.pdf)
└── README.md
```

Nama lengkap berkas laporan tersedia melalui tautan pada tabel di atas.

## Teknologi yang Digunakan

| Kebutuhan | Pustaka / Lingkungan |
| --- | --- |
| Pemrograman dan notebook | Python, Jupyter Notebook, Google Colab |
| Model dan pelatihan jaringan saraf | PyTorch (`torch`, `torch.nn`, `torch.optim`) |
| Dataset citra dan transformasi | torchvision |
| Pengolahan data dan tabel eksperimen | NumPy, pandas |
| Dataset Iris, standardisasi, dan evaluasi klasifikasi | scikit-learn |
| Grafik loss, akurasi, dan prediksi | Matplotlib |

## Menjalankan Notebook

### Melalui Google Colab

1. Buka [Google Colab](https://colab.research.google.com/).
2. Buka notebook melalui tab **GitHub**, lalu masukkan URL repository ini.
3. Pilih notebook yang ingin dijalankan dan gunakan runtime Python 3.
4. Periksa import pustaka, kemudian jalankan sel secara berurutan dari atas.
5. Amati hasil pelatihan, grafik, tabel perbandingan, dan pembahasan pada notebook.

Notebook Praktikum 2–4 memilih CUDA jika tersedia dan menggunakan CPU jika tidak tersedia. Pemilihan perangkat mengikuti kode pada notebook; lama pelatihan dapat berbeda antar-runtime.

### Melalui Jupyter di Komputer Lokal

Unduh repository:

```bash
git clone https://github.com/habibiputrar/DeepLearning_B_2411531001_Habibi-Putra-Rizqullah.git
cd DeepLearning_B_2411531001_Habibi-Putra-Rizqullah
```

Gunakan Python yang kompatibel dengan versi PyTorch yang dipasang. Pasang `torch` dan `torchvision` mengikuti [panduan instalasi resmi PyTorch](https://pytorch.org/get-started/locally/), sesuai sistem operasi dan pilihan CPU atau CUDA.

Pasang pustaka pendukung dan Jupyter Notebook:

```bash
python -m pip install numpy pandas matplotlib scikit-learn notebook
```

Jalankan Jupyter dari folder repository, lalu buka salah satu file `.ipynb`:

```bash
jupyter notebook
```

Panduan pemasangan dan perintah menjalankan Jupyter juga tersedia pada [dokumentasi instalasi Jupyter](https://jupyter.org/install).

## Dataset dan Hasil Eksperimen

- **Iris** dimuat melalui `load_iris()` dari scikit-learn.
- **MNIST** diunduh oleh torchvision ke folder `./data` saat notebook dijalankan dengan `download=True`; akses internet diperlukan pada unduhan pertama.
- **Data sinus dan cosinus** dibuat langsung di dalam notebook untuk eksperimen prediksi sekuensial.

Notebook menyertakan output tersimpan berupa hasil evaluasi, grafik pelatihan, contoh prediksi, serta tabel eksperimen. Pembahasan lebih lanjut tersedia pada laporan PDF masing-masing praktikum.

Hasil pelatihan dapat berubah sesuai inisialisasi model, konfigurasi eksperimen, perangkat, dan lingkungan pustaka. Gunakan parameter pada notebook saat membandingkan eksperimen yang sama.

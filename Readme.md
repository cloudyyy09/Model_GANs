# 🎨 Model_GANs - Implementasi Generative Adversarial Networks

# Kelompok 2
## Revo Pratama - G1A022058
## Ahmad Radesta - G1A022086
## Ari Setiawan - G1A022092

Repositori ini berisi implementasi dari *Generative Adversarial Networks (GANs)* menggunakan Python dan Jupyter Notebook. GAN merupakan model generatif berbasis deep learning yang mampu menghasilkan data sintetis menyerupai distribusi data asli, seperti gambar, teks, atau sinyal lainnya.

Proyek ini ditujukan untuk pembelajaran dan eksperimen terhadap cara kerja GAN, pelatihan Generator dan Discriminator, serta pengamatan terhadap kualitas hasil data sintetis yang dihasilkan.

---

## 📚 1. Teori Dasar GAN

*Generative Adversarial Network (GAN)* adalah arsitektur deep learning yang diperkenalkan oleh Ian Goodfellow dkk. pada tahun 2014. GAN terdiri dari dua jaringan saraf utama yang saling bersaing:

- *Generator (G):* Bertugas menghasilkan data baru (palsu) yang mirip dengan data asli.
- *Discriminator (D):* Bertugas membedakan antara data asli (real) dan data palsu (fake) yang dihasilkan oleh Generator.

Proses pelatihan GAN bersifat adversarial:  
Generator belajar untuk menipu Discriminator, sementara Discriminator belajar untuk mengenali hasil buatan Generator.

---

## 🧠 2. Tujuan Proyek

- Memahami arsitektur dan prinsip kerja GAN.
- Membangun model GAN dari awal menggunakan framework deep learning.
- Melatih Generator dan Discriminator secara iteratif.
- Menghasilkan data sintetis (gambar atau lainnya) dari noise acak.
- Mengamati proses pembelajaran Generator melalui visualisasi output.

---

## 🗂 3. Struktur Direktori
├── model_GANs.ipynb # Notebook utama implementasi dan pelatihan GAN
├── README.md # Dokumentasi proyek
└── hasil/ # (opsional) folder hasil output model (jika disimpan)


---

## 🛠 4. Dependensi dan Instalasi

### 📦 Requirements:
- Python ≥ 3.7
- TensorFlow atau PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

### 🔧 Instalasi:
```bash
git clone https://github.com/cloudyyy09/Model_GANs.git
cd Model_GANs
pip install -r requirements.txt
jupyter notebook

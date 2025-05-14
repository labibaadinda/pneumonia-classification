# Klasifikasi Pneumonia

## Deskripsi Proyek

Proyek ini bertujuan untuk mengembangkan model CNN (Convolutional Neural Network) yang dapat mengklasifikasikan citra rontgen dada (chest X-ray) untuk mendeteksi pneumonia pada anak-anak usia 1 hingga 5 tahun. Dataset yang digunakan berasal dari **Guangzhou Women and Children’s Medical Center, Guangzhou**, yang berfokus pada citra rontgen dada anak-anak sebagai bagian dari perawatan klinis rutin mereka.

### Dataset

Dataset ini terdiri dari **5.863 gambar rontgen dada** yang terbagi menjadi dua kelas:

* **Pneumonia**
* **Normal**

Dataset ini dipisahkan menjadi tiga folder utama:

1. **Train**: Untuk pelatihan model AI.
2. **Test**: Untuk pengujian model.
3. **Val**: Untuk validasi model.

### Instalasi

Untuk menjalankan proyek ini, Anda memerlukan beberapa pustaka Python. Anda dapat menginstal pustaka-pustaka yang dibutuhkan dengan mengikuti langkah-langkah berikut:

#### 1. **Kloning Repositori (Opsional)**
```bash
git clone https://github.com/labibaadinda/pneumonia-classification.git
cd pneumonia-classification
```

#### 2. **Menyiapkan Lingkungan Virtual**

Disarankan untuk membuat lingkungan virtual untuk menghindari konflik dependensi. Berikut adalah langkah-langkah untuk membuat lingkungan virtual menggunakan `venv`:

* **Membuat Lingkungan Virtual**:

  ```bash
  python3 -m venv venv
  ```

* **Mengaktifkan Lingkungan Virtual**:

  * Untuk Windows:

    ```bash
    venv\Scripts\activate
    ```
  * Untuk macOS/Linux:

    ```bash
    source venv/bin/activate
    ```

#### 3. **Menginstal Dependensi**

Setelah mengaktifkan lingkungan virtual, Anda dapat menginstal semua dependensi yang diperlukan dengan menjalankan perintah berikut untuk menginstal dari file `requirements.txt`:

```bash
pip install -r requirements.txt
```

#### 4. **Instalasi Pustaka Tambahan (Opsional)**

Jika ada pustaka yang perlu diinstal secara manual, Anda dapat menginstalnya dengan pip. Contoh:

```bash
pip install tensorflow
pip install tensorflowjs
pip install seaborn
pip install matplotlib
```

#### 5. **Menyiapkan Dataset**

* Pastikan mengunduh dataset rontgen dada pneumonia dan menempatkannya di lokasi yang sesuai. Dataset nya [Guangzhou Women and Children’s Medical Center](https://www.researchgate.net/figure/The-splits-of-the-pneumonia-datasets-from-Guangzhou-Women-and-Childrens-Medical-Center_tbl1_348896669)
* Sesuaikan path dataset di dalam kode program, jika diperlukan.

#### 6. **Menjalankan Proyek**

Setelah semua dependensi terinstall, dapat mulai menjalankan proyek dengan menjalankan skrip atau notebook yang sesuai. Jika menggunakan Jupyter Notebook atau Google Colab, pastikan untuk mengupload dataset yang dibutuhkan dan jalankan notebook.

---

### Referensi

* [Guangzhou Women and Children’s Medical Center](https://www.researchgate.net/figure/The-splits-of-the-pneumonia-datasets-from-Guangzhou-Women-and-Childrens-Medical-Center_tbl1_348896669)
* [TensorFlow Documentation](https://www.tensorflow.org/)


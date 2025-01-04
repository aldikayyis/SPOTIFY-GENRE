# **Spotify Songs Analysis**

Proyek ini bertujuan untuk menganalisis dataset yang berisi 5000 lagu Spotify dari berbagai genre. Setiap lagu memiliki berbagai fitur audio seperti `danceability`, `energy`, `tempo`, dan `valence`, yang dianalisis untuk memahami pola serta hubungan antar fitur. Selain itu, dibuat variabel baru, `mood`, yang menggambarkan suasana atau karakter emosional lagu berdasarkan kombinasi fitur-fitur audio tersebut.

Proyek ini terdiri dari beberapa langkah utama, termasuk pembersihan data, eksplorasi data, pembuatan variabel baru, hingga visualisasi hasil analisis. Hasil akhir diharapkan dapat memberikan wawasan tentang pola karakteristik audio lagu-lagu Spotify dan bagaimana fitur-fitur tersebut berkontribusi terhadap suasana lagu.

---

## **Highlights Proyek**

### **1. Pembersihan Data**
- Menghapus nilai yang hilang pada kolom fitur audio.
- Menstandarkan format kolom dan mengatasi duplikat.
- Mengatasi outlier pada fitur `tempo`, `energy`, dan `valence` untuk menjaga kualitas analisis.

### **2. Eksplorasi Data**
- Menganalisis distribusi fitur utama (`danceability`, `energy`, `valence`, `tempo`).
- Menghitung korelasi antar fitur audio menggunakan matriks korelasi.
- Menemukan hubungan signifikan antara beberapa fitur, seperti antara `energy` dan `valence`.

### **3. Pembuatan Variabel Mood**
- Membuat variabel baru bernama `mood` berdasarkan kombinasi dua fitur: `energy` dan `valence`.
- Kategori mood:
  - **Happy**: Valence tinggi, energy tinggi.
  - **Sad**: Valence rendah, energy rendah.
  - **Energetic**: Valence rendah, energy tinggi.
  - **Calm**: Valence tinggi, energy rendah.

### **4. Visualisasi Data**
Visualisasi digunakan untuk memperjelas hasil analisis dan memberikan wawasan lebih lanjut:
- Scatter plot untuk hubungan antara `energy` dan `valence`.
- Matriks korelasi antar fitur audio.
- Bar chart distribusi kategori `mood` pada dataset.

---

## **File Proyek**

- **`spotify_songs_with_mood.csv`**: Dataset yang telah diproses dan diperbarui dengan kolom `mood`.
- **`README.md`**: Dokumentasi proyek ini.
- **`matrix spotify.png`**: Gambar matriks korelasi yang menunjukkan hubungan antar fitur audio.
- **`mood.png`**: Visualisasi distribusi mood lagu.
- **`Energy dan Valence.png`**: Scatter plot hubungan antara `energy` dan `valence`.
- **`SPOTIFY_GENRE.ipynb`**: Notebook Jupyter untuk eksplorasi dan analisis data.

---

## **Contoh Visualisasi**

1. **Matriks Korelasi Antar Fitur Audio**  
   Menunjukkan hubungan antar fitur audio seperti `energy`, `valence`, dan `tempo`.  
   ![Correlation Matrix](matrix%20spotify.png)

2. **Distribusi Mood Lagu**  
   Menampilkan distribusi lagu berdasarkan kategori mood yang telah dibuat.  
   ![Mood Distribution](mood.png)

3. **Hubungan Antara Energy dan Valence**  
   Scatter plot ini menunjukkan bagaimana `energy` dan `valence` saling berkaitan dalam menentukan mood lagu.  
   ![Energy vs Valence](Energy%20dan%20Valence.png)

---

## **Cara Menjalankan Proyek**

1. **Clone repositori ini**:
   ```bash
   git clone https://github.com/username/spotify-songs-analysis.git
   ```

2. **Instal dependensi Python**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan file notebook untuk analisis**:
   ```bash
   jupyter notebook SPOTIFY_GENRE.ipynb
   ```

---

## **Kesimpulan**

Proyek ini menunjukkan bagaimana fitur audio pada lagu-lagu Spotify dapat dikategorikan ke dalam suasana atau mood tertentu. Melalui analisis ini, ditemukan bahwa kombinasi `energy` dan `valence` sangat memengaruhi suasana lagu, yang divisualisasikan ke dalam empat kategori mood utama: **Happy**, **Sad**, **Energetic**, dan **Calm**. 

Wawasan ini dapat digunakan oleh produser musik, pengembang aplikasi musik, dan pendengar dalam memilih atau merekomendasikan lagu berdasarkan suasana hati yang diinginkan. Langkah selanjutnya bisa berupa pembuatan model machine learning sederhana untuk memprediksi mood lagu baru berdasarkan fitur audionya.

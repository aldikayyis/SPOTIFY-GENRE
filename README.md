# Spotify Songs Analysis

Proyek ini bertujuan untuk menganalisis dataset yang berisi 5000 lagu Spotify dari berbagai genre. Setiap lagu memiliki berbagai fitur audio seperti danceability, energy, tempo, dan valence, yang dianalisis untuk memahami pola dan hubungan antar fitur. Selain itu, kami menciptakan variabel baru, `mood`, untuk menggambarkan suasana atau karakter emosional lagu berdasarkan fitur-fitur audio tersebut.

![Spotify Analysis](https://via.placeholder.com/800x400.png?text=Visualization+Placeholder)

## Highlights Proyek
- **Pembersihan Data**: Menghilangkan data yang hilang, mendeteksi outlier, dan menstandarkan format kolom.
- **Eksplorasi Data**: Menganalisis distribusi, pola, dan korelasi antar fitur audio.
- **Pembuatan Variabel Mood**: Mengkategorikan lagu ke dalam mood seperti 'Happy', 'Sad', 'Energetic', dan 'Calm' berdasarkan valence dan energy.
- **Visualisasi Data**: Membuat visualisasi seperti scatter plots, heatmaps, dan bar charts untuk menyajikan hasil analisis.

## File Proyek
- **`spotify_songs_with_mood.csv`**: Dataset yang telah diproses dan diperbarui dengan kolom `mood`.
- **`analysis_report.md`**: Dokumentasi analisis data, lengkap dengan interpretasi dan hasil eksplorasi.
- **`correlation_matrix.png`**: Gambar matriks korelasi untuk menggambarkan hubungan antar fitur audio.

## Contoh Visualisasi
Berikut adalah beberapa contoh visualisasi dari analisis ini:

1. **Matriks Korelasi Antar Fitur Audio**  
   ![Correlation Matrix](path/to/correlation_matrix.png)

2. **Distribusi Mood Lagu**  
   ![Mood Distribution](path/to/mood_distribution.png)

3. **Hubungan Antara Energy dan Valence**  
   ![Energy vs Valence](path/to/energy_vs_valence.png)

## Cara Menjalankan Proyek
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/spotify-songs-analysis.git

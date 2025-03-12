---

# Advanced Natural Language Processing Projects

Proyek ini berisi kumpulan resep (recipes) implementasi teknik-teknik **Advanced Natural Language Processing (NLP)**. Setiap resep menjelaskan dan mengimplementasikan solusi untuk permasalahan NLP yang berbeda, mulai dari analisis sentimen hingga konversi teks ke suara dan penerjemahan.

## Daftar Resep

1. **Text Similarity**  
   Menghitung kemiripan antara dokumen menggunakan **TF-IDF** dan **cosine similarity** dengan *scikit-learn*.

2. **POS Tagging**  
   Melakukan part-of-speech tagging menggunakan modul **nltk** untuk memberi label pada kata-kata (noun, verb, adjective, dll).

3. **Named Entity Recognition (NER)**  
   Mengekstraksi entitas seperti nama orang, organisasi, atau lokasi dari sebuah teks menggunakan **nltk** dan **SpaCy**.

4. **Topic Extraction**  
   Mengidentifikasi topik dalam dokumen melalui teknik **LDA (Latent Dirichlet Allocation)** menggunakan pustaka **gensim**.

5. **Text Classification**  
   Mengklasifikasikan teks, contohnya untuk membedakan email spam dan ham, dengan menggunakan model **Naive Bayes** dan **Logistic Regression**.

6. **Sentiment Analysis**  
   Menganalisis sentimen suatu teks (positif atau negatif) menggunakan **TextBlob** untuk memperoleh nilai polarity dan subjectivity.

7. **Word Sense Disambiguation**  
   Menangani ambiguitas kata (misalnya kata "bank" dengan arti institusi keuangan atau tepi sungai) menggunakan algoritma **Lesk** dari pustaka **pywsd** dan **nltk**.

8. **Speech-to-Text**  
   Mengkonversi suara menjadi teks menggunakan **SpeechRecognition** dan **PyAudio**. (Catatan: untuk lingkungan cloud seperti Google Colab, gunakan file audio sebagai input karena akses mikrofon lokal terbatas.)

9. **Text-to-Speech**  
   Mengkonversi teks menjadi suara menggunakan **gTTS** (Google Text-to-Speech) dan memutar audio secara langsung di Google Colab.

10. **Translating Speech**  
    Menerjemahkan teks dari satu bahasa ke bahasa lain menggunakan **googletrans** sebagai alternatif dari pustaka goslate yang sudah tidak aktif.

## Cara Menjalankan Proyek

1. **Instalasi Dependensi**  
   Pastikan semua pustaka yang diperlukan sudah terinstal. Jika menggunakan Google Colab, gunakan perintah:
   ```python
   !pip install -q gtts googletrans==4.0.0-rc1 SpeechRecognition PyAudio gensim nltk spacy pywsd
   ```
   Jangan lupa untuk mengunduh resource NLTK (seperti `stopwords`, `punkt`, dll.) dan model SpaCy jika diperlukan.

2. **Jalankan Notebook**  
   Proyek ini dikembangkan menggunakan **Jupyter Notebook**. Kamu dapat menjalankannya di lingkungan lokal (misalnya melalui PyCharm) atau di Google Colab sesuai kebutuhan.

3. **Konfigurasi Input/Output**  
   Pastikan kamu mengupload file audio jika menggunakan modul Speech-to-Text di Google Colab, atau jalankan kode di lingkungan lokal dengan mikrofon yang sudah terkonfigurasi dengan benar.

## Informasi Pengembang

- **Nama**: Rafif Nuraydin  
- **Kelas**: TI-CCIT 6B  
- **NIM**: 2207412051  

## Kesimpulan

Proyek ini mencakup implementasi berbagai teknik NLP yang berguna untuk analisis teks dan suara. Resep-respelnya dapat digunakan sebagai dasar untuk pengembangan aplikasi NLP yang lebih kompleks, seperti analisis sentimen, klasifikasi teks, ekstraksi topik, dan penerjemahan bahasa.

---

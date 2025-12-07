# Tugas-Akhir-IR-Hoax-Search

Proyek ini adalah implementasi sistem Information Retrieval (IR) sederhana untuk melakukan pencarian dan penelusuran pada dataset berita hoax di Indonesia (TurnBackHoax). Sistem dibangun menggunakan Python dengan menerapkan metode pembobotan TF-IDF dan BM25, serta melalui tahap preprocessing teks bahasa Indonesia (Sastrawi).

Fitur Utama:

    Preprocessing: Tokenisasi, Stopword Removal, dan Stemming (Library Sastrawi).

    Modeling: Implementasi Vector Space Model (TF-IDF) dan Probabilistic Model (BM25).

    Search Engine: Fitur pencarian berita relevan berdasarkan keyword.

    Evaluasi Kinerja: Pengujian otomatis menggunakan metrik Precision, Recall, dan Mean Average Precision (MAP).

Hasil Evaluasi: Berdasarkan pengujian terhadap 10 query sampel, sistem mencapai skor MAP (Mean Average Precision) sebesar 0.9985 (99.85%), menunjukkan akurasi yang sangat tinggi dalam mengurutkan dokumen relevan.

Teknologi:

    Python (Pandas, NumPy, Scikit-learn, Sastrawi).

    Google Colab / Jupyter Notebook.

# Adipati Analisis Profil LinkedIn 🚀💼

Selamat datang di Analisis Profil LinkedIn! Alat ini tidak hanya membaca profil Anda tetapi juga menganalisis gambar profil secara visual untuk memberikan umpan balik terperinci dan saran yang dapat dilaksanakan untuk meningkatkan profil LinkedIn.

### Bagaimana Cara Kerjanya
Aplikasi kami memanfaatkan kekuatan model OpenAI's GPT-4 dan GPT-4 Vision melalui API Assistant, mengintegrasikan kemampuan analisis teks dan visual. Berikut adalah gambaran singkat:

- **app.py:** Frontend aplikasi, dibangun dengan Streamlit. Ini mengelola antarmuka pengguna, memfasilitasi interaksi yang mudah, dan menampilkan wawasan langsung kepada Anda.
- **main.py:** Menginisialisasi Assistant OpenAI yang khusus dirancang untuk optimasi profil LinkedIn, menggabungkan pengambilan dari dokumen dan pemanggilan fungsi kustom.
- **linkedin_scraper.py:** Mengumpulkan data dari URL profil LinkedIn Anda, mempersiapkannya untuk analisis komprehensif oleh Asisten.

### Langkah-langkah Sederhana untuk Pengguna:
1. Masukkan URL profil LinkedIn Anda.
2. Aplikasi akan mengambil data profil Anda, mempersiapkannya untuk analisis mendalam.
3. Asisten AI kustom kami, ditingkatkan dengan kemampuan visual, memeriksa baik konten maupun gambar profil, memastikan evaluasi profil yang holistik.

### Sorotan
- **OpenAI Assistants API:** Menggunakan Assistants API untuk analisis teks dan rekomendasi.
- **Fungsi Kustom & GPT-4 Vision:** Fungsi kustom mengakses GPT-4 Vision untuk kritik yang mendalam terhadap gambar profil, mengevaluasi presentasi profesional dan kesesuaian.
- **Pengambilan dan Pemanggilan Fungsi:** Mengintegrasikan pengambilan dokumen untuk konteks yang lebih kaya dan memanggil fungsi kustom untuk tugas khusus seperti analisis gambar.

### Memulai dengan Cepat
1. **Klon dan Atur:** Klon repositori ini dan instal dependensi (pip install -r requirements.txt).
2. **Jalankan Aplikasi:** Gunakan streamlit run app.py untuk memulai aplikasi.
3. **Masukkan dan Analisis:** Cukup masukkan kunci API OpenAI dan URL profil LinkedIn Anda di sidebar, kemudian tekan "Analisis" untuk melihat keajaiban terjadi.

### Berkontribusi
Kami menyambut kontribusi! Jika Anda memiliki saran atau perbaikan, silakan fork repositori ini, commit pembaruan Anda, dan kirimkan pull request.

### Teknologi
- **Streamlit:** Untuk membuat antarmuka aplikasi web.
- **OpenAI API:** Memanfaatkan API Assistants, termasuk GPT-4 untuk analisis teks dan GPT-4 Vision untuk analisis gambar.
- **Python:** Untuk logika backend dan integrasi dengan API OpenAI.
- **Dibuat dengan ❤️ dan Python.**

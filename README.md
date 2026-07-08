# 👋 Naufal Azaria
### AI Native Engineer & Data Scientist

<p align="left">
  <a href="https://github.com/azcharia"><img src="https://img.shields.io/github/followers/azcharia?label=Follow&style=social" alt="GitHub Followers" /></a>
  <a href="mailto:azcharias@gmail.com"><img src="https://img.shields.io/badge/Email-azcharias%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://portopuerto.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-portopuerto.vercel.app-blueviolet?style=flat-square" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/azcharia"><img src="https://img.shields.io/badge/LinkedIn-Naufal%20Azaria-blue?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
</p>

*"Structure equals beauty."*

Saya adalah pengembang sistem AI-native dan peneliti data science yang berfokus menjembatani arsitektur perangkat lunak dengan analisis kuantitatif. Saya membangun aplikasi lintas platform (Flutter), mengintegrasikan model cerdas (LLMs, RAG pipelines, Vector Databases), dan merancang visualisasi data interaktif untuk memberikan solusi praktis berdaya dampak tinggi.

---

### 🛠️ Technical Stack & Tools

*   **🧠 Data Science & AI:** Python, SQL, LlamaIndex, PyTorch, scikit-learn, pgvector, statsmodels (SARIMA), Pandas, NumPy, Streamlit.
*   **⚙️ Backend & APIs:** FastAPI, Node.js, Deno (Deno Edge Functions), Supabase Edge Functions, RESTful APIs.
*   **💻 Frontend & Mobile:** Flutter, Dart, Riverpod, React / Next.js, Tailwind CSS, shadcn/ui.
*   **🗄️ Databases & Devops:** PostgreSQL, Supabase RLS, SQLite, Hive (Local Cache), Git / GitHub Workflows.

---

### 🚀 Featured Projects

#### 📊 [Regional Welfare Polarization Analysis](https://github.com/azcharia/welfare-polarization-indonesia)
> Pipeline machine learning tidak terawasi (unsupervised learning) untuk menganalisis polarisasi kesejahteraan regional di Indonesia.
*   **Detail:** Melakukan segmentasi terhadap 514 kabupaten/kota di Indonesia berdasarkan indikator sosio-ekonomi BPS. Menguji 28 konfigurasi clustering (menentukan K-Means K=4 optimal), menerapkan PCA untuk reduksi dimensi, dan membuat dasbor Streamlit interaktif dengan Plotly.
*   **Stack:** Python, scikit-learn, PCA, Streamlit, Plotly, Node.js (untuk compiler laporan otomatis).

#### 📈 [Predictive Time-Series Modeling](https://github.com/azcharia/research-forecasting)
> Pipeline peramalan deret waktu (time-series forecasting) untuk memprediksi konsumsi energi harian.
*   **Detail:** Mengembangkan dan membandingkan model dasar statistik (SARIMA) dengan model Deep Learning sekuensial (RNN, LSTM, GRU) menggunakan PyTorch. LSTM berhasil mencapai akurasi tertinggi dalam menekan angka kesalahan prediksi.
*   **Stack:** PyTorch, LSTM, GRU, statsmodels, Python, Pandas.

#### 🏗️ [Leighton Asia — AI Defect Tracker](https://github.com/azcharia/leighton)
> Aplikasi Flutter yang terintegrasi dengan Groq LLaMA Vision API dan Whisper API untuk mengotomatisasi pencatatan cacat konstruksi secara asinkron.
*   **Detail:** Meraih Juara 3 pada AI STOR 2.0 Hackathon. Memanfaatkan Deno Edge Functions dan pg_net trigger di Supabase untuk menjalankan inferensi gambar secara serverless.
*   **Stack:** Flutter, React, Supabase (Postgres, Edge Functions), Groq API (LLaMA Vision & Whisper).

#### 🛒 [NobleSoft — AI-Assisted POS SaaS](https://github.com/azcharia/noblesoft)
> Aplikasi Point of Sale (POS) multi-tenant untuk UMKM yang mengutamakan interaksi Chat-First berbasis AI.
*   **Detail:** Memiliki asisten AI terintegrasi menggunakan LlamaIndex dan Groq API untuk menerjemahkan bahasa alami langsung menjadi transaksi database. Menggunakan pgvector untuk pencarian semantik produk serta BYOK untuk isolasi kredensial pengguna secara aman.
*   **Stack:** FastAPI (Python), Next.js, LlamaIndex, pgvector, Supabase.

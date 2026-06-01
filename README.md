# 👋 Naufal Azaria
### Software Engineer & Cross-Platform Developer

<p align="left">
  <a href="https://github.com/azcharia"><img src="https://img.shields.io/github/followers/azcharia?label=Follow&style=social" alt="GitHub Followers" /></a>
  <a href="mailto:azcharias@gmail.com"><img src="https://img.shields.io/badge/Email-azcharias%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://portopuerto.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-portopuerto.vercel.app-blueviolet?style=flat-square" alt="Portfolio" /></a>
  <a href="https://instagram.com/azcharia"><img src="https://img.shields.io/badge/Instagram-%40azcharia-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" /></a>
</p>

*"Simplicity is the ultimate sophistication."*

I am a software developer based in Indonesia. I build cross-platform mobile apps with Flutter and Dart, and design backend systems that integrate AI. My work is focused on clean architecture, practical database design, and building tools that solve real problems.

---

### 🛠️ Technical Stack & Tools

*   **💻 Frontend & Mobile:** Flutter, Dart, Riverpod, Provider, HTML/CSS, responsive web layouts.
*   **⚙️ Backend & APIs:** FastAPI (Python), Next.js (TypeScript), Node.js, Deno, Deno Deploy (Edge Functions).
*   **🗄️ Databases & Storage:** Supabase, PostgreSQL, SQLite (sqflite), Hive (Local Key-Value Cache), pgvector.
*   **🧠 Data Science & AI:** Groq API, OpenRouter, LlamaIndex, PyTorch, Statsmodels (SARIMA), Pandas, NumPy.

---

### 🚀 Featured Projects

#### 🏗️ [Leighton Asia — AI-Assisted Defect Logging MVP](https://github.com/azcharia/leighton)
> A mobile and web system built for the Leighton Asia Hackathon to automate construction site defect logging.
*   **How it works:** Field engineers snap a photo of a concrete defect and record a brief voice description. The system uploads the assets to Supabase, transcribes the audio using the Groq Whisper API, classifies the defect using the Groq LLaMA Vision API, and syncs the result to a React-based web dashboard in real-time.
*   **Stack:** Flutter, React (Vite, Tailwind CSS), Supabase (Postgres, Deno Edge Functions, Storage), Groq Whisper & LLaMA Vision.
*   **Links:** 🌐 [Live Web Dashboard](https://leighton.vercel.app) | 📹 [Video Demo](https://drive.google.com/file/d/1q-Y1UHx0D5lUxl3pBuWeaL2TrEEYPH_D/view?usp=sharing)

#### 🛒 [NobleSoft — Chat-First POS & Inventory](https://github.com/azcharia/noblesoft)
> An open-source cashier and inventory management system designed for Indonesian micro-businesses.
*   **How it works:** Instead of forcing users to navigate complex forms and nested menus, it uses a chat-based interface. Users type natural commands (such as *"Jual Kopi Susu 2 cup ke Budi"* or *"Tambah stok Sabun Mandi 10 pcs"*), and a Python backend parses the instruction to update inventory and record the sale in a PostgreSQL database.
*   **Stack:** FastAPI (Python), Next.js (TypeScript, shadcn/ui), Supabase (PostgreSQL + `pgvector`), LlamaIndex, Groq API.
*   **Links:** 💻 [Source Code](https://github.com/azcharia/noblesoft)

#### 🌸 [Chatty — Personal AI Companion](https://github.com/azcharia/chatty)
> A personal companion chat application featuring Akane, a virtual friend built with conversational capability in mind.
*   **How it works:** It uses the OpenRouter API with the Owl Alpha model to achieve natural, context-aware dialogue with a massive context memory. It includes a local parser that detects reminder requests from natural chat and registers local device notifications, along with diagnostic tools to manage the local database.
*   **Stack:** Flutter, SQLite (sqflite), Provider, OpenRouter API.
*   **Links:** 💻 [Source Code](https://github.com/azcharia/chatty)

#### 🏛️ [SIPEN-GO — Gombang Census & Demographic System](https://github.com/azcharia/sipengo)
> A census and demographic management database built for the Gombang village government in Indonesia.
*   **How it works:** The app maps address structures, tracks individual resident details, renders dynamic family tree diagrams, and pinpoints family locations using Google Maps coordinate integrations. To handle spotty internet in rural areas, it uses Hive for offline-first caching before syncing data back to Supabase.
*   **Stack:** Flutter, Riverpod, Supabase (PostgreSQL + Auth), Hive Local Cache, Google Maps API.
*   **Links:** 💻 [Source Code](https://github.com/azcharia/sipen-go)

#### 📊 [Walmart Sales Forecasting](https://github.com/azcharia/research)
> Time-series forecasting experiments built to compare traditional statistical models with deep learning architectures.
*   **How it works:** It processes historical Walmart sales data, implements feature engineering (lagged variables, calendar adjustments, rolling statistics), and trains forecasting models to predict weekly store revenues.
*   **Stack:** Python, PyTorch, Statsmodels, Pandas, NumPy, Scikit-learn, Jupyter Notebook.
*   **Links:** 💻 [Source Code](https://github.com/azcharia/research)

---

### 🌱 Other Projects
*   **[plant-watering-reminder](https://github.com/azcharia/plant-watering-reminder):** A utility application built in Dart for tracking and scheduling plant watering cycles.
*   **[airi](https://github.com/azcharia/airi):** An exploratory playground project focused on JavaScript and TypeScript configurations.

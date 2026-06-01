# Naufal Azaria
I am a software developer based in Indonesia. I build cross-platform mobile apps with Flutter and Dart, and design backend systems that integrate AI. My work is focused on clean architecture, practical database design, and building tools that solve real problems.

You can reach me at [azcharias@gmail.com](mailto:azcharias@gmail.com), check my portfolio at [portopuerto.vercel.app](https://portopuerto.vercel.app/), or follow me on Instagram [@azcharia](https://instagram.com/azcharia).

---

### Technical Skills

*   **Frontend & Mobile:** Flutter, Dart, Riverpod, Provider, HTML/CSS, responsive web layouts.
*   **Backend & APIs:** FastAPI (Python), Next.js (TypeScript), Node.js, Deno, Deno Deploy (Edge Functions).
*   **Databases & Storage:** Supabase, PostgreSQL, SQLite (sqflite), Hive (Local Key-Value Cache), pgvector.
*   **Data Science & AI:** Groq API, OpenRouter, LlamaIndex, PyTorch, Statsmodels (SARIMA), Pandas, NumPy.

---

### Featured Projects

#### Leighton Asia — AI-Assisted Defect Logging MVP
A mobile and web system built for the Leighton Asia Hackathon to automate construction site defect logging. Field engineers snap a photo of a concrete defect and record a brief voice description. The system uploads the assets to Supabase, transcribes the audio using the Groq Whisper API, classifies the defect using the Groq LLaMA Vision API, and syncs the result to a React-based web dashboard in real-time.
*   **Tech Stack:** Flutter, React (Vite, Tailwind CSS), Supabase (Postgres, Deno Edge Functions, Storage), Groq Whisper & LLaMA Vision.
*   **Artifacts:** [Live Web Dashboard](https://leighton.vercel.app) | [Source Code](https://github.com/azcharia/leighton) | [Video Demo](https://drive.google.com/file/d/1q-Y1UHx0D5lUxl3pBuWeaL2TrEEYPH_D/view?usp=sharing)

#### NobleSoft — Chat-First POS and Inventory
An open-source cashier and inventory management system designed for Indonesian micro-businesses. Instead of forcing users to navigate complex forms and nested menus, it uses a chat-based interface. Users type natural commands (such as "Jual Kopi Susu 2 cup ke Budi" or "Tambah stok Sabun Mandi 10 pcs"), and a Python backend parses the instruction to update inventory and record the sale in a PostgreSQL database.
*   **Tech Stack:** FastAPI (Python), Next.js (TypeScript, shadcn/ui), Supabase (PostgreSQL + `pgvector`), LlamaIndex, Groq API.
*   **Artifacts:** [Source Code](https://github.com/azcharia/noblesoft)

#### Chatty — Personal AI Companion
A personal companion chat application featuring Akane, a virtual friend built with conversational capability in mind. It uses the OpenRouter API with the Owl Alpha model to achieve natural, context-aware dialogue with a massive context memory. It includes a local parser that detects reminder requests from natural chat and registers local device notifications, along with diagnostic tools to manage the local database.
*   **Tech Stack:** Flutter, SQLite (sqflite), Provider, OpenRouter API.
*   **Artifacts:** [Source Code](https://github.com/azcharia/chatty)

#### SIPEN-GO — Village Population Census
A census and demographic management database built for the Gombang village government in Indonesia. The app maps address structures, tracks individual resident details, renders dynamic family tree diagrams, and pinpoints family locations using Google Maps coordinate integrations. To handle spotty internet in rural areas, it uses Hive for offline-first caching before syncing data back to Supabase.
*   **Tech Stack:** Flutter, Riverpod, Supabase (PostgreSQL + Auth), Hive Local Cache, Google Maps API.
*   **Artifacts:** [Source Code](https://github.com/azcharia/sipen-go)

#### Walmart Sales Forecasting
Time-series forecasting experiments built to compare traditional statistical models with deep learning architectures. It processes historical Walmart sales data, implements feature engineering (lagged variables, calendar adjustments, rolling statistics), and trains forecasting models to predict weekly store revenues.
*   **Tech Stack:** Python, PyTorch, Statsmodels, Pandas, NumPy, Scikit-learn, Jupyter Notebook.
*   **Artifacts:** [Source Code](https://github.com/azcharia/research)

---

### Other Projects
*   **[plant-watering-reminder](https://github.com/azcharia/plant-watering-reminder):** A utility application built in Dart for tracking and scheduling plant watering cycles.
*   **[airi](https://github.com/azcharia/airi):** An exploratory playground project focused on JavaScript and TypeScript configurations.

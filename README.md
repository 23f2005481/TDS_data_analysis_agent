
# ⚡ Data Analyst Agent — Your AI-Powered Data Companion

> Smarter, faster, and more intuitive analysis of your datasets using **Generative AI + Python magic** ✨
> **Repository:** *\[Insert GitHub Repo Link]*

---

## 📌 Overview

Meet **Data Analyst Agent 2.0** — your AI-driven partner for data exploration and analysis.

Forget manual crunching — just upload your dataset + questions, and get:
✅ Clean visual reports
✅ AI-generated insights
✅ Automated workflows

**Who’s it for?**

* 🧾 Analysts
* 🔬 Researchers
* 📈 Startups & Businesses
* 🎓 Students & Learners

Turn raw data into actionable knowledge in minutes.

---

## ✨ Features at a Glance

| Feature                 | Why It Matters 🚀                                |
| ----------------------- | ------------------------------------------------ |
| 🤖 AI-Powered Insights  | Understands queries using Google’s Generative AI |
| 📊 Rich Visualizations  | Interactive plots via **Seaborn & Matplotlib**   |
| 🌍 Web Scraper Mode     | Pull fresh data from live URLs                   |
| 📂 Multi-Format Support | CSV, Excel, JSON, Parquet, TXT                   |
| 🔄 Batch Q\&A           | Answer multiple questions in one go              |
| 🖥️ User-Friendly       | Clean UI, zero steep learning curve              |
| ⚡ Speed Optimized       | Fast execution with real-time feedback           |

---

## 🚀 Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/data-analyst-agent.git
cd data-analyst-agent
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure API Keys

Create a `.env` file in the project root:

```ini
GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240
```

### 4️⃣ Launch the App

```bash
python -m uvicorn app:app --reload
```

Open 👉 [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🧑‍💻 How It Works

1. **Write Queries** – Create a `.txt` file with natural language questions (e.g., “What’s the revenue growth month-over-month?”).
2. **Upload Dataset + Questions** –

   * Dataset (optional): CSV, Excel, JSON, Parquet, TXT
   * Questions file (required): Plain text
3. **Sit Back** – The AI processes your data, generates insights, and builds visualizations automatically.

---

## 🛠 Under the Hood

**Backend:**

* ⚡ FastAPI – Lightweight, high-performance API
* 🧠 LangChain – LLM orchestration framework
* ✨ Google Generative AI – Core intelligence
* 📊 Pandas + NumPy – Data wrangling
* 🎨 Seaborn + Matplotlib – Visual storytelling

**Frontend:**

* HTML5 + CSS + JavaScript
* Modern, Bootstrap-inspired UI

---

## 🔧 API Reference

| Method | Endpoint   | Description                |
| ------ | ---------- | -------------------------- |
| `GET`  | `/`        | Web interface              |
| `POST` | `/api`     | Submit dataset + questions |
| `GET`  | `/summary` | Diagnostics & summaries    |

---

## 📂 Supported File Types

| Format  | Extensions      |
| ------- | --------------- |
| CSV     | `.csv`          |
| Excel   | `.xlsx`, `.xls` |
| JSON    | `.json`         |
| Parquet | `.parquet`      |
| Text    | `.txt`          |

---

## 🎯 Use Cases

* 📈 **Business Strategy** – KPI tracking, forecasts, performance reviews
* 🔬 **Research** – Data exploration, correlation checks, hypothesis validation
* 🤖 **Data Science** – Fast EDA, anomaly detection
* 📊 **Reporting** – Auto-generated dashboards & summaries

---

## 🔒 Security First

* ✅ Local-first: no cloud storage of your data
* ✅ Secrets safe: API keys stored in `.env`
* ✅ Production-ready: Configurable CORS policies

---

## 📜 License

Licensed under the **MIT License** – free for personal and commercial use.

---

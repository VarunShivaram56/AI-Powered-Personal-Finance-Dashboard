# 💰 AI-Powered Personal Finance Dashboard with Local Intelligence

A **privacy-first, AI-powered desktop application** that helps users securely manage, analyze, and query their personal bank transactions **entirely offline**.  
All data extraction, storage, and AI inference occur **locally on the user’s machine**, ensuring complete data privacy and security.

---

## 🚀 Project Overview

The **AI-Powered Personal Finance Dashboard** enables users to:

- 🔒 **Redact sensitive information** from bank statements (PDFs) before processing  
- 📄 **Extract structured transactions** from PDF bank statements using AI  
- 🧠 **Intelligently categorize** transactions into 13 Indian financial categories  
- 💾 **Store transactions locally** in an encrypted SQLCipher database  
- 📊 **Visualize** spending patterns, income, and savings via interactive dashboards  
- 💬 **Query** finances in natural language using a **local RAG-enabled chatbot**  

This project focuses on **data privacy, local AI inference**, and **insightful visualization** — bringing intelligent finance management to your desktop without any cloud dependency.

---

## 🧩 Features (Planned / In Progress)

| Feature | Description | Status |
|----------|-------------|--------|
| PDF Upload & Redaction | Securely upload and redact bank statements | ✅ Planned |
| Transaction Extraction | Parse PDFs and extract structured data using LLM | 🧠 In Progress |
| Categorization | AI-based classification into 13 Indian categories | ⏳ Prototype |
| Local Encrypted Storage | Store data securely with SQLite/DuckDB + SQLCipher | ⏳ Planned |
| Dashboard Visuals | Interactive analytics with Plotly / React Charts | ⏳ Planned |
| RAG Chatbot | Natural language query system for transactions | 🧠 Planned |
| Privacy-first Design | 100% offline, local AI processing | ✅ Core Principle |

---

## 🏗️ Tech Stack

**Frontend:**  
- Electron.js  
- React.js  

**Backend:**  
- Python (FastAPI for modular services)  
- pdfplumber (PDF text extraction)  
- pandas, regex (data processing)  

**AI / NLP:**  
- Local LLM (e.g., Grok-4-Fast or compatible)  
- RAG pipeline with ChromaDB / FAISS / LanceDB  

**Database:**  
- SQLite / DuckDB (Encrypted with SQLCipher)  

**Visualization:**  
- Plotly, Matplotlib, React Charts  

---

## 🔐 Design Principles

1. **Privacy-First:** No cloud usage; everything runs locally  
2. **Modular & Extensible:** Separate components for parsing, categorization, and analytics  
3. **Explainable AI:** Clear transaction mapping and rule-based + AI classification  
4. **Secure Storage:** Encrypted database with local-only access  

---

## 🧠 System Flow (High-Level)

User → [Upload PDF]
→ [Redaction & Parsing via pdfplumber + LLM]
→ [Categorization into 13 financial categories]
→ [Encrypted Local DB Storage]
→ [Interactive Dashboard + RAG Chatbot Queries]



---

## 📁 Project Structure (Initial Draft)

AI-Finance-Dashboard/
│
├── backend/
│ ├── api/ # FastAPI endpoints
│ ├── parsing/ # PDF parsing logic
│ ├── categorization/ # Rule-based + LLM categorization
│ ├── storage/ # Encrypted DB logic
│ └── chatbot/ # Local RAG chatbot
│
├── frontend/
│ ├── electron/ # Electron.js wrapper
│ ├── react/ # React UI components
│ └── assets/ # Icons, logos, etc.
│
├── data/
│ ├── samples/ # Sample PDFs and JSON outputs
│ └── embeddings/ # Local vector DB files
│
├── README.md
└── requirements.txt




---

## 🧭 Future Roadmap

- [ ] Build working prototype for PDF parsing  
- [ ] Implement rule-based + LLM categorization  
- [ ] Integrate encrypted local DB storage  
- [ ] Design and link React dashboard  
- [ ] Develop RAG chatbot for local querying  
- [ ] Package desktop app with Electron  

---

## 🧑‍💻 Author
**Varun Shivaram**  
AI & Data Science Enthusiast | Web & Backend Developer  
📧 [Add your email or LinkedIn here (optional)]

---

## 📝 License
This project is currently in its **early development stage** and not yet open for production use.  
License type: *To be decided (e.g., MIT, Apache 2.0)*

---

## 🌟 Acknowledgements
- [pdfplumber](https://github.com/jsvine/pdfplumber)  
- [FastAPI](https://fastapi.tiangolo.com/)  
- [ChromaDB](https://www.trychroma.com/) / [FAISS](https://faiss.ai/)  
- [Electron](https://www.electronjs.org/)  
- [Plotly](https://plotly.com/)  

---

> 💡 *This project aims to redefine how individuals interact with their financial data — combining privacy, intelligence, and accessibility into one powerful local desktop app.*


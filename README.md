# 📄 Smart Documentation Retrieval System (SDRS)

## 📋 Project Overview
A bilingual (EN/FR) intelligent search engine that retrieves exact technical information from engine maintenance documentation using Natural Language Processing.

---

##  The Problem
Maintenance technicians waste time searching through thick technical manuals to find:
- Oil type and quantity for a specific engine
- Belt reference number
- Step-by-step maintenance procedures
- Battery specifications

This system answers any technical question instantly in English or French.

---

##  How It Works
---

##  Example Queries

| Question | Answer Found |
|----------|-------------|
| "What oil does ENG006 use?" | 6.5L 15W-40, filter OF-2234 |
| "Quelle courroie pour groupe clim?" | Référence 4PK1250 |
| "How to change the belt?" | 6-step procedure |
| "Quelle batterie pour groupe electrogene?" | BOSCH 12V-80Ah |

---

##  Technical Approach

### Documentation Simulated
- 28 technical documents
- 14 in English + 14 in French
- Categories: Engine Specs, Spare Parts, Coolant, Battery, Procedures, Safety

### NLP Pipeline
- TF-IDF Vectorization
- Cosine Similarity Search
- Top-K document retrieval

### Interactive Interface
- Built with ipywidgets
- Real-time search results
- Color-coded by category
- Language flag indicator 🇬🇧🇫🇷

---

##  Results
- ✅ Bilingual search working perfectly
- ✅ Correct document retrieved for all test queries
- ✅ Interactive interface for non-technical users
- ✅ Color-coded results by category

---

##  Repository Structure
---

##  Tools Used
- **Python** — Pandas, Scikit-learn
- **NLP** — TF-IDF, Cosine Similarity
- **UI** — ipywidgets, IPython Display
- **GitHub** — Version Control

---

## 🔗 Related Projects
- [Project 1 — Smart Engine Maintenance System](https://github.com/teachermarouane-ops/engine-maintenance-portfolio)
- [Project 2 — CBMS NLP Classifier](https://github.com/teachermarouane-ops/cbms-nlp-classifier)

---

## 👤 Author
**teachermarouane-ops**
ALX Data Science Program — Portfolio Project 2026

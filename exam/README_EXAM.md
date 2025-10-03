# 📝 Final Exam – Applications of Large Language Models

Welcome to the **Final Exam (2025)** for the course. This branch (`exam-2025-final`) contains all the materials students need.

---

## 📂 Folder Structure

```
exam/
├── FE_2025_Final.ipynb              # Colab-ready student notebook
├── dataset/
│   ├── renewable_energy_exam.txt     # Exam corpus (~2 pages)
│   └── queries.json                  # 5 exam queries
├── templates/
│   ├── partA_eval_template.csv       # Evaluation table template for Part A
│   └── partB_eval_template.csv       # Evaluation table template for Part B
├── rubrics/
│   ├── grading_checklist.md/.pdf     # TA checklist
│   ├── examiner_guide.md/.pdf        # Examiner guide
│   └── student_handout.md/.pdf       # Student handout
└── README_EXAM.md                    # This file
```

---

## 🚀 Getting Started

1. **Open the notebook in Colab:**  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anandrao1962/ALLM-2025-FE-simple-local-rag/blob/exam-2025-final/exam/FE_2025_Final.ipynb)

2. Run the **Setup** cell to install required libraries.

3. Load the dataset and queries (already provided in `exam/dataset/`).

4. Complete **Part A** and **Part B** as instructed in the notebook and the handout.

---

## 🅐 Part A — Prompting & Decoding (50 pts)

- Make **two prompt modifications** (persona, format, reasoning).  
- Try **two decoding strategies** (temperature/top‑k/top‑p).  
- Compare baseline vs. modified outputs for the 5 queries.  
- Fill in **partA_eval_template.csv**.  
- Write a **3–4 sentence reflection** on tool use.

---

## 🅑 Part B — Retrieval & Evaluation (50 pts)

- Choose ONE retrieval modification:  
  - Change **chunking**  
  - Swap **embedding model**  
  - Add **re‑ranking**  
- Compare baseline vs. modified on precision/recall/relevance.  
- Fill in **partB_eval_template.csv**.  
- Write a **3–4 sentence reflection** on tool use.

---

## ⚡ Bonus (+10 pts)

Optional: implement a small **agentic twist** (Self‑Ask / Plan‑and‑Answer / Tool‑Selector).  
Run on one query and add a short commentary.

---

## 📑 Submission Checklist

- [ ] Completed Part A code + evaluation + reflection  
- [ ] Completed Part B code + evaluation + reflection  
- [ ] (Optional) Bonus attempted  
- [ ] Exported `.ipynb`, `.pdf`, `partA_eval_template.csv`, and `partB_eval_template.csv`  
- [ ] Uploaded to Canvas (or designated platform)

---

## 🔒 Academic Integrity

- You may use **internet resources, books, or LLMs/agents**, but you must:  
  - Log usage in the **Reflection** sections.  
  - Critically assess correctness.  
- Copy‑pasting without evaluation will not receive full credit.

---

Good luck 🚀  

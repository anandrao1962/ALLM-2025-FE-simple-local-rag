# 📘 Final Exam – Applications of Large Language Models

**Weight:** 20% • **Duration:** 3 hours • **Format:** Programming (open book/internet; any LLM/agent allowed)  
**Submission:** `.ipynb`, `.pdf`, and two CSVs (Part A & Part B)

---

## Environment
A Colab notebook is provided with the baseline RAG (FAISS + SentenceTransformers + FLAN‑T5). No setup required.

## Dataset
**Title:** *History and Impact of Renewable Energy Technologies* (~2 pages)  
Stored at `exam/dataset/renewable_energy_exam.txt`

## Exam Queries (5)
1) Country + year of first modern wind turbine  
2) Two environmental challenges in the text  
3) How to mitigate wind variability outages (from “Future Trends”)  
4) Summarize pros/cons of solar, wind, hydro (3–4 sentences)  
5) Which tech has highest social/environmental trade-offs and why

---

## Part A — Prompting & Decoding (50)
- Make **two prompt changes** (persona, format, reasoning).  
- Try **two decoding strategies** (temperature/top‑k/top‑p).  
- Compare baseline vs. modified on 5 queries; fill the **Part A table** (1–4 Correctness & Coherence).  
- Write a **3–4 sentence reflection** on tool use.

## Part B — Retrieval & Evaluation (50)
- Choose ONE: change **chunking**, swap **embedding model**, or add **re‑ranking**.  
- Evaluate **Precision/Recall** (context) and **Answer Relevance (1–4)**; fill the **Part B table**.  
- Write a **3–4 sentence reflection** on tool use.

## Optional Bonus (+10) – Agentic Twist
Choose one: Self‑Ask, Plan‑and‑Answer, or Tool‑Selector rule; run on one query; add a short note.

---

## Scoring (per Part = 50)
- Code 20 • Commentary 10 • Evaluation 10 • Reflection 10  
**Total:** 100 (+10 bonus possible)

## Submission Checklist
- [ ] Part A done + table filled  
- [ ] Part B done + table filled  
- [ ] Reflections written  
- [ ] (Optional) Bonus attempted  
- [ ] Exported `.ipynb`, `.pdf`, and both CSVs

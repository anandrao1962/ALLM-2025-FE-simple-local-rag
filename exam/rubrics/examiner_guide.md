# 🎓 Examiner’s Guide – Final Exam

**Course:** Applications of Large Language Models  
**Exam:** Programming Final (3 hours, 20% of grade)  
**Base:** `mrdbourke/simple-local-rag` (Colab version)

---

## 1. Purpose
Assess students’ ability to **apply** prompting/decoding, **modify** retrieval, **evaluate** results, and **reflect** on AI/tool use. This is a capstone integrating Assignments 1–3.

## 2. Setup & Logistics
- Provide a pre-tested Colab notebook with dataset, baseline RAG, empty evaluation tables.  
- Students submit: `.ipynb`, `.pdf`, and two CSVs.  
- Time: 3 hours.

## 3. Sample Baseline Outputs (Typical)
- Q1: “Scotland, 1887.” (Correctness 4, Coherence 4)  
- Q2: “Bird impacts; minerals for solar.” (3,3)  
- Q3: “Energy storage helps.” (3,2)  
- Q4: Short, generic summary (3,3)  
- Q5: “Hydropower due to displacement/ecosystems.” (4,4)

## 4. Expected Student Work
### Part A – Prompt & Decode
- Two prompt edits (persona/format/reasoning) + two decoding strategies.  
- Evaluation table comparing baseline vs. modified across 5 queries.  
- Clear commentary (2–3 sentences per change).

### Part B – Retrieval
- ONE modification: chunking, embeddings, or simple re-rank.  
- Evaluate precision/recall + relevance (1–4), complete table.  
- Short commentary on trade-offs.

### Reflections
- 3–4 sentence notes on tools used, reliability, and corrections made.

## 5. Grading Guide (Per Part = 50)
- **Code** 20: runs and implements required changes.  
- **Commentary** 10: clear rationale.  
- **Evaluation** 10: tables filled with notes.  
- **Reflection** 10: thoughtful, concise tool log.

## 6. Common Pitfalls
- Overly terse notes; incomplete tables; omitted reflections; only cosmetic changes.

## 7. Benchmarks
- **Excellent (90–100):** Fully working, insightful commentary, strong evaluation, thoughtful reflections.  
- **Proficient (80–89):** Minor gaps; generally complete and clear.  
- **Developing (70–79):** Partial implementations; thin commentary; missing entries.  
- **Needs Improvement (<70):** Non-functional; missing components; no reflection.

## 8. Bonus (+10) – Agentic Twist
- Self-Ask / Plan-and-Answer / Tool-Selector rule.  
- Grading: Implementation 5, Commentary 3, Result 2.

# Predicting End-of-Chapter Grades: Impact of Self-Index and Engagement in Online Learning

**Author:** Jinyi Xue  
**Institution:** Department of Statistics, College of Arts and Sciences, Ohio State University  
**Date:** September 2025  

---

## 📘 Overview
This project investigates predictors of student performance in an online statistics and data science platform, **CourseKata**, using **End-of-Chapter (EOC)** correction rates as the primary outcome.  
Data include **engagement metrics** (on-page time, idle time, off-page time) and **self-reported motivational indices** (Intrinsic Value, Utility Value, Cost, Expectancy).  

The analysis focuses on understanding:  
- How self-assessment accuracy relates to performance,  
- How idle time and engagement trends shift across chapters, and  
- Performance differences between students who **completed** all chapters vs. those who did not.

The repository contains:
- `aaFinalCode.Rmd`: Full R Markdown with data wrangling, exploratory graphs, and modeling.  
- `aaFinalCode.html`: Rendered HTML version of the full analysis.  
- `final_poster_Nightingale.pdf`: Concise project poster with finalized results.  
- `checkpoints_eoc.csv`, `checkpoints_pulse.csv`, `page_views.csv`: Core datasets (large file may be omitted).  

---

## 🔍 Key Findings
- **Self-Index strongly predicts grades:** Students who rated their understanding higher performed better overall (β ≈ 0.007, *p* < 0.0001).  
- **Idle time slightly reduces performance:** A small but significant negative effect (*p* ≈ 0.018).  
- **Later chapters are harder:** Scores decline in chapters 9–13 compared to chapters 1–4 (*p* < 0.0001).  
- **Completion matters:** Students completing all chapters consistently scored higher than those who did not (*t*-test *p* ≈ 0.08).  
- Findings support the **Practicing Connections Hypothesis**: deliberate practice across complex problems promotes deeper understanding:contentReference[oaicite:0]{index=0}.

---

## 📂 Repository Structure
Waiver_EOC/
├─ aaFinalCode.Rmd # Main R analysis script
├─ aaFinalCode.html # Rendered HTML report
├─ checkpoints_eoc.csv # EOC assessment data
├─ checkpoints_pulse.csv # Self-report motivation survey
├─ page_views.csv # Clickstream engagement data (>100MB, omitted online)
├─ final_poster_Nightingale.pdf # Poster summary (primary deliverable)

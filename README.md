# 📘 Coursera Courses Metadata Analysis 2025  
*Comprehensive Educational & Data Analytics Study*

---

# 📑 Table of Contents  
1️⃣ [Project Overview](#1️⃣-project-overview)  
2️⃣ [Dataset Workflow](#2️⃣-dataset-workflow)  
3️⃣ [Structured Analysis](#3️⃣-structured-analysis)  
&nbsp;&nbsp;&nbsp;&nbsp;• [Instructor Availability](#instructor-availability)  
&nbsp;&nbsp;&nbsp;&nbsp;• [Skills per Course](#skills-per-course)  
4️⃣ [Key Observations](#4️⃣-key-observations)  
5️⃣ [Pedagogical & Policy Implications](#5️⃣-pedagogical--policy-implications)  
6️⃣ [References](#6️⃣-references)  
📄 [License](#📄-license)  
🙏 [Acknowledgments](#🙏-acknowledgments)

---

# 1️⃣ Project Overview

This project analyzes Coursera courses (2025) with a complete data science workflow, including:

- Dataset cleaning and preprocessing  
- Skills extraction and normalization  
- Instructor–course mapping  
- Category-level analytics  
- Power BI modeling and dashboard structuring  

🎯 **Goal:**  
Understand how online learning platforms (like Coursera) structure *skills*, *instructors*, and *course architecture* — and connect these findings to global educational challenges, especially quality, accessibility, and the need for deep competencies.

---

# 2️⃣ Dataset Workflow

### 📌 Dataset Source
- **Dataset name:** *Coursera Courses Metadata for Data and Learning Analytics (2025)*  
- **Collected by:** *Phi Long Nguyen*  
- **Origin:** Coursera  
- **Hosted on:** Kaggle  
  ➝ https://www.kaggle.com/datasets/phi-long-nguyen/coursera-courses-metadata-2025  

### 🧹 Main Processing Steps  
1. **Import the dataset** (CSV).  
2. **Clean text columns**: remove symbols, fix malformed brackets, standardize lists.  
3. **Explode multi-value fields**:  
   - `skills`  
   - `instructors`  
4. **Create final relational tables**:  
   - `coursera_skills`  
   - `coursera_instructors`  
   - `coursera_data` (course-level summary)  
5. **Prepare for Power BI**:  
   - URL used as primary key  
   - Relationship model  
6. **Export** as clean CSVs for analysis and dashboarding.

---

# 3️⃣ Structured Analysis

## Instructor Availability

### ⭐ **Average instructors per course: 0.79**

| Category                   | Avg Instructors per Course | Difference from Average | Interpretation                           |
|-----------------------------|---------------------------|-----------------------|-----------------------------------------|
| Social Sciences             | 1.50                      | +0.71                 | Strong expert availability              |
| Health                      | 1.14                      | +0.35                 | High and stable                         |
| Business                    | 1.03                      | +0.24                 | Healthy instructor pool                 |
| Arts & Humanities           | 0.82                      | +0.03                 | Close to average                         |
| Physical Science & Eng.     | 0.82                      | +0.03                 | Close to average                         |
| Personal Development        | 0.76                      | −0.03                 | Slightly below average                   |
| Data Science                | 0.64                      | −0.15                 | Low                                      |
| Language Learning           | 0.59                      | −0.20                 | Low                                      |
| Math & Logic                | 0.58                      | −0.21                 | Low                                      |
| Computer Science            | 0.47                      | −0.32                 | Very low                                 |
| Information Technology      | 0.20                      | −0.59                 | Extremely low                            |

---

## Skills per Course

### ⭐ **Average skills per course: 1.67**

| Category                   | Avg Skills per Course | Difference from Average | Interpretation                               |
|-----------------------------|--------------------|------------------------|---------------------------------------------|
| Personal Development        | 2.15               | +0.48                  | Highly multidisciplinary                    |
| Business                    | 2.10               | +0.43                  | Diverse competencies                         |
| Maths & Logic               | 1.91               | +0.24                  | Strong variety                               |
| Social Sciences             | 1.79               | +0.12                  | Slightly above average                       |
| Computer Science            | 1.69               | +0.02                  | Balanced                                     |
| Information Technology      | 1.58               | −0.09                  | Slightly below                               |
| Language Learning           | 1.46               | −0.21                  | Focused                                      |
| Health                      | 1.40               | −0.27                  | Specialized                                  |
| Data Science                | 1.39               | −0.28                  | Specialized                                  |
| Physical Science & Eng.     | 1.29               | −0.38                  | Very focused                                 |
| Arts & Humanities           | 1.25               | −0.42                  | Very low skill variety                       |

---

# 4️⃣ Key Observations

- **Historical fields** (Health, Business, Social Sciences) have many instructors and diverse courses.  
- **Tech fields** (IT, CS, DS) are *specialized* but have *very few instructors*.  
- Courses with many skills do not always align with strong instructor availability.  
- MOOCs democratize education but also reveal **structural imbalances in global expertise availability**.  
- If instructor shortage persists in tech fields, pedagogical depth may decrease.

---

# 5️⃣ Pedagogical & Policy Implications

- Encourage a shift from **diploma accumulation** to **competency-based learning**.  
- Train more **high-quality instructors** in emerging technology domains.  
- Build deep, structured **learning pathways** aligned with job market needs.  
- Aligns with **UN SDG4: Quality Education**  
  → Promoting lifelong learning, instructor professionalization, and equitable access to knowledge.  
- Ensure sustainability of MOOCs by reducing instructor overload.  

---

# 6️⃣ References

- Credential inflation — OUP Academic (2023)  
- Décredentialization — OUP Academic (2023)  
- Skill-based hiring — arXiv (2023)  
- Overeducation — arXiv (2024)  
- MOOCs & labor market — arXiv (2024)  
- Education & technological progress — OECD (2023)

---

# 📄 License

This project is licensed under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**  

**Copyright © 2025  
Sandrine Aboudi**

You are free to:
- **Share** — copy and redistribute the material  
- **Adapt** — remix and build upon it  

As long as:
- You credit the author (Sandrine Aboudi)  
- You don’t use it for commercial purposes  
- You share any derivative content under the same license  

🔗 Full license text: https://creativecommons.org/licenses/by-nc-sa/4.0/

---

# 🙏 Acknowledgments

- **Phi Long Nguyen** — dataset creator (Kaggle)  
- **Coursera** — original course metadata source  
- **Kaggle** — dataset hosting and accessibility  





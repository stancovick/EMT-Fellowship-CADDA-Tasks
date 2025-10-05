# EMT Fellowship CADDA Task 2 – Toxicity Data Exploration

## 📖 Overview
This notebook explores the **Tox21 toxicity dataset** from [DrugDataResource](https://github.com/kexinhuang12345/DrugDataResource).  
It identifies toxicity patterns across assays and highlights compounds with low toxicity, as part of the **EMT Fellowship CADDA program (Group 7)**.

---

## ⚙️ Steps Performed
1. Loaded and cleaned the dataset (removed missing values).  
2. Summarized toxicity outcomes (toxic vs non-toxic per assay).  
3. Visualized patterns using bar charts, heatmaps, and histograms.  
4. Selected compounds that passed all assays (potential safe leads).  

---

## 💡 Key Findings
- Some assays show higher toxicity frequency (harder to pass).  
- Certain assays correlate, indicating related toxicity mechanisms.  
- A small subset of compounds passed all assays — potential safe candidates.  

---

## 🧠 Tools Used
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

---

## ▶️ How to Run
```bash
git clone https://github.com/stancovick/EMT-Fellowship-CADDA-Tasks.git
cd EMT-Fellowship-CADDA-Tasks/EMT-Assignment_Task2
pip install pandas matplotlib seaborn
jupyter notebook Dr_Leah_Task2_toxicity_analysis_final.ipynb




Author: Abonyi, Stanley Arinze (Group 7 Leader)
Mentor: Dr. Leah
Program: EMT Fellowship – Computational Drug Discovery (CADDA)

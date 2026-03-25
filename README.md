## End to End  ML Project

## End to End ML Project

### 🎓 Student Performance — EDA & Feature Engineering

An exploratory data analysis project on the Students Performance in Exams dataset,
uncovering how demographic and socio-economic factors influence academic scores.

---

## 📂 Dataset
- **Source:** [Kaggle — Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Size:** 1,000 rows × 8 columns
- **Features:** Gender, Race/Ethnicity, Parental Education, Lunch Type, Test Prep Course
- **Targets:** Math Score, Reading Score, Writing Score

---

## 📁 Project Structure
```
├── data/
│   └── raw/
│       └── stud.csv
├── notebooks/
│   └── EDA_Student_Performance.ipynb
└── README.md
```

---

## 📊 Notebook Contents
1. Problem Statement
2. Basic Data Inspection
3. Univariate Analysis
4. Bivariate Analysis
5. Multivariate Analysis
6. Outlier Detection
7. Feature Engineering
8. Key Insights & Conclusions

---

## 💡 Key Findings
- Students on **standard lunch** significantly outperform those on free/reduced lunch
- **Test preparation course** completion positively impacts all three scores
- **Parental education level** is a strong predictor — higher education → higher scores
- **Reading and writing scores** are highly correlated (~0.95) and move together

---

## 🛠️ Tech Stack
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn

---

## ▶️ How to Run
```bash
git clone https://github.com/Someshrawat9/ML_Project.git
cd ML_Project
pip install -r requirements.txt
jupyter notebook notebooks/EDA_Student_Performance.ipynb
```

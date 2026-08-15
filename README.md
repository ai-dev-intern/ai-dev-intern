<h1 align="center">Hi there 👋, I'm Eshanth T</h1>

<p align="center">
  <b>Data Analytics · Machine Learning · B.Tech AI &amp; DS Student</b>
</p>

<h3 align="center">I clean messy data and prove what it can — and can't — predict</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ai-dev-intern&style=flat-square&color=0A66C2&label=Profile+Views" alt="profile views"/>
  <img src="https://img.shields.io/github/followers/ai-dev-intern?style=flat-square&color=0A66C2&logo=github&label=Followers" alt="followers"/>
  <img src="https://img.shields.io/badge/Based%20in-Coimbatore,%20India-0A66C2?style=flat-square" alt="location"/>
</p>

---

## 🚀 About Me

- 🎓 **B.Tech, Artificial Intelligence & Data Science (2025–29)**
- 📊 I work across the whole data path — **profiling → cleaning → feature engineering → modelling → reporting**
- 🐍 Python is my main tool: pandas, NumPy, scikit-learn, SciPy
- 🔍 I care about **honest analysis**. If a dataset has no signal, I say so and show the evidence rather than shipping an inflated score
- 🧩 Practising DSA daily on LeetCode & HackerRank
- 🤝 Comfortable in team repos — branching, reviews, and Git-based workflows
- 📍 Coimbatore, India

---

## 🔭 What I'm Working On

```text
▸ Forecasting pipelines      building supply-chain and retail demand models
▸ Data quality tooling       reusable profiling + leakage-detection checks
▸ Streamlit dashboards       turning analysis into something people can click
▸ DSA                        consistent daily practice, Python
```

---

## 🌐 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/eshanth-t-044ab2381/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://leetcode.com/u/AI_Dev_Intern/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="https://www.hackerrank.com/profile/AI_Dev_Intern" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" alt="HackerRank"/>
  </a>
  <a href="mailto:eshanththirmoorthy@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

---

## 💻 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Data & ML**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)

**Apps & Interfaces**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,sklearn,js,react,nodejs,sqlite,git,github,vscode&theme=dark" alt="tech stack icons"/>
</p>

---

## 📌 Featured Projects

### 📉 [Nike Sales — Cleaning & Preprocessing Pipeline](https://github.com/ai-dev-intern/nike-sales-cleaning) &nbsp; `solo`

A 14-step auditable pipeline over 2,500 messy retail rows — and a diagnostic report
that concludes the dataset **cannot support a predictive model**, with the evidence to back it.

- Caught that `Revenue` was a **derived column** (`Units × MRP × (1 − Discount)`, exact on 207/207 rows) — textbook target leakage
- Proved `Profit` carries no signal: correlations ≈ 0.00, ANOVA p = 0.23–0.89 across every categorical
- Resolved three mixed date formats, split a column holding two measurement systems, canonicalised 9 spellings into 6 cities
- Diagnosed missingness as **MCAR**, then quantified impute-vs-complete-cases as a sensitivity analysis

`Python` `pandas` `NumPy` `scikit-learn` `SciPy`

---

### 🚨 [SafeSphere — Public Transport Safety Intelligence](https://github.com/ai-dev-intern/AI-powered-public-transport-safety-intelligence-system) &nbsp; `team of 3`

An AI safety system for passengers travelling by taxi, bus or metro across Coimbatore —
real-time risk detection, wearable heart-rate monitoring, and one-tap SOS.

- Risk-coloured route mapping (green / orange / red) driven by AI risk scores
- Live taxi simulation with danger-zone detection and nearest-police-station lookup
- Heart-rate thresholds that trigger automatic safety responses, audio capture and continuous GPS sharing

`Python` `Streamlit` `Geospatial data` `Sensor integration`

---

### 🧠 [Question Bank Generator](https://github.com/ai-dev-intern/Automated-programming-question-generator) &nbsp; `team`

An LLM-assisted pipeline that scrapes, classifies, enriches and **machine-verifies**
programming interview questions against real test cases, served through a static React portal.

- Offline generation pipeline → verified SQLite store → static JSON export
- Every question validated by executing candidate solutions against generated test cases
- Browsable portal with difficulty filters, company tags, and checkbox-based JSON export

`Python` `Groq LLM API` `SQLite` `React`

---

## 🌱 Currently Learning

![Time Series](https://img.shields.io/badge/Time_Series_Forecasting-0A66C2?style=flat-square)
![Feature Eng](https://img.shields.io/badge/Feature_Engineering-0A66C2?style=flat-square)
![SQL](https://img.shields.io/badge/Advanced_SQL-0A66C2?style=flat-square)
![DSA](https://img.shields.io/badge/DSA_in_Python-0A66C2?style=flat-square)
![MLOps](https://img.shields.io/badge/MLOps_Basics-0A66C2?style=flat-square)

---

## 📈 Activity

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ai-dev-intern&theme=tokyonight&hide_border=true" alt="commit streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ai-dev-intern&theme=tokyo-night&hide_border=true&area=true" alt="contribution graph"/>
</p>

---

<p align="center">
  <i>Always learning, building, and improving. 🚀</i>
</p>

<p align="center">
  <b>Open to internships and collaboration in data analytics & machine learning.</b>
</p>

<p align="center">
  <img src="assets/header.svg" alt="Chetsada Phummee: Data Science, Machine Learning Engineering and Applied AI" width="100%">
</p>

<p align="center">
  <a href="https://chetsada-phu.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-chetsada--phu.github.io-5140be?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="https://linkedin.com/in/chetsada-phummee"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-242236?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:Chetsada.Phummee@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Say%20hi-7d6cd0?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

### Hi, I'm Jayda 👋

I study Economics at Chulalongkorn University (GPA 3.44, graduating November 2027). I analyze data, build and evaluate models, and develop AI applications that support practical decisions. Right now I'm looking for a **Data Science internship** in forecasting, risk modeling or applied ML.

- 💼 AI/ML Engineer Intern at **KBTG**, May to July 2026, building agentic workflows on Databricks
- 🏆 First place in three team hackathons (DOH, PTT Spark Hack and CUNEX)
- 📈 Most of my projects pit a model against a simple baseline on time-ordered splits. I also write down what the numbers don't prove.

---

### 🏆 Hackathon wins

| | Project | What I worked on | Result |
|:-:|---|---|---|
| 🥇 | **CMISSION**<br><sub>DOH Hackathon 2026 · Jul 2026</sub> | YOLO11n black-smoke detection for vehicle emissions | **0.763** test mAP@0.5 on 3,173 images |
| 🥇 | **CatMium**<br><sub>PTT Spark Hack 2025 · Jan 2026</sub> | Engine-sound classification from spectrograms | **93.29%** accuracy, 1,500+ samples |
| 🥇 | **C-Canteen**<br><sub>CUNEX Hackathon (Chula × KBTG) · Apr 2025</sub> | YOLOv8 seat-occupancy detection from canteen CCTV | 31-table pilot scope |

<details>
<summary><b>Project notes and limits</b> (click to open)</summary>
<br>

- **CMISSION:** 3,173 images, 122 FPS on an NVIDIA T4 in the documented setup. The CCTV, microphone-array and edge-hardware screening system was a proposal. It was not deployed.
- **CatMium:** engine audio came from field research with Toyota K. Motors. I used peak detection, RMS windows and Librosa to cut five-second spectrogram samples. The 93.29% comes from a source-recording split in a quiet service-bay proof of concept, so it isn't a validated production diagnostic.
- **C-Canteen:** YOLOv8 instance segmentation with focus-point logic to estimate which of 31 tables were free.

</details>

---

### 🧪 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 📉 [USD/THB Forecasting](https://github.com/chetsada-phu/usd-thb-forecasting)
I compared seven models with rolling evaluation: Random Walk, XGBoost, RNN, LSTM, Transformer, Chronos and TimesFM. The RNN won on validation, then lost to Random Walk on test (RMSE **0.1293 vs 0.1258** over 85 forecasts).

<sub>Python · PyTorch · XGBoost · Hugging Face</sub>

</td>
<td width="50%" valign="top">

#### 🛒 [Retail Sales Forecasting](https://github.com/chetsada-phu/retail-sales-forecasting)
Six approaches, eight expanding-window validation periods, 913,000 sales records. A LightGBM + seasonal blend reached **5.939** mean validation MAE: 45.6% below weekly naive and 3.46% below LightGBM alone.

<sub>Python · pandas · scikit-learn · LightGBM</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🛡️ [Payment Fraud Risk Modeling](https://github.com/chetsada-phu/fintech-fraud-detection)
A fraud-risk pipeline on 5,948 synthetic transactions with chronological splits. XGBoost reached test AP **0.172** against **0.009** for rules, though the test set held only 10 fraud cases. Includes decision thresholds, reason codes and FastAPI scoring.

<sub>Python · scikit-learn · XGBoost · FastAPI</sub>

</td>
<td width="50%" valign="top">

#### 💬 [Text-to-SQL Data Assistant](https://github.com/chetsada-phu/text-to-sql-chatbot)
Ask questions about a CSV in plain language. It loads the file into SQLite, pulls in the relevant schema, writes the SQL and runs it read-only, with query validation and automatic repair.

<sub>Python · Streamlit · SQLite · LLMs</sub>

</td>
</tr>
</table>

---

### 🧰 Toolkit

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-5140be?style=flat-square&logo=python&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-5140be?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="R" src="https://img.shields.io/badge/R-5140be?style=flat-square&logo=r&logoColor=white">
  <img alt="pandas" src="https://img.shields.io/badge/pandas-7d6cd0?style=flat-square&logo=pandas&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-7d6cd0?style=flat-square&logo=scikitlearn&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-7d6cd0?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-7d6cd0?style=flat-square&logo=tensorflow&logoColor=white">
  <img alt="XGBoost" src="https://img.shields.io/badge/XGBoost-7d6cd0?style=flat-square">
  <img alt="LightGBM" src="https://img.shields.io/badge/LightGBM-7d6cd0?style=flat-square">
  <img alt="Databricks" src="https://img.shields.io/badge/Databricks-242236?style=flat-square&logo=databricks&logoColor=white">
  <img alt="MLflow" src="https://img.shields.io/badge/MLflow-242236?style=flat-square&logo=mlflow&logoColor=white">
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-242236?style=flat-square&logo=langchain&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-242236?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-242236?style=flat-square&logo=powerbi&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-242236?style=flat-square&logo=git&logoColor=white">
</p>

---

### 🐍 Watch the snake eat my contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chetsada-phu/chetsada-phu/output/snake-dark.svg">
  <img alt="A snake animation eating Chetsada's GitHub contribution graph" src="https://raw.githubusercontent.com/chetsada-phu/chetsada-phu/output/snake.svg">
</picture>

<p align="center"><sub>question → evidence → decision</sub></p>

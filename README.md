<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=3000&pause=900&color=2E8B57&center=true&vCenter=true&width=750&lines=Smart+Outcome+Predictor;Ensemble+Learning+for+EdTech+Analytics;Bagging+%2B+Boosting+%2B+Voting+%2B+Stacking;Dual-Task%3A+Classification+%26+Regression" alt="Typing SVG" />

<br>

![Project Banner](https://capsule-render.vercel.app/api?type=waving&color=0:1B5E20,100:2E8B57&height=200&section=header&text=Smart%20Outcome%20Predictor&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Predicting%20Student%20Success%20with%20Ensemble%20Machine%20Learning&descAlignY=58&descAlign=50)

<br>

[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=checkmarx&logoColor=white)](#)
[![Model](https://img.shields.io/badge/Final%20Model-Stacking%20Ensemble-2E8B57?style=for-the-badge&logo=scikitlearn&logoColor=white)](#)
[![Domain](https://img.shields.io/badge/Domain-EdTech%20Analytics-1B5E20?style=for-the-badge&logo=googlescholar&logoColor=white)](#)
[![Type](https://img.shields.io/badge/Type-Classification%20%2B%20Regression-6B6B6B?style=for-the-badge)](#)

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC1C24?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

<br>

## 🎯 About the Project

> An **ensemble-powered machine learning system** built for an EdTech analytics platform to solve two problems at once: predicting **whether a student will complete a course**, and forecasting **what score they'll finish with**.

This project takes on the role of a **Machine Learning Engineer at an EdTech company**, where single models were producing unstable, unreliable results. The brief was clear — stop relying on one model, and build a system that combines the strengths of *many* models to get accuracy and stability that a lone algorithm simply can't match.

<div align="center">

```
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
   Classification Target — Course Completion
   62.5% Not Completed ████████████████████░░░░
   37.5% Completed      ████████████░░░░░░░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

</div>

<br>

## ✨ Highlights

<table>
<tr>
<td width="50%" valign="top">

### 🧩 Two Tasks, One Pipeline
- **Classification** → Will the student finish the course?
- **Regression** → What will their final score be?

</td>
<td width="50%" valign="top">

### 🌳 Four Ensemble Families
- **Bagging** → Bootstrap Aggregating
- **Boosting** → AdaBoost, Gradient Boosting, LightGBM, XGBoost
- **Voting** → Hard & Soft strategies
- **Stacking** → Meta-learner combination

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Rigorous Dual Evaluation
- Accuracy, Precision, Recall, F1, ROC-AUC
- MAE, RMSE, R² Score
- Training efficiency benchmarking

</td>
<td width="50%" valign="top">

### 🏢 Deployment-Ready Thinking
- Bias-variance trade-off explained in practice
- Bagging vs Boosting impact compared
- Clear final model recommendation

</td>
</tr>
</table>

<br>

## 🗺️ Project Journey

<div align="center">

| Stage | Focus | Outcome |
|:---:|:---|:---|
| 🧩 **Part A** | Ensemble Theory | Bagging, Boosting, Voting & Stacking explained |
| 📦 **Part B** | Data Preparation | Cleaned, encoded, scaled for both tasks |
| 🌱 **Part C** | Bagging | Bagging vs single Decision Tree |
| 🚀 **Part D** | Boosting | AdaBoost → Gradient Boosting → LightGBM → XGBoost |
| 🗳️ **Part E** | Voting & Stacking | Hard vs Soft Voting, meta-learner Stacking |
| 📈 **Part F** | Model Comparison | Full metrics across all 8 ensemble techniques |
| 📋 **Part G** | Reporting | Trade-offs and final deployment recommendation |

</div>

<br>

## 🔍 The Dataset

<div align="center">

<table>
<tr><th>Category</th><th>Details</th></tr>
<tr><td>👤 Demographics</td><td>Age, Region, Device Type, Education Background</td></tr>
<tr><td>📚 Course Context</td><td>Course Level, Course Category, Days Since Start</td></tr>
<tr><td>⏱️ Engagement Metrics</td><td>Sessions, Time Spent, Videos Watched, Quiz Attempts</td></tr>
<tr><td>📝 Performance Signals</td><td>Assignments Submitted, Forum Posts, Avg Quiz Score, Attendance Rate</td></tr>
<tr><td>🎯 Target (Classification)</td><td><code>Completion Status</code> — Not Completed (0) vs Completed (1)</td></tr>
<tr><td>🎯 Target (Regression)</td><td><code>Final Score</code> — Continuous, 0 to 100</td></tr>
</table>

</div>

<br>

## 🏆 Final Verdict

<div align="center">

### 🧠 Stacking Ensemble — Best for Both Tasks

</div>

> Among all eight ensemble techniques tested, **Stacking** came out on top for **both** the classification task and the regression task — not by accident, but because it doesn't just combine models, it *learns* the best way to combine them.

<div align="center">

| Why Stacking Wins Twice |
|:---|
| 🧠 A meta-learner studies the outputs of multiple base models and learns optimal weighting |
| ⚖️ Balances the strengths of tree-based, linear, and ensemble base models together |
| 🎯 Delivered the highest ROC-AUC for completion prediction |
| 📐 Delivered the highest R² Score for final score prediction |

</div>

<div align="center">

**Gradient Boosting is recommended as a strong, simpler backup — nearly matching Stacking with far less complexity.**

</div>

<br>

## ⚖️ Bagging vs Boosting — The Core Trade-off

<div align="center">

<table>
<tr>
<td align="center" width="50%">

### 🌱 Bagging
**Reduces Variance**
<br>
Many models trained in parallel, predictions averaged to smooth out instability

</td>
<td align="center" width="50%">

### 🚀 Boosting
**Reduces Bias**
<br>
Models trained sequentially, each one correcting the mistakes of the last

</td>
</tr>
</table>

</div>

<div align="center">

**Bagging makes an unstable model reliable. Boosting makes a weak model accurate. This project needed both.**

</div>

<br>

## 🥇 Boosting Family Showdown

<div align="center">

<table>
<tr>
<td align="center" width="25%">

**AdaBoost**
<br>
Reweights hard cases each round

</td>
<td align="center" width="25%">

**Gradient Boosting**
<br>
Corrects residual errors directly — strongest individual performer

</td>
<td align="center" width="25%">

**LightGBM**
<br>
Leaf-wise growth — fastest training, near-identical accuracy

</td>
<td align="center" width="25%">

**XGBoost**
<br>
Built-in regularization — most robust for production scale

</td>
</tr>
</table>

</div>

<br>

## 🧪 Theory Covered

<details>
<summary><b>📖 Click to expand the conceptual foundations explored in this project</b></summary>
<br>

- What ensemble learning is and why combining models outperforms any single model
- The structural differences between Bagging, Boosting, and Voting
- The Bias-Variance trade-off and how different ensemble families address it
- How Voting Classifiers and Stacking Ensembles combine predictions differently
- A conceptual comparison of AdaBoost, Gradient Boosting, LightGBM, and XGBoost

</details>

<br>

## 🛠️ Tech Stack

<div align="center">

![scikit-learn](https://img.shields.io/badge/scikit--learn-Bagging%20%7C%20Boosting%20%7C%20Voting%20%7C%20Stacking-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-EC1C24?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-Fast%20Boosting-02569B?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numeric%20Computing-013243?style=flat-square&logo=numpy&logoColor=white)

</div>

<br>

## 📚 What This Project Demonstrates

<div align="center">

```
✔ Solving classification AND regression from the same feature pipeline
✔ Comparing Bagging vs Boosting with measurable, side-by-side evidence
✔ Benchmarking four boosting algorithms on accuracy and training speed
✔ Understanding when Soft Voting beats Hard Voting, and why
✔ Building a Stacking meta-learner that outperforms every individual model
✔ Recommending a deployment strategy based on performance AND complexity
```

</div>

<br>

## 👨‍💻 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/u/00000000?v=4" width="100" height="100" style="border-radius: 50%;" alt="Author Avatar"/>

### **Ayush Isamaliya**
*Data Science & Aspiring ML Engineer*

</div>

---

### 🌐 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-isamaliya16-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/isamaliya16)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush_isamaliya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-isamaliya-686533312/)

</div>

<br>

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:2E8B57,100:1B5E20&height=120&section=footer)

**Built as part of the Python Data Science track at Red & White Skill Education**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=4000&pause=1500&color=6B6B6B&center=true&vCenter=true&width=500&lines=Thank+you+for+reviewing+this+project!;Star+%E2%AD%90+if+you+found+it+insightful." alt="Footer Typing SVG" />

*Made with ❤️ | PR5 — Smart Outcome Predictor | Ensemble Learning | EdTech Analytics*

</div>

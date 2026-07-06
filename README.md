<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=250&section=header&text=Loan%20Default%20Risk%20Analysis&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Statistics%20|%20Probability%20|%20Linear%20Algebra&descAlignY=60&descSize=18" width="100%"/>
</p>

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white"/>

</p>

<p align="center">

<img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square"/>
<img src="https://img.shields.io/badge/Exam-Practical%20Set%20C-yellow?style=flat-square"/>
<img src="https://img.shields.io/badge/Institute-Red%20%26%20White%20Skill%20Education-red?style=flat-square"/>

</p>

<p align="center">
<a href="https://github.com/Dhairyapatel1mc">
<img src="https://skillicons.dev/icons?i=github" width="50"/>
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/ghost-patel-0267663b7/">
<img src="https://skillicons.dev/icons?i=linkedin" width="50"/>
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://www.instagram.com/ghost_6927/">
<img src="https://skillicons.dev/icons?i=instagram" width="50"/>
</a>
</p>

---
## 📌 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [🎯 Project Objectives](#-project-objectives)
- [🚀 Features](#-features)
- [🔗 Quick Links](#-quick-links)
- [📊 Dataset Attributes](#-dataset-attributes)
- [📁 Project Structure](#-project-structure)
- [🧠 Statistical Concepts Used](#-statistical-concepts-used)
- [🧰 Technologies Used](#-technologies-used)
- [⚙️ Installation](#️-installation)
- [▶️ How to Run](#️-how-to-run)
- [📄 Sample Results](#-sample-results)
- [🎓 Learning Outcomes](#-learning-outcomes)
- [💡 Future Improvements](#-future-improvements)
- [👤 Author](#-author)
- [⭐ Support](#-support)
- [🏆 Final Conclusion](#-final-conclusion)

---

## <a id="-project-overview"></a>🎯 Project Overview

**Loan Default Risk Analysis** applies core statistics, probability, and linear algebra to a bank's loan application data to understand what drives customer default. Working as a data analyst, the task is to explain the underlying statistical concepts in theory — each backed by its own illustrative visual — then apply Python-based analysis to quantify default risk on real data.

The project is split into two parts, matching the original exam structure:

| Part | Focus | Deliverable |
|------|-------|-------------|
| **Part A — Theory** | 5 theory concepts, each with a worked explanation *and* a supporting chart | `Part_A_Theory.pdf` |
| **Part B — Practical** | 4 hands-on steps: Central Tendency & Dispersion, Probability & Events, Distributions & Visualization, Linear Algebra Application | `loan_default_risk_analysis part B.ipynb` |

> 🏫 Prepared for **Red & White Skill Education** — Practical Exam, Set C.
>
> ⚠️ **Note:** `Part_A_Theory.pdf` currently answers Q1–Q5 (Mean/Median/Mode, Variance vs Std Dev, Random Variable, Conditional Probability, Bayes' Theorem). Empirical vs Theoretical Probability, Poisson Distribution, and Eigenvectors are **not yet included** — see [Quick Links](#-quick-links) below.

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-project-objectives"></a>🎯 Project Objectives

- Explain core statistical concepts — mean/median/mode, variance/standard deviation, random variables, conditional probability, and Bayes' theorem — each with a visual, not just text
- Measure the central tendency and spread of customer income and loan amounts
- Calculate the empirical probability of loan default, overall and conditioned on credit score
- Test whether credit score and income follow known distributions
- Represent customers as vectors and apply dot product, norm, and angle calculations to their financial profiles

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-features"></a>🚀 Features

- 📄 A dedicated theory PDF covering 5 core statistical concepts, each with a worked example and chart
- 📓 A practical notebook mirroring the exam's own Step 1–4 structure
- 📊 7 exported chart images from Part B, viewable directly from the `charts/` folder without opening Jupyter
- 🗣️ Every code cell is paired with a plain-English, student-voice markdown explanation
- 🔍 "Interpretation" notes after every graph, tying the math back to loan risk
- 📋 A final summary section consolidating every metric and insight
- 🔁 Fully reproducible — clean and minimal plotting code throughout

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-quick-links"></a>🔗 Quick Links

**Part A — Theory Illustrations** *(from `Part_A_Theory.pdf`)*

| | |
|---|---|
| ✅ [Mean, Median, Mode](Part_A_Theory.pdf#page=1) | ✅ [Variance vs Std Dev](Part_A_Theory.pdf#page=2) |
| ✅ [Random Variable](Part_A_Theory.pdf#page=3) | ✅ [Conditional Probability](Part_A_Theory.pdf#page=4) |
| ✅ [Bayes' Theorem](Part_A_Theory.pdf#page=5) | ⬜ Empirical vs Theoretical *(not yet added)* |
| ⬜ Poisson Distribution *(not yet added)* | ⬜ Eigenvectors *(not yet added)* |

**Part B — Practical Results** *(from `charts/`)*

| | |
|---|---|
| ✅ [Income Distribution](charts/09_income_distribution_mean_median.png) | ✅ [Contingency Heatmap](charts/10_creditscore_default_contingency_heatmap.png) |
| ✅ [Credit Score Gaussian Fit](charts/11_creditscore_gaussian_fit.png) | ✅ [Loan Amount Skew & Kurtosis](charts/12_loan_amount_skew_kurtosis.png) |
| ✅ [Q-Q Plot Income](charts/13_qq_plot_income.png) | ✅ [Customer Vectors](charts/14_customer_vectors_income_loanamount.png) |
| ✅ [Correlation Heatmap](charts/15_correlation_heatmap.png) | |

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-dataset-attributes"></a>📊 Dataset Attributes

| Column | Type | Description |
|--------|------|-------------|
| `Customer_ID` | string | Unique customer identifier |
| `Age` | integer | Customer's age |
| `Income` | float | Annual income |
| `Loan_Amount` | float | Amount of loan applied for |
| `Credit_Score` | integer | Credit score (300–850) |
| `Loan_Term` | integer | Loan repayment term, in months |
| `Default_Status` | categorical | Whether the customer defaulted (Yes/No) |

~5,000 synthetic customer records, generated with a realistic relationship between credit score and default risk.

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-project-structure"></a>📁 Project Structure

```
.
├── README.md                                  # You are here
├── Part_A_Theory.pdf                          # Part A — 5 theory answers with worked examples & charts
├── loan_default_risk_analysis part B.ipynb    # Part B — practical notebook (Steps 1–4)
├── loan_applications.csv                      # Loan applications dataset (~5,000 records)
└── charts/                                    # Exported Part B chart images (PNG)
    ├── 09_income_distribution_mean_median.png
    ├── 10_creditscore_default_contingency_heatmap.png
    ├── 11_creditscore_gaussian_fit.png
    ├── 12_loan_amount_skew_kurtosis.png
    ├── 13_qq_plot_income.png
    ├── 14_customer_vectors_income_loanamount.png
    └── 15_correlation_heatmap.png
```

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-statistical-concepts-used"></a>🧠 Statistical Concepts Used

**Part A — Theory, with Visuals** *(`Part_A_Theory.pdf`)*

1. **Mean, Median, Mode** — A toy customer income array (with one outlier) shows exactly how a single high earner pulls the mean above the median.
2. **Variance vs Standard Deviation** — Loan amount spread is explained in both squared units (variance) and original units (standard deviation).
3. **Random Variable** — Loan Default Status is used as a discrete random variable example from the dataset.
4. **Conditional Probability** — `P(Default | Low Credit Score)` is used to show how conditioning changes a probability.
5. **Bayes' Theorem** — The formula `P(A|B) = [P(B|A) × P(A)] / P(B)` is explained in a banking context.

**Part B — Practical**

- **Step 1** — `.mean()`, `.median()`, `.mode()` on `Income`; range, `.var()`, `.std()` on `Loan_Amount`.
- **Step 2** — Empirical `P(Default)`; `pd.cut()` + `pd.crosstab()` for a Credit_Score × Default_Status contingency table; conditional `P(Default | Credit_Score < 600)`.
- **Step 3** — `scipy.stats.norm.pdf()` Gaussian overlay on Credit_Score; `skew()` / `kurtosis()` on Loan_Amount; `probplot()` Q-Q plot for Income.
- **Step 4** — First 5 customers' `[Income, Loan_Amount]` as vectors; `numpy.dot()`, `numpy.linalg.norm()`, and the angle between two customers' vectors.

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-technologies-used"></a>🧰 Technologies Used

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)

</div>

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-installation"></a>⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/Dhairyapatel1mc/Practical-Exam-Mathematics-Advanced-Statistics-.git
cd Practical-Exam-Mathematics-Advanced-Statistics-

# Install dependencies
pip install numpy pandas matplotlib seaborn scipy jupyter
```

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-how-to-run"></a>▶️ How to Run

1. Make sure `loan_applications.csv` is in the project folder.
2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `loan_default_risk_analysis part B.ipynb`.
4. Run all cells in order (**Cell → Run All**). Later steps reuse variables from earlier ones (e.g. `p_default`, `vectors`), so cells should not be skipped.
5. For Part A theory answers, open `Part_A_Theory.pdf` directly.

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-sample-results"></a>📄 Sample Results

| Task | Metric | Result | Insight |
|---|---|---|---|
| Central Tendency | Income Mean vs Median | Mean > Median | Confirms right-skewed income |
| Dispersion | Loan_Amount Std Dev | High relative to mean | Wide spread in loan sizes across customers |
| Probability | P(Default) | ~17% | Baseline default rate across all customers |
| Conditional Probability | P(Default \| Credit_Score < 600) | ~34% | Low credit score customers default far more often |
| Distribution Fit | Credit_Score vs Normal | Close to Gaussian | Credit scoring is designed to be roughly Normal |
| Skew/Kurtosis | Loan_Amount | Positive skew | Loan sizes are right-skewed with a long tail |
| Normality Check | Income Q-Q Plot | Deviates in upper tail | Income is not Normally distributed |
| Linear Algebra | Customer Vector Angle | Computed per pair | Quantifies similarity of income-to-loan ratio |

*(Exact numeric values are computed live in the notebook and printed under each task.)*

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-learning-outcomes"></a>🎓 Learning Outcomes

- How to turn abstract statistical definitions into concrete, visual intuition before applying them to real data
- How to calculate and interpret mean, median, mode, variance, and standard deviation on real data
- How to compute empirical and conditional probability directly from a dataset
- How to build and read a contingency table for two categorical variables
- How to check a variable's distribution shape using histograms, Gaussian overlays, skewness, kurtosis, and Q-Q plots
- How to represent real-world records as vectors and apply dot product, norm, and angle calculations to them

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-future-improvements"></a>💡 Future Improvements

- Add the missing Part A concepts — Empirical vs Theoretical Probability, Poisson Distribution, and Eigenvectors — to `Part_A_Theory.pdf`
- Build an actual logistic regression model to predict `Default_Status` from the other features
- Apply Bayes' Theorem explicitly to update default probability given multiple risk factors at once
- Add PCA on the numeric features, building on the correlation matrix in Part B
- Validate the Gaussian fit for Credit_Score with a formal normality test (e.g. Shapiro-Wilk)
- Turn the contingency table into a full chi-square test of independence

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-author"></a>👤 Author

<table>
<tr>
<td valign="top">

**Ghost (Patel Dhairya)**

- 🏫 Red and White Skill Education (RWSkill)
- 💻 GitHub — [@Dhairyapatel1mc](https://github.com/Dhairyapatel1mc)
- 💼 LinkedIn — [ghost-patel](https://www.linkedin.com/in/ghost-patel-0267663b7/)
- 📷 Instagram — [@ghost_6927](https://www.instagram.com/ghost_6927/?hl=en)

</td>
<td align="center" valign="middle">

<a href="https://github.com/Dhairyapatel1mc"><img src="https://skillicons.dev/icons?i=github" height="40"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/ghost-patel-0267663b7/"><img src="https://skillicons.dev/icons?i=linkedin" height="40"/></a>
&nbsp;
<a href="https://www.instagram.com/ghost_6927/?hl=en"><img src="https://skillicons.dev/icons?i=instagram" height="40"/></a>

</td>
</tr>
</table>

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-support"></a>⭐ Support

If this project helped you:

- ⭐ **Star** this repository
- 🍴 **Fork** it and adapt it for your own dataset
- 📤 **Share** it with your classmates
- 💬 **Open an Issue** for suggestions or bugs

**[⬆ Back to top](#-table-of-contents)**

---

## <a id="-final-conclusion"></a>🏆 Final Conclusion

Credit score is the clearest driver of loan default risk in this dataset — customers with a credit score below 600 default at roughly double the overall rate, a gap made explicit by comparing conditional and unconditional probability. Both `Income` and `Loan_Amount` are right-skewed rather than Normally distributed, confirmed both visually (histograms, Q-Q plot) and numerically (skewness, kurtosis), which matters for any model that assumes Normality. Representing customers as vectors adds a further lens — beyond raw income or loan size, the *angle* between two customers' vectors captures whether they borrow in a similar proportion to what they earn, a distinction plain averages would miss entirely. Grounding each Part A theory concept in its own visual, before ever touching the real dataset, made every one of these practical results easier to interpret once they appeared.

**[⬆ Back to top](#-table-of-contents)**

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=100&section=footer)

</div>

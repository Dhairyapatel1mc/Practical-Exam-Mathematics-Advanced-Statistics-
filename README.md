

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

| Part | Focus |
|------|-------|
| **Part A — Theory** | 8 theory concepts, each with an expanded explanation *and* a supporting illustrative chart |
| **Part B — Practical** | 4 hands-on steps: Central Tendency & Dispersion, Probability & Events, Distributions & Visualization, Linear Algebra Application |

> 🏫 Prepared for **Red & White Skill Education** — Practical Exam, Set C.

**[⬆ Back to top](#toc)**

---

## <a id="-project-objectives"></a>🎯 Project Objectives

- Explain core statistical concepts — mean/median/mode, variance/standard deviation, random variables, conditional probability, Bayes' theorem, probability types, Poisson distribution, and eigenvalues/eigenvectors — each with a visual, not just text
- Measure the central tendency and spread of customer income and loan amounts
- Calculate the empirical probability of loan default, overall and conditioned on credit score
- Test whether credit score and income follow known distributions
- Represent customers as vectors and apply dot product, norm, and angle calculations to their financial profiles

**[⬆ Back to top](#toc)**

---

## <a id="-features"></a>🚀 Features

- 📓 One structured Jupyter notebook, mirroring the exam's own Part A / Part B / Step 1–4 structure
- 🎨 Every one of Part A's 8 theory concepts is paired with its own illustrative chart, not left as text alone
- 🧮 Every theory concept is also connected forward to the matching hands-on calculation in Part B
- 📊 15 exported chart images in total, so results can be viewed without opening Jupyter
- 🗣️ Every code cell is paired with a plain-English, student-voice markdown explanation
- 🔍 "Interpretation" notes after every graph, tying the math back to loan risk
- 📋 A final summary table consolidating every metric and insight
- 🔁 Fully reproducible — fixed random seed, clean and minimal plotting code throughout

**[⬆ Back to top](#toc)**

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

**[⬆ Back to top](#toc)**

---

## <a id="-project-structure"></a>📁 Project Structure

```
.
├── README.md                              # You are here
├── loan_default_risk_analysis.ipynb       # Main analysis notebook (Part A + Part B)
├── loan_applications.csv                  # Loan applications dataset (~5,000 records)
└── charts/                                # Exported chart images (PNG)
    ├── 01_mean_median_mode.png
    ├── 02_variance_std_dev.png
    ├── 03_random_variable_dice.png
    ├── 04_conditional_probability_venn.png
    ├── 05_bayes_theorem_pipeline.png
    ├── 06_empirical_vs_theoretical_probability.png
    ├── 07_poisson_distribution.png
    ├── 08_eigenvectors_transformation.png
    ├── 09_income_distribution_mean_median.png
    ├── 10_creditscore_default_contingency_heatmap.png
    ├── 11_creditscore_gaussian_fit.png
    ├── 12_loan_amount_skew_kurtosis.png
    ├── 13_qq_plot_income.png
    ├── 14_customer_vectors_income_loanamount.png
    └── 15_correlation_heatmap.png
```

**[⬆ Back to top](#toc)**

---

## <a id="-statistical-concepts-used"></a>🧠 Statistical Concepts Used

**Part A — Theory, with Visuals**

1. **Mean, Median, Mode** — A toy 10-customer income array (with one outlier) is plotted as a sorted bar chart with mean and median lines overlaid, showing exactly how a single high earner pulls the mean above the median.
2. **Variance vs Standard Deviation** — Two synthetic distributions sharing the same mean but very different spread are plotted side by side, making the abstract idea of "spread" visually obvious before it's calculated numerically.
3. **Random Variable** — A fair die roll is used as the simplest possible random variable, plotted as a flat probability bar chart across its 6 equally-likely outcomes.
4. **Conditional Probability** — A two-circle Venn-style diagram (`matplotlib.patches.Circle`) visualizes `P(A|B)` as the overlap region measured only against circle B, not the whole population.
5. **Bayes' Theorem** — Drawn as a left-to-right "pipeline" (prior → evidence → posterior) instead of just the formula, framing it as a belief-updating process a bank could apply per customer.
6. **Empirical vs Theoretical Probability** — A coin-flip simulation at five increasing sample sizes shows the empirical proportion of heads converging toward the true 50% theoretical probability (Law of Large Numbers).
7. **Poisson Distribution** — `scipy.stats.poisson.pmf()` is plotted at three different λ (lambda) values, showing how a single parameter reshapes the whole distribution.
8. **Eigenvalues & Eigenvectors** — A 2×2 matrix is applied to several sample vectors; most rotate under the transformation, but the matrix's actual eigenvectors (found via `numpy.linalg.eig()`) only stretch, never rotate — the geometric definition of an eigenvector, made visible.

**Part B — Practical**

- **Step 1** — `.mean()`, `.median()`, `.mode()` on `Income`; range, `.var()`, `.std()` on `Loan_Amount`.
- **Step 2** — Empirical `P(Default)`; `pd.cut()` + `pd.crosstab()` for a Credit_Score × Default_Status contingency table; conditional `P(Default | Credit_Score < 600)`.
- **Step 3** — `scipy.stats.norm.pdf()` Gaussian overlay on Credit_Score; `skew()` / `kurtosis()` on Loan_Amount; `probplot()` Q-Q plot for Income.
- **Step 4** — First 5 customers' `[Income, Loan_Amount]` as vectors; `numpy.dot()`, `numpy.linalg.norm()`, and the angle between two customers' vectors.

**[⬆ Back to top](#toc)**

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

**[⬆ Back to top](#toc)**

---

## <a id="-installation"></a>⚙️ Installation

```bash
# Clone the repository
git clone <YOUR_REPO_URL>
cd loan-default-risk-analysis

# Install dependencies
pip install numpy pandas matplotlib seaborn scipy jupyter
```

**[⬆ Back to top](#toc)**

---

## <a id="-how-to-run"></a>▶️ How to Run

1. Make sure `loan_applications.csv` is in the project folder.
2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `loan_default_risk_analysis.ipynb`.
4. Run all cells in order (**Cell → Run All**). Later steps reuse variables from earlier ones (e.g. `p_default`, `vectors`), so cells should not be skipped.

**[⬆ Back to top](#toc)**

---

## 📊 Visualizations

| Loan Amount Distribution | Q-Q Plot |
|---|---|
| <img src="charts/Loan Amount Distribution.png" width="450"/> | <img src="charts/Income vs Normal Distribution.png" width="450"/> |

| Income Distribution | Customer Vectors |
|---|---|
| <img src="charts/Income Distribution with Mean & Median.png" width="450"/> | <img src="charts/First 5 Customers as [Income, Loan_Amount] Vectors.png" width="450"/> |

| Credit Score Gaussian Fit | Contingency Table |
|---|---|
| <img src="charts/Credit Score Distribution with Gaussian Curve.png" width="450"/> | <img src="charts/Credit Score Band vs Default Status.png" width="450"/> |

| Correlation Matrix |
|---|
| <img src="charts/Correlation Matrix Numeric Features.png" width="600"/> |
**[⬆ Back to top](#toc)**

---

## <a id="-learning-outcomes"></a>🎓 Learning Outcomes

- How to turn abstract statistical definitions into concrete, visual intuition before applying them to real data
- How to calculate and interpret mean, median, mode, variance, and standard deviation on real data
- How to compute empirical and conditional probability directly from a dataset
- How to build and read a contingency table for two categorical variables
- How to check a variable's distribution shape using histograms, Gaussian overlays, skewness, kurtosis, and Q-Q plots
- How to represent real-world records as vectors and apply dot product, norm, and angle calculations to them
- How to connect linear algebra concepts like eigenvalues back to practical tools like correlation matrices

**[⬆ Back to top](#toc)**

---

## <a id="-future-improvements"></a>💡 Future Improvements

- Build an actual logistic regression model to predict `Default_Status` from the other features
- Apply Bayes' Theorem explicitly to update default probability given multiple risk factors at once
- Add PCA on the numeric features, directly building on the correlation matrix and eigenvalue theory covered in Part A
- Validate the Gaussian fit for Credit_Score with a formal normality test (e.g. Shapiro-Wilk)
- Turn the contingency table into a full chi-square test of independence

**[⬆ Back to top](#toc)**

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

**[⬆ Back to top](#toc)**

---

## <a id="-support"></a>⭐ Support

If this project helped you:

- ⭐ **Star** this repository
- 🍴 **Fork** it and adapt it for your own dataset
- 📤 **Share** it with your classmates
- 💬 **Open an Issue** for suggestions or bugs

**[⬆ Back to top](#toc)**

---

## <a id="-final-conclusion"></a>🏆 Final Conclusion

Credit score is the clearest driver of loan default risk in this dataset — customers with a credit score below 600 default at roughly double the overall rate, a gap made explicit by comparing conditional and unconditional probability. Both `Income` and `Loan_Amount` are right-skewed rather than Normally distributed, confirmed both visually (histograms, Q-Q plot) and numerically (skewness, kurtosis), which matters for any model that assumes Normality. Representing customers as vectors adds a further lens — beyond raw income or loan size, the *angle* between two customers' vectors captures whether they borrow in a similar proportion to what they earn, a distinction plain averages would miss entirely. Grounding each Part A theory concept in its own visual, before ever touching the real dataset, made every one of these practical results easier to interpret once they appeared.

**[⬆ Back to top](#toc)**

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=100&section=footer)

</div>

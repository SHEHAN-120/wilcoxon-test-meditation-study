# Meditation-Based Stress Reduction Program Analysis

This project evaluates the effectiveness of a meditation-based stress reduction program using real-world data. The data represents the number of calm days (without reported anxiety symptoms) over a six-month period for 13 participants after completing the program.

## 🧪 Objective

To determine if the **median number of calm days exceeds 100**, using visual and statistical tools in **R via Google Colab**.

---


## 🔍 Analysis Performed

###  Boxplot & Q-Q Plot

* I used **R in Google Colab** for the entire analysis – it was a great experience integrating R in a Python environment using `rpy2`.
* I drew a **boxplot** to visualize the data distribution and detect outliers.
* I drew a **Q-Q plot** to visually assess normality of the dataset.
* These visual tools helped to **check for normality** before selecting an appropriate test.

###  Interpretation

* The **boxplot** revealed a moderate spread and a few high values, suggesting **right-skewness**.
* The **Q-Q plot** showed deviation from the normal line, especially at the upper tail, indicating the data is **not normally distributed**.

###  Hypothesis Test

I performed a one-sample Wilcoxon signed-rank test with:

* **H₀ (Null Hypothesis):** Median ≤ 100 days
* **H₁ (Alternative Hypothesis):** Median > 100 days

###  Test and Conclusion



## 💻 Tools Used

* **Google Colab** with R using `rpy2`
* **R Programming Language**

  * Visualization: `boxplot()`, `qqnorm()`, `qqline()`
  * Hypothesis testing: `wilcox.test()`
* **Plots were used to check for normality before hypothesis testing.**

---

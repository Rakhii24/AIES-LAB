---

# 🧠 Artificial Intelligence & Ethical Systems (AIES) – Practical Lab Work

This repository showcases hands-on experiments for the **AIES course**, focusing on the core principles of *fairness, bias detection, and transparency* in AI. The aim is to critically analyze how AI models behave with respect to sensitive attributes and to explore approaches that promote ethical AI.

---

## 📘 Experiments Overview

### 🔎 Experiment 1: Identifying Bias in Machine Learning Models

**Goal:**
Examine the presence of bias in predictive models when sensitive features (e.g., gender, age, race) are involved.

**Dataset Example:**

* Synthetic Hiring Data or any dataset with demographic features.

**Steps Performed:**

1. Import and explore the dataset.
2. Preprocess and split into training/testing sets.
3. Train a baseline classifier (Logistic Regression).
4. Evaluate **accuracy** alongside **fairness metrics** (Demographic Parity, Selection Rate).
5. Visualize predictions across groups.

**Outcome:**
Unequal model behavior across demographics (if any) can be identified and quantified.

---

### ⚖️ Experiment 2: Data Quality & Fairness

**Goal:**
Understand how class imbalance in datasets influences fairness in AI outcomes and apply balancing techniques to address it.

**Dataset Example:**

* German Credit Dataset (binary classification).

**Steps Performed:**

1. Load and analyze dataset statistics (`head()`, `describe()`).
2. Train a baseline Logistic Regression model.
3. Assess fairness using the **Fairlearn** toolkit.
4. Handle imbalance using **SMOTE (Synthetic Minority Oversampling)**.
5. Re-train and compare fairness results before vs. after balancing.

**Outcome:**
Fairness improves when imbalance is mitigated, with minimal compromise in performance.

---

### 🌐 Experiment 3: Making AI Transparent

**Goal:**
Explore **explainable AI (XAI)** techniques that clarify how models make predictions, enhancing trust and accountability.

**Dataset Example:**

* Loan Approval dataset or a similar decision-making dataset.

**Steps Performed:**

1. Train models (Decision Tree / Random Forest).
2. Apply **LIME** and **SHAP** to explain predictions.
3. Visualize feature importance and decision pathways.
4. Interpret how explanations help in responsible AI usage.

**Outcome:**
Improved model transparency — users can see *why* predictions are made, not just *what* the output is.

---

## ⚙️ Tools & Libraries

* **Programming Language:** Python 3.x
* **Environment:** Jupyter Notebook / VS Code
* **Key Libraries:**

  * `numpy`, `pandas`, `scikit-learn`
  * `fairlearn`
  * `imbalanced-learn`
  * `matplotlib`, `seaborn`
  * `lime`, `shap`

---

✅ By completing these experiments, we build an understanding of *how fairness, accountability, and transparency* shape ethical AI design.

---



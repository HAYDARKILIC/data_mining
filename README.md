# 🔍 Data Mining

**Artificial Intelligence Engineering — Lecture Notes and Hands-on Notebooks**  
Haydar Kılıç

---

## 📖 About

This repository contains weekly Jupyter Notebooks for the **Data Mining** course. Each notebook is the hands-on Python companion to that week's lecture slides: the theoretical concepts and numerical examples from the slides are reproduced exactly, then generalised and explored further.

**Target audience:** Undergraduate students in Artificial Intelligence Engineering.

---

## 📂 Contents

| Lecture | Topic | Notebook |
|---------|-------|----------|
| Lecture 1 | Classification: Core Concepts and Techniques | [`Lecture1/DMI_Lecture1_Notebook.ipynb`](Lecture1/DMI_Lecture1_Notebook.ipynb) |
| Lecture 2 | *(coming soon)* | — |
| Lecture 3 | *(coming soon)* | — |
| Lecture 4 | *(coming soon)* | — |
| Lecture 5 | *(coming soon)* | — |

---

## 📚 Lecture 1 — Classification: Core Concepts and Techniques

### Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | What is Classification? | `(x, y)` pairs, induction, deduction |
| 2 | Vertebrate Dataset | Real-world example, multi-class → binary conversion |
| 3 | Confusion Matrix | TP, TN, FP, FN; accuracy and error rate formulas |
| 4 | Decision Tree Structure | Root / internal / leaf nodes; `DecisionTreeClassifier` |
| 5 | Hunt's Algorithm | Recursive tree-growing simulation (from scratch) |
| 6 | Attribute Types | Nominal, ordinal, continuous; splitting conditions |
| 7 | Impurity Measures | Entropy, Gini index, classification error; comparison plots |
| 8 | Information Gain & Gain Ratio | `ΔInfo`, split information, the CustomerID trap |
| 9 | Overfitting & Underfitting | Depth–error curve, generalisation error `errgen(T)` |
| 10 | Model Selection & CV | Holdout, k-fold cross-validation, hyperparameter search |
| 11 | Statistical Model Comparison | Confidence interval, effect of sample size |

---

## 🛠️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/<username>/data-mining.git
cd data-mining
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

---

## 📦 Requirements

See [`requirements.txt`](requirements.txt) for the full list.

| Package | Purpose |
|---------|---------|
| `numpy` | Numerical computing, array operations |
| `pandas` | DataFrames, tabular data manipulation |
| `matplotlib` | Visualisation |
| `scikit-learn` | Decision trees, metrics, cross-validation |
| `scipy` | Statistical tests (confidence intervals) |
| `jupyter` | Notebook environment |

---

## 📁 Repository Structure

```
data-mining/
│
├── README.md                              ← This file
├── requirements.txt                       ← Dependencies
│
├── Lecture1/
│   └── DMI_Lecture1_Notebook.ipynb       ← Classification fundamentals
│
├── Lecture2/                              ← (coming soon)
├── Lecture3/                              ← (coming soon)
├── Lecture4/                              ← (coming soon)
└── Lecture5/                              ← (coming soon)
```

---

## 📝 Notes on the Notebooks

- Every notebook is **self-contained** — all datasets are generated within the code; no external files are required.
- Cells must be run **in order**; later cells depend on variables defined in earlier ones.
- All plots are produced with `matplotlib`; no additional rendering libraries are needed.
- Notebooks are tested with Python **3.10+**.

---

## 📖 References

- Tan, P.-N., Steinbach, M., & Kumar, V. (2018). *Introduction to Data Mining* (2nd ed.). Pearson.
- [scikit-learn Decision Tree Documentation](https://scikit-learn.org/stable/modules/tree.html)

---

## 📜 License

These materials are prepared for educational purposes. Free to use with attribution.

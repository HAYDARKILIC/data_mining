# 🔍 Data Mining

**Haydar Kilic | Artificial Intelligence Engineering**

---

## 📖 About

This repository contains Jupyter Notebooks for the **Data Mining** course. Each notebook accompanies the theoretical lecture slides for that as a hands-on Python exercise: the concepts and numerical examples from the slides are reproduced exactly, then generalized and reinforced.

---

## 📂 Contents

| Lecture | Topic | Notebook |
|---------|-------|----------|
| Lecture 1 | Classification: Fundamental Concepts and Techniques | [`Lecture1/DM_Lecture1_Notebook.ipynb`] |
| Lecture 2 | Classification: Advanced Techniques (KNN, NBC, ANN, SVM) | [`Lecture2/DM_Lecture2_Notebook.ipynb`] |
| Lecture 3 | Classification: Advanced Techniques II (ANN, SVM, Bayesian Networks, Ensemble, Imbalance, Metrics) | [`Lecture3/DM_Lecture3_Notebook.ipynb`] |
| Lecture 4 | Association Analysis (Apriori, FP-Growth, GSP, Pattern Evaluation) | [`Lecture4/DM_Lecture4_Notebook.ipynb`] |
| Lecture 5 | Cluster Analysis and Anomaly Detection | [`Lecture5/DM_Lecture5_Notebook.ipynb`] |

---

## 📚 Lecture 1 — Classification: Fundamental Concepts and Techniques

### Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | What is Classification? | `(x, y)` pair, induction, deduction |
| 2 | Vertebrate Dataset | Real-world example, multi-class → binary transformation |
| 3 | Confusion Matrix | TP, TN, FP, FN; accuracy and error rate formulas |
| 4 | Decision Tree Structure | Root / internal / leaf nodes; `DecisionTreeClassifier` |
| 5 | Hunt's Algorithm | Recursive tree-growing simulation (from scratch) |
| 6 | Attribute Types | Nominal, ordinal, continuous; split conditions |
| 7 | Impurity Measures | Entropy, Gini index, classification error; comparison plots |
| 8 | Information Gain & Gain Ratio | `ΔInfo`, split information, CustomerID trap |
| 9 | Overfitting & Underfitting | Depth–error curve, generalization error `errgen(T)` |
| 10 | Model Selection & CV | Holdout, k-fold cross-validation, hyperparameter search |
| 11 | Statistical Model Comparison | Confidence interval, sample size effect |

---

## 📚 Lecture 2 — Classification: Advanced Techniques

### Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | K-Nearest Neighbors (KNN) | Euclidean distance, distance-weighted voting, effect of k |
| 2 | Naive Bayes Classifier (NBC) | Bayes' theorem, conditional independence, Gaussian NBC, Laplace correction |
| 3 | Artificial Neural Networks (ANN) | Perceptron, weight update, XOR problem, vanishing gradient, ReLU |
| 4 | Support Vector Machines (SVM) | Maximum margin hyperplane, support vectors, kernel trick (RBF, Poly, Sigmoid) |
| 5 | Algorithm Comparison | KNN / NBC / MLP / SVM comparison on Breast Cancer & Half-Moon datasets |

---

## 📚 Lecture 3 — Classification: Advanced Techniques II

### Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | ANN In-Depth | Biological neuron analogy, forward propagation, mini-batch gradient descent, backpropagation |
| 2 | SVM (In-Depth) | Dual problem, KKT conditions, kernel trick, feature space transformation φ |
| 3 | Bayesian Networks | DAG structure, local Markov property, CPT, joint distribution, inference |
| 4 | Ensemble Learning | Binomial error analysis, Bias-Variance trade-off, Bagging, Random Forest, AdaBoost |
| 5 | Class Imbalance | Accuracy paradox, unLectureampling, oversampling, SMOTE (from scratch), class weight |
| 6 | Performance Metrics | Confusion matrix, Precision/Recall/F1/Fβ, ROC curve, PR curve, optimal decision threshold, cost matrix |

---

## 📚 Lecture 4 — Association Analysis

### Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | Basic Concepts | Support count σ(X), support s(X), confidence c(X→Y), association rule |
| 2 | Apriori Principle | Anti-monotonicity property, itemset lattice structure, pruning strategy |
| 3 | Apriori Algorithm | candidate-gen (Fₖ×Fₖ join), candidate-prune, support counting (from scratch) |
| 4 | Rule Generation | ap-genrules, confidence anti-monotonicity, Lift calculation |
| 5 | Compact Representation | Maximal frequent itemsets, closed frequent itemsets, hierarchy |
| 6 | FP-Growth | FP-tree (from scratch), header table, conditional FP-tree, mining without candidate generation |
| 7 | Pattern Evaluation | Lift, PS (Piatetsky-Shapiro), φ-correlation, IS (Cosine) measures |
| 8 | Simpson's Paradox | Hidden variables, stratified vs. aggregated analysis, HDTV example |
| 9 | Categorical & Continuous | Conversion to binary form, discretization, bin width effect |
| 10 | Sequence Patterns | GSP algorithm, subsequence testing, web visit sequence example |
| 11 | Rare & Negative Patterns | h-confidence (All-Confidence), cross-support pattern, competitor product analysis |

---

## 📚 Lecture 5 — Cluster Analysis and Anomaly Detection

### Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | Introduction to Cluster Analysis | Unsupervised learning, concept of similarity |
| 2 | K-Means Algorithm | SSE, centroid update, convergence |
| 3 | Initialization | Random vs. K-Means++ |
| 4 | Optimal K | Elbow method, Silhouette analysis |
| 5 | Hierarchical Clustering | Agglomerative clustering, dendrogram |
| 6 | Density-Based Clustering | DBSCAN, epsilon, minPts |
| 7 | Anomaly Detection | Local Outlier Factor (LOF), Z-score |
| 8 | Clustering Evaluation | Silhouette, intra/inter cluster distance |

---

## 🛠️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/HAYDARKILIC/data_mining.git
cd data_mining
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
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
| `numpy` | Numerical computation, array operations |
| `pandas` | DataFrames, tabular operations |
| `matplotlib` | Visualization |
| `scikit-learn` | KNN, NBC, MLP, SVM, Ensemble, metrics, cross-validation |
| `scipy` | Statistical tests, Gaussian density, binomial coefficient |
| `networkx` | Bayesian Network DAG visualization (Lecture 3, optional) |
| `jupyter` | Notebook environment |

> **Note:** Lecture 4 (Association Analysis) uses only standard libraries (`itertools`, `collections`); no additional dependencies are required.

---

## 📁 Repository Structure

```
data_mining/
│
├── README.md
├── requirements.txt
│
├── Lecture1/
│   └── DM_Lecture1_Notebook.ipynb
│
├── Lecture2/
│   └── DM_Lecture2_Notebook.ipynb
│
├── Lecture3/
│   └── DM_Lecture3_Notebook.ipynb
│
├── Lecture4/
│   └── DM_Lecture4_Notebook.ipynb
│
├── Lecture5/
│   └── DM_Lecture5_Notebook.ipynb
```
## 📖 Reference

Tan, P. N., Steinbach, M., & Kumar, V. (2016). Introduction to data mining. Pearson Education India.

---

*Data Mining — Haydar Kılıç, Artificial Intelligence Engineering*

# 🧠 Breast Cancer Classification with Custom ML Algorithms

This project implements and evaluates several classification algorithms from scratch and compares them with their Scikit-learn counterparts on the **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset. The focus is on understanding model fundamentals, performance metrics, and decision boundaries.

---

## 📂 Dataset

* **Source:** UCI Machine Learning Repository – [WDBC dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
* **Features:** 30 real-valued input features computed from digitized images of fine needle aspirates (FNAs).
* **Target:** `Diagnosis` — Malignant (M) or Benign (B)

---

## 🛠️ Implemented Models (from scratch)

1. **Custom Gaussian Naive Bayes (GNB)**
2. **Custom Gaussian Discriminant Analysis (GDA)**
3. **Custom Logistic Regression (using Gradient Descent)**
4. **Custom Perceptron**

---

## ✅ Model Evaluation

Each model is evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**

## 📊 Results Summary

| Model                       | Accuracy | Precision | Recall | F1-Score |
| --------------------------- | -------- | --------- | ------ | -------- |
| Custom GDA                  | 0.947    | 0.929     | 0.929  | 0.929    |
| Sklearn GDA                 | 0.965    | 1.000     | 0.905  | 0.950    |
| Custom GNB                  | 0.921    | 0.923     | 0.857  | 0.889    |
| Sklearn GNB                 | 0.921    | 0.923     | 0.857  | 0.889    |
| Custom Logistic Regression  | 0.982    | 1.000     | 0.952  | 0.976    |
| Sklearn Logistic Regression | 0.974    | 0.976     | 0.952  | 0.964    |
| Custom Perceptron           | 0.912    | 0.881     | 0.881  | 0.881    |
| Sklearn Perceptron          | 0.965    | 0.952     | 0.952  | 0.952    |

---

## 📉 Visualizations

* **PCA Projection** to visualize class separation
* **Decision Boundary Plots** for each classifier (2D after PCA)
* **SVM Linear Kernel** test for linear separability

---

## 🧪 Key Learnings

* Custom implementations enhance understanding of core ML concepts like likelihood, decision boundaries, and optimization.
* Scikit-learn models outperform in efficiency and sometimes in accuracy, due to optimized internals.
* Logistic Regression and GDA performed best overall in this setting.
* PCA and SVM were used to assess linear separability of the classes.

---

## 🧰 Tech Stack

* Python 3.x
* Pandas, NumPy, Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

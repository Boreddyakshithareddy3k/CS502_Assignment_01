# 🌸 Iris Dataset Classification using PCA + Logistic Regression

This project demonstrates **dimensionality reduction** using **Principal Component Analysis (PCA)** combined with **Logistic Regression** for classification on the famous **Iris dataset**.

---

## 1. 📖 Introduction
The **Iris dataset** is one of the most widely used datasets in machine learning, containing **150 samples** across three species of Iris flowers:  
- *Setosa*  
- *Versicolor*  
- *Virginica*  

Each flower is described using **4 features**:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

The main objective of this project is to:  
- Reduce the **feature space (4D → 2D)** using PCA  
- Classify flowers using **Logistic Regression**  
- Evaluate performance using **Confusion Matrix** and **Classification Report**

---

## 2. ⚙️ Methodology

**Step 1: Data Preprocessing**  
- Standardized features using `StandardScaler`.

**Step 2: Principal Component Analysis (PCA)**  
- Reduced 4 features into 2 principal components.  
- Captured maximum variance in the dataset.  

**Step 3: Logistic Regression**  
- Supervised classification algorithm.  
- Used sigmoid function for probability predictions.  

**Step 4: Evaluation**  
- Assessed performance using Confusion Matrix and Classification Report.

---

## 3. 💻 Code Implementation
The implementation was done in **Python** using:  
- `numpy`, `pandas` → Data handling  
- `scikit-learn` → PCA, Logistic Regression, Evaluation  
- `matplotlib` → Visualization  

📂 Refer to **`code.ipynb`** for the full code.  

---

## 4. 📊 Results

- **Confusion Matrix Analysis**  
  - Diagonal elements = correctly classified samples  
  - Off-diagonal = misclassifications  

- **Performance**  
  - *Setosa*: 100% accuracy  
  - *Versicolor & Virginica*: a few misclassifications  
  - **Overall accuracy ~96%**  

---

## 5. ✅ Conclusion
This project demonstrates that:  
- **PCA** reduces dataset complexity while retaining important variance.  
- **Logistic Regression** is effective for multi-class classification.  
- Combined, they provide strong results with **~96% accuracy** on the Iris dataset.  

---









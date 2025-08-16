# Support Vector Machine (SVM) Classification  

## 📌 Objective  
Implement and understand **Support Vector Machines (SVM)** for classification problems using Python’s Scikit-learn library.  
Visualize **decision boundaries**, explore the **kernel trick**,  **margin maximization**,and perform **hyperparameter tuning**.  

---

## 🛠 Tools & Libraries Used  
- **Python 3.x**  
- **Pandas** – Data handling  
- **NumPy** – Numerical operations  
- **Scikit-learn** – SVM model, scaling, and evaluation  
- **Matplotlib** – Plotting and visualizations  

---

## 📁 Dataset  
We use the **Breast Cancer dataset** (built-in from 'sklearn.datasets'6).  

- **Features**: cell radius, texture, smoothness, compactness, etc.  
- **Target**: Tumor type  
  - '0' = Malignant  
  - '1' = Benign  

---

## 📖 Steps to Run the Project  

### 1️⃣ Load & Explore Dataset  
- Use 'load_breast_cancer()' from 'sklearn'  
- Check dataset shape, feature names, and target values  

### 2️⃣ Data Preprocessing  
- Select features ('radius_mean', 'texture_mean') for 2D visualization  
- Normalize features using 'StandardScaler'  

### 3️⃣ Train the Model  
- Create an 'SVC' object (Support Vector Classifier)  
- Try different kernels: 'linear', 'rbf', 'poly'  

### 4️⃣ Margin Maximization  
- Visualize **support vectors** and the **maximum margin** between classes  

### 5️⃣ Kernel Trick  
- Show how **RBF kernel** creates non-linear decision boundaries  

### 6️⃣ Hyperparameter Tuning  
- Use 'GridSearchCV' to find best values for 'C' and 'gamma'  

### 7️⃣ Evaluate Model  
- Calculate **Accuracy, Precision, Recall, F1-score**  
- Display **Confusion Matrix**  

### 8️⃣ Visualize Decision Boundaries  
- Create meshgrid for feature space  
- Plot decision regions and support vectors  

---

## 📊 Example Accuracy Output  
| Kernel  | Accuracy | Best Params (C, γ) |
|---------|----------|---------------------|
| Linear  | 96.49%   | C=1                 |
| RBF     | 98.24%   | C=10, γ=0.01        |
| Poly    | 94.73%   | C=1, degree=3       |  

---

## 🎨 Decision Boundary Example  
A plot showing:  
- Decision regions (colored areas)  
- Training points (circles)  
- Test points (crosses)  
- Support vectors (highlighted)  

---


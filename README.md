# Decision Trees and Random Forests

This project explores **tree-based models** for classification using the **Heart Disease Dataset**.

## 📌 Objective
- Learn how **Decision Trees** and **Random Forests** work.
- Understand model interpretability and overfitting.
- Compare single decision trees with ensemble learning methods.
- Evaluate models using cross-validation.

---

## 🛠️ Tools Used
- **Python 3**
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/)

---
## 🚀 Steps in the Notebook
1. **Load Dataset**  
   - Heart disease dataset with 1,025 samples and 14 columns.
   - `target` column = 1 (disease), 0 (no disease).

2. **Train a Decision Tree Classifier**  
   - Fit a decision tree on training data.  
   - Visualize the tree using `plot_tree`.  

3. **Overfitting Analysis**  
   - Train trees with different `max_depth`.  
   - Compare **train vs test accuracy** to detect overfitting.  

4. **Train a Random Forest Classifier**  
   - Use 100 trees for better generalization.  
   - Compare accuracy with Decision Tree.  

5. **Feature Importances**  
   - Extract and plot feature importance scores.  
   - Identify key features driving predictions.  

6. **Cross-validation**  
   - Perform **5-fold cross-validation**.  
   - Report mean accuracy across folds.  

---

## 📊 Example Results
- **Decision Tree Accuracy:** ~75% (may vary by depth).  
- **Random Forest Accuracy:** ~83%.  
- **Important Features:** `cp` (chest pain), `thalach` (max heart rate), `oldpeak`, etc.  

---

## ▶️ How to Run
1. Clone/download this repository.  
2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn matplotlib

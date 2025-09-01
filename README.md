## 🍄Mushroom Classification

This project classifies mushrooms as **edible** or **poisonous** using machine learning models.  

---

## 📂 Dataset
The dataset contains mushroom attributes such as:
- Cap shape, surface, and color  
- Odor, gill size, gill color  
- Habitat, population, etc.  

Target variable:  
- **Edible (e)** or **Poisonous (p)**

Dataset source: [Mushroom Dataset](https://www.kaggle.com/datasets/uciml/mushroom-classification)

---

## 🚀 Algorithms Used
1. **Logistic Regression**  
2. **Decision Tree Classifier**  
3. **Random Forest Classifier**  

---

## ⚙️ Steps
1. Preprocess categorical features using Label Encoding  
2. Train-test split  
3. Train Logistic Regression, Decision Tree, Random Forest  
4. Evaluate with:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix  

---

## 📊 Results
- Logistic Regression: Good baseline performance  
- Decision Tree: Highly interpretable rules  
- Random Forest: Achieved **near 100% accuracy** on test data  

---

## 📌 Requirements
Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

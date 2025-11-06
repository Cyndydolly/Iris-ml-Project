# 🌸 Iris Flower Classification — Machine Learning Project

This project applies **machine learning** to classify *Iris flowers* into their respective species using the **Iris dataset**.  
It’s a beginner-friendly but powerful example of supervised learning with clear visualization and perfect model performance.

## 📊 **Project Overview**

The Iris dataset contains 150 samples of flowers with four measured features:

- 🌿 **Sepal length**
- 🌿 **Sepal width**
- 🌸 **Petal length**
- 🌸 **Petal width**

Each flower belongs to one of three species:
- *Iris-setosa*
- *Iris-versicolor*
- *Iris-virginica*

The goal is to predict the species based on the flower measurements.

---

## 🧠 **Tech Stack**

- **Python 3**
- **Pandas** — Data analysis  
- **Matplotlib & Seaborn** — Visualization  
- **Scikit-learn** — Machine learning (Decision Tree Classifier)
- **Jupyter Notebook** — Interactive development

---

## ⚙️ **Model Workflow**

1. **Data Loading**  
   Imported the Iris dataset (`IRIS.csv`) into a pandas DataFrame.  

2. **Data Exploration**  
   Viewed data summary, statistics, and feature relationships.  

3. **Visualization**  
   - Pair plots using Seaborn to observe separability between species.  
   - Confusion matrix and feature importance plots after model training.  

4. **Model Training**  
   - Split dataset into 80% training and 20% testing data.  
   - Used a **Decision Tree Classifier** for prediction.  

5. **Evaluation**  
   Achieved **100% accuracy**, with perfect precision, recall, and F1-score across all classes.

---

## 📈 **Results**

| Metric      | Score |
|--------------|--------|
| Accuracy     | 1.00 |
| Precision    | 1.00 |
| Recall       | 1.00 |
| F1-score     | 1.00 |

**Confusion Matrix:** All predictions were correct (perfect diagonal).  
**Top Features:** Petal length and petal width had the highest importance.

## 🎨 **Visualizations**

- 🌿 *Pairplot* showing species separation  
- 🔢 *Confusion Matrix* heatmap  
- 📊 *Feature Importance* bar chart  

   git clone https://github.com/yourusername/iris-ml-project.git
   cd iris-ml-project

# Breast Cancer Analysis & Prediction Project 🎗️

This project analyzes the **Breast Cancer Wisconsin** dataset using supervised machine learning techniques. The primary objective is to assist medical diagnosis by predicting tumor characteristics and classifying them as malignant or benign.

## 👥 Project Team
* **Batuhan İNAN**
* **Emir İnanç ŞEKER**

## 🎯 Project Objectives
The project focuses on two main machine learning tasks:
1.  **Regression Analysis:** Predicting the tumor radius (`radius_mean`) based on other physical features (Texture, Smoothness, Compactness, etc.).
2.  **Classification Analysis:** Diagnosing the tumor as **Malignant (M)** or **Benign (B)**.

## 🛠️ Technologies & Libraries
* **Python 3.x**
* **Pandas & NumPy:** For data cleaning, manipulation, and preprocessing.
* **Matplotlib & Seaborn:** For exploratory data analysis (EDA) and visualization.
* **Scikit-learn:** For building and evaluating machine learning models (Regression & Classification).

## 📊 Methodology & Models

### 1. Classification Task
To determine whether a tumor is malignant, we implemented and compared three different algorithms using **5-Fold Cross-Validation** to ensure reliability:

| Model | Accuracy Score | Observations |
|-------|----------------|--------------|
| **Logistic Regression** | ~94% | Served as a strong baseline; easy to interpret. |
| **Decision Tree** | ~91% | Showed high variance; prone to overfitting without pruning. |
| **Random Forest** | **~96%** | **Best Performance.** Successfully captured non-linear relationships and complex feature interactions. |

### 2. Regression Task
* **Target:** `radius_mean`
* **Algorithm:** Linear Regression
* **Features Used:** Texture, Smoothness, Compactness, Concavity, Symmetry.
* **Metric:** Mean Squared Error (MSE) and R² Score.

## 🚀 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ahvcxa/Breast-Cancer-Prediction.git](https://github.com/ahvcxa/Breast-Cancer-Prediction.git)
    cd Breast-Cancer-Prediction
    ```

2.  **Install required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook ML_Regression_Classification.ipynb
    ```

## 📝 Conclusion
Based on our analysis, the **Random Forest** classifier proved to be the most reliable model for this dataset, achieving over 95% accuracy. While Logistic Regression provided good interpretability regarding feature importance, the Random Forest algorithm's ability to handle the complexity of biological data made it the superior choice for clinical diagnostic support in this context.

---
*This project was developed as part of the Introduction to Machine Learning course.*

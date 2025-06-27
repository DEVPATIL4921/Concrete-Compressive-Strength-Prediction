# 🧱 Modeling of High-Performance Concrete Strength using Artificial Neural Networks

This project focuses on predicting the **compressive strength** of concrete using **Artificial Neural Networks (ANNs)**. It is based on the Concrete Compressive Strength dataset from the UCI Machine Learning Repository.

---

## 📄 Overview

- 📊 **Type**: Regression
- 🧪 **Samples**: 1030
- 📈 **Features**: 8 input features + 1 target variable (Compressive Strength)
- 🏗️ **Domain**: Civil Engineering, Construction Materials

The goal is to build a neural network model that can learn the nonlinear relationships between the ingredients and the resulting concrete strength.

---

## 📁 Dataset Information

📌 **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength)

| Column               | Description                         | Unit   |
|----------------------|-------------------------------------|--------|
| Cement               | Cement component                    | kg/m³  |
| Blast Furnace Slag   | Blast furnace slag component        | kg/m³  |
| Fly Ash              | Fly ash component                   | kg/m³  |
| Water                | Water component                     | kg/m³  |
| Superplasticizer     | Superplasticizer additive           | kg/m³  |
| Coarse Aggregate     | Coarse aggregate component          | kg/m³  |
| Fine Aggregate       | Fine aggregate component            | kg/m³  |
| Age                  | Age of concrete samples             | Days   |
| Compressive Strength | **Target**: Strength of concrete    | MPa    |

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

## 📊 Modeling Approach

- **Data Preprocessing**:
  - Handled scaling (Standard, MinMax, Robust, Power)
  - Train/Test split
  - Normality tests and correlation analysis
- **Model**: Artificial Neural Network (ANN)
  - Layers: Dense, Dropout
  - Optimized using Keras
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score

---

## 📈 Results

*(Insert your model results here)*  
Example:

| Metric       | Value    |
|--------------|----------|
| R² Score     | 0.89     |
| MSE          | 18.34    |
| MAE          | 2.97     |

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/concrete-strength-ann.git
cd concrete-strength-ann
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook MODELING_OF_HIGH_PERFORMANCE_CONCRETE.ipynb
```

---

## 📚 Citation

> Yeh, I-C. "Modeling of Strength of High-Performance Concrete Using Artificial Neural Networks." *Cement and Concrete Research*, Vol. 28, No. 12, pp. 1797-1808, 1998.

---

## 📬 Contact

Devesh Pandurang Patil  
📧 devesh.patil@email.com  
🔗 [LinkedIn](https://linkedin.com/in/your-profile)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
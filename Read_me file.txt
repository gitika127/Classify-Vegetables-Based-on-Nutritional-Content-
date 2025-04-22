# Vegetable Classification Based on Nutritional Content

## 📌 Project Overview
This project uses machine learning to classify vegetables into categories like **leafy**, **root**, and others based on their **nutritional values** – specifically **vitamin A**, **vitamin C**, and **fiber**. The classification helps in understanding health benefits and can aid in nutrition planning and agricultural applications.

---

## 🎯 Objective
- To classify vegetables based on their nutrient composition using supervised learning.
- To train and evaluate a model using features: vitamin A, vitamin C, and fiber.
- To predict the vegetable category for new nutritional input data.

---

## 🧠 Methodology
1. **Data Preprocessing**:
   - Missing values are removed.
   - Target labels are encoded using `LabelEncoder`.
   - Feature scaling is applied using `StandardScaler`.

2. **Model Training**:
   - Data is split into training and test sets (80/20).
   - A `RandomForestClassifier` is trained on the dataset.

3. **Model Evaluation**:
   - Evaluated using Accuracy, Precision, Recall.
   - Confusion Matrix and Feature Importance graphs are plotted.

4. **Prediction**:
   - The model predicts the type of vegetable based on custom user input (vitamin values).

---

## 🧪 Results
- **Accuracy**: ~92%
- **Precision**: ~91%
- **Recall**: ~90%
- **Feature Importance**:
  - Vitamin A and Vitamin C were the most significant features.
- **Prediction**:
  - Given a user input (e.g., `vitamin_a: 8000`, `vitamin_c: 25`, `fiber: 2.5`), the model successfully predicts the vegetable type.

---

## 📊 Visualization
- Confusion Matrix Heatmap: Shows classification performance across actual vs predicted labels.
- Feature Importance Chart: Displays how much each nutrient contributes to the model’s decision-making.

---

## 🧾 Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

Install dependencies using:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib

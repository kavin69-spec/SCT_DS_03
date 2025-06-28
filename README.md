# 🌳 Decision Tree Classifier for Customer Purchase Prediction

This project leverages a **Decision Tree classifier** to predict whether a customer will purchase a product or service based on their **demographic** and **behavioral data**. The model is built using Python and visualized with the help of `sklearn.tree`.

---

## 🎯 Objective

Predict customer purchasing behavior using classification techniques. This can help businesses in:
- **Targeted marketing**
- **Customer segmentation**
- **Conversion optimization**

---

## 📊 Dataset

The dataset contains features such as:
- Age
- Job
- Marital status
- Education
- Default status
- Balance
- Contact type
- Day, Month
- Duration
- Campaign
- Previous marketing outcomes
- And more...

> *Target variable:* `y` (1 if customer subscribed, 0 otherwise)

---

## 🛠️ Technologies Used

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)

---

## 🔍 Workflow

1. **Data Preprocessing**
   - Encoding categorical variables
   - Handling missing values
   - Feature scaling (if needed)

2. **Model Building**
   - Using `DecisionTreeClassifier` from `sklearn.tree`
   - Training/testing data split using `train_test_split`

3. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report (Precision, Recall, F1-score)

4. **Visualization**
   - Decision tree plotted using `plot_tree()`

---

## 📈 Results

### ✅ Classification Report (Sample)

# 🌳  Mushroom Edibility Classifier  

## 📌 Project Overview

This project is a **Machine Learning model** that predicts whether a mushroom is **edible or poisonous** based on its features.

It uses a **Decision Tree Classifier** along with data preprocessing and evaluation techniques.

---

## 🚀 Features

* Data preprocessing using **Label Encoding**
* Exploratory Data Analysis (EDA)
* Train-Test Split
* Decision Tree model training
* Model evaluation using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report
* Model visualization
* Model saving using `joblib`

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Graphviz

---

## 📂 Dataset

The dataset contains various mushroom characteristics such as:

* Cap shape
* Color
* Odor
* Habitat
* And more...

Target variable:

* `class` → Edible or Poisonous

---

## ⚙️ How It Works

1. **Load Dataset**

   ```python
   df = pd.read_csv("dataset.csv")
   ```

2. **Preprocessing**

   * Convert categorical values using Label Encoding

3. **Split Data**

   ```python
   train_test_split()
   ```

4. **Train Model**

   ```python
   DecisionTreeClassifier()
   ```

5. **Evaluate Model**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

6. **Visualize Tree**

   * Using Graphviz

---

## 📊 Output

* Accuracy of the model
* Confusion matrix visualization
* Decision tree structure

---

## 💾 Model Saving

The trained model is saved using:

```python
joblib.dump(model, "mushroom_model.pkl")
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/mushroom-classifier.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn graphviz joblib
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📈 Future Improvements

* Try other models (Random Forest, SVM)
* Hyperparameter tuning
* Deploy as a web app (Flask/Streamlit)

---

## 🙌 Author

Your Name

---

## ⭐ If you like this project

Give it a star on GitHub!


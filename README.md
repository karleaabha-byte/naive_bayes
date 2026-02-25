
# 🧠 Naive Bayes Classifier Web App

An interactive **Machine Learning web application** built using **Streamlit** and **Scikit-Learn**.

This app allows users to upload any CSV dataset, select a target column, train a **Gaussian Naive Bayes classifier**, and evaluate model performance.

---

## 🚀 Features

- 📂 Upload any CSV dataset  
- 🎯 Select target column dynamically  
- 📊 Adjustable train-test split  
- 🧠 Gaussian Naive Bayes model training  
- ✅ Accuracy score display  
- 🔎 Confusion matrix visualization  
- 📈 Scatter plot (for 2 selected features)  

---

## 📊 How It Works

1. Upload a dataset (CSV format)  
2. Select the target column  
3. Choose test size percentage  
4. Train the model  
5. View performance metrics and visualizations  

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/naive-bayes-streamlit-classifier.git
cd naive-bayes-streamlit-classifier
````

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
```

Activate environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the app

```bash
streamlit run app1.py
```

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```
streamlit
pandas
numpy
scikit-learn
matplotlib
seaborn
```

---

## 🧠 Model Used

**Gaussian Naive Bayes** (from Scikit-Learn)

Best suited for:

* Multi-class classification
* Continuous features
* Educational ML demonstrations

---

## 📌 Example Datasets

* Iris Dataset
* Credit Default Dataset
* Any custom classification dataset

---

## 🔮 Future Improvements

* Precision, Recall, F1-Score
* ROC Curve visualization
* Model comparison (Logistic Regression, SVM)
* Cross-validation
* Deployment on Streamlit Cloud

---

## 👨‍💻 Author

Built as a Machine Learning practice and portfolio project.


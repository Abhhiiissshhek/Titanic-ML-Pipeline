# 🚢 Titanic Survival Prediction – End-to-End Machine Learning Pipeline

An end-to-end Machine Learning project that predicts passenger survival on the Titanic using a production-style **Scikit-learn Pipeline**. The project demonstrates the complete ML workflow, including data preprocessing, feature engineering, model training, evaluation, serialization, and inference.

---

# 📌 Overview

The Titanic disaster is one of the most well-known datasets in Machine Learning. This project aims to predict whether a passenger survived based on demographic and travel-related information.

Unlike notebook-only implementations, this project follows a modular software engineering approach by separating preprocessing, training, evaluation, and prediction into reusable components.

---

# ✨ Features

* End-to-end Machine Learning pipeline
* Automated data preprocessing
* Feature engineering using Scikit-learn
* Model training and evaluation
* Model serialization using Joblib
* Modular and maintainable project structure
* Easy inference on new passenger data

---

# 🛠 Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* Joblib
* Matplotlib
* Seaborn

---

# 📂 Project Structure

```text id="eybtmz"
Titanic-ML-Pipeline/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── models/
│   └── titanic_pipeline.pkl
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│   ├── evaluate.py
│   └── pipeline.py
│
├── requirements.txt
├── README.md
└── run_training.py
```

---

# 🔄 Machine Learning Workflow

```text id="u11b5l"
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Preprocessing Pipeline
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Saved Pipeline (.pkl)
      │
      ▼
Prediction on New Data
```

---

# 📊 Dataset

The project uses the famous **Titanic Dataset** from Kaggle.

Input features include:

* Passenger Class
* Sex
* Age
* Fare
* Number of Siblings/Spouses
* Number of Parents/Children
* Embarked Port

Target:

* **Survived**

  * 0 → Did Not Survive
  * 1 → Survived

---

# 🧠 Machine Learning Pipeline

The pipeline automates the complete preprocessing workflow:

* Missing value imputation
* Categorical feature encoding
* Numerical feature scaling
* Feature transformation
* Model training
* Prediction

Using a Scikit-learn Pipeline ensures that the same preprocessing steps are applied consistently during both training and inference.

---

# 🚀 Installation

Clone the repository:

```bash id="fjlwm0"
git clone https://github.com/Abhhiiissshhek/Titanic-ML-Pipeline.git

cd Titanic-ML-Pipeline
```

Create a virtual environment:

```bash id="3rnzqn"
python -m venv .venv
```

Activate it:

### Windows

```bash id="xwxjlwm"
.venv\Scripts\activate
```

### Linux/macOS

```bash id="0a0wpf"
source .venv/bin/activate
```

Install dependencies:

```bash id="rrqmdq"
pip install -r requirements.txt
```

---

# ▶️ Train the Model

```bash id="d74nbd"
python run_training.py
```

The script will:

* Load the dataset
* Preprocess the data
* Train the model
* Evaluate performance
* Save the trained pipeline

---

# 🔮 Make Predictions

Run:

```bash id="nzxjlwm"
python src/predict.py
```

Example prediction:

```text id="khy4vw"
Passenger:

Age: 24
Sex: Female
Class: 1

Prediction:

✅ Survived
```

---

# 📈 Model Evaluation

Evaluate the trained model using:

```bash id="6prr7r"
python src/evaluate.py
```

Metrics include:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

> **Note:** Replace the placeholder values below with your actual evaluation results.

| Metric    |  Value |
| --------- | -----: |
| Accuracy  | XX.XX% |
| Precision |  XX.XX |
| Recall    |  XX.XX |
| F1 Score  |  XX.XX |

---

# 📦 Saved Model

After training, the complete preprocessing pipeline and trained model are saved as:

```text id="cdsgiw"
models/
└── titanic_pipeline.pkl
```

This allows predictions on new data without retraining the model.

---

# 📚 Key Learnings

This project helped me gain practical experience with:

* Data preprocessing
* Feature engineering
* Scikit-learn Pipelines
* Machine Learning model training
* Model evaluation
* Model serialization
* Building reusable ML workflows

---

# 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Feature importance visualization
* Experiment tracking with MLflow
* FastAPI deployment
* Streamlit web application
* Docker support
* GitHub Actions for CI/CD

---

# 👨‍💻 Author

**Abhishek Prajapati**

* GitHub: https://github.com/Abhhiiissshhek
* LinkedIn: https://www.linkedin.com/in/abhishekprajapati-ml

---

# ⭐ Support

If you found this project useful, consider giving the repository a **⭐ Star**. Feedback, issues, and contributions are always welcome.

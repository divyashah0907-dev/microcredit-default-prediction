# Microfinance-Loan-Repayment-Prediction-System

A Machine Learning project focused on predicting whether a microcredit borrower is likely to default on a loan. The project uses borrower and loan-related features to build predictive models that help financial institutions assess credit risk and make informed lending decisions.

## 📂 Project Structure

```
Microfinance-Loan-Repayment-Prediction-System/
│
├── README.md                           # Project documentation
├── microfinance_data_description.xlsx   # Description of dataset attributes and features
├── microcrofinance_loan_repayment_prediction.ipynb # Main notebook containing data analysis and model development
└── microfinance_sample_dataset.xlsx     # Sample dataset used for training and testing
```

---

## 🎯 Project Objective

The goal of this project is to develop a predictive model that identifies borrowers who are at risk of defaulting on their microcredit loans.

By analyzing borrower demographics, financial history, and loan characteristics, the model helps improve lending decisions and reduce financial risk.

---

## 📊 Dataset

The dataset contains borrower and loan-related information used to predict loan repayment behavior.

### Files

| File | Description |
|--------|-------------|
| `microfinance_sample_dataset.xlsx` | Sample dataset containing borrower and loan information |
| `microfinance_data_description.xlsx` | Detailed explanation of all dataset features and variables |
| `microfinance_default_prediction.ipynb` | Jupyter Notebook containing data preprocessing, model training, and evaluation |

---

## 🔍 Project Workflow

### 1. Data Collection
- Load dataset from Excel files.
- Understand feature definitions using the data description file.

### 2. Exploratory Data Analysis (EDA)
- Analyze data distributions.
- Identify missing values.
- Detect outliers.
- Explore relationships between features and loan default status.

### 3. Data Preprocessing
- Handle missing values.
- Encode categorical variables.
- Feature engineering.
- Scale numerical features where necessary.

### 4. Model Development
- Train classification models to predict loan defaults.
- Compare multiple algorithms.
- Optimize model performance.

### 5. Model Evaluation
Common evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### 6. Prediction
- Predict default probability for new borrowers.
- Classify borrowers into low-risk and high-risk categories.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/microcredit_default_prediction.git
cd microcredit_default_prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
microcredit_default_prediction.ipynb
```

Run all cells to reproduce the complete analysis and prediction workflow.

---

## 📈 Expected Results

The trained model predicts whether a borrower is likely to default on a loan based on historical borrower and loan information.

Potential benefits include:

- Improved credit risk assessment
- Better loan approval decisions
- Reduced default rates
- Enhanced portfolio management

---

## 🔮 Future Enhancements

- Hyperparameter tuning
- Feature selection optimization
- Ensemble learning techniques
- XGBoost / LightGBM implementation
- Probability-based risk scoring
- Model deployment using Flask or FastAPI
- Interactive dashboard using Streamlit

---

## 💡 Business Use Cases

- Microfinance Institutions (MFIs)
- Rural Banking Systems
- Credit Risk Assessment Platforms
- Financial Inclusion Programs
- Digital Lending Applications

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

## 👨‍💻 Author

**Divya Shah**

Machine Learning Project – Microcredit Default Prediction using Python and Scikit-Learn.

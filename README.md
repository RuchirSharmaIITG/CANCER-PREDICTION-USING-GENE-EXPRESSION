# 🧬 CANCER-PREDICTION-USING-GENE-EXPRESSION

In this project, we explored cancer classification using 14,500+ gene features. After careful preprocessing and feature selection, we applied Random Forest and Logistic Regression (OvR). 
The approach performed well, with F1-scores of 1.00 (public) and 0.991 (private) in the hackathon (link in ABOUT THE PROJECT.pdf).

---

## 🛠️ Tools & Libraries

- Python 3.10+
- scikit-learn
- pandas
- numpy
- seaborn
- matplotlib

---

## 🧪 Models Implemented

- Random Forest Classifier
- Logistic Regression (One-vs-Rest)

---

## 🔍 Key Features

- Missing value handling and normalization
- Top 300 features selected using Mutual Information
- Two models used: **Logistic Regression (LR)** and **Random Forest (RF)**
- Visualizations: MI scores, ROC curves, confusion matrices
- Evaluation: accuracy, F1-score, precision, recall
- Predictions on 401 test samples with submission-ready output

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RuchirSharmaIITG/CANCER-PREDICTION-USING-GENE-EXPRESSION.git
   cd CANCER-PREDICTION-USING-GENE-EXPRESSION
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook "CANCER PREDICTION USING GENE EXPRESSION.ipynb"
   ```

---

## 📁 Project Structure

```bash
├── DATASET                                        # Includes raw dataset files
│   ├── sample_submission.csv
│   ├── test.csv
│   ├── train.csv
│   └── train_labels.csv
├── ABOUT THE PROJECT.pdf                          # Project summary and hackathon link
├── CANCER PREDICTION USING GENE EXPRESSION.ipynb  # Main notebook
├── README.md                                      # Project overview file
├── requirements.txt                               # Required Python packages
├── submission_RUCHIR_SHARMA_LR.csv                # Logistic Regression predictions
└── submission_RUCHIR_SHARMA_RF.csv                # Random Forest predictions
```

## 📬 Contact

- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/ruchir-sharma-243a10337) 

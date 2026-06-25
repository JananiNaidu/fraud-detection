# Fraud Detection using Machine Learning

Build a production-ready fraud detection system from scratch using Python.

## Project Overview
This project detects fraudulent financial transactions using machine learning achieving 94% accuracy.

## Skills Gained
- Data preprocessing and cleaning
- Feature engineering
- Handling imbalanced datasets (SMOTE)
- Model selection and evaluation
- NLP, embeddings, tokenization
- REST API deployment with Flask

## Project Structure
fraud-detection/

├── data/

├── src/

│   ├── data_preprocessing.py

│   ├── feature_engineering.py

│   ├── train.py

│   ├── evaluate.py

│   └── predict.py

├── reports/figures/

├── main.py

├── app.py

└── requirements.txt
## Results
| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 91.2% | 0.93 |
| Random Forest | 94.1% | 0.97 |
| XGBoost | 94.8% | 0.98 |

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Add dataset to `data/raw/creditcard.csv`
3. Run: `python main.py`
## Output Results

### Confusion Matrix
![Confusion Matrix](reports/figures/confusion_matrix_Best%20Model.png)

### ROC Curve
![ROC Curve](reports/figures/roc_curve_Best%20Model.png)
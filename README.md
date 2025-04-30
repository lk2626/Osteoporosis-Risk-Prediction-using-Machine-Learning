Osteoporosis Risk Prediction using Machine Learning via FRAX®
🔍 Overview
This project explores the use of machine learning to predict osteoporosis risk factors using FRAX data. We compare Gradient Boosting Classifier (GBC) with four other popular ML algorithms—Random Forest, Support Vector Machine, Logistic Regression, and K Nearest Neighbors—to evaluate their effectiveness in identifying individuals at risk of osteoporotic fractures.

📌 Objective
To screen individuals aged ≥35 from rural Chennai, Tamil Nadu, and predict their risk of osteoporotic fractures using the FRAX® calculator and machine learning models. The goal is to improve predictive accuracy over traditional clinical methods.

📊 Dataset
Sample Size: 500 individuals (270 males, 230 females)

Age Group: ≥35 years

Location: Rural areas of Chennai, Tamil Nadu, India

BMD Measurement: Dual-energy X-ray absorptiometry (DXA)

Input Features: Clinical risk factors and FRAX scores

🧠 Machine Learning Models Used
Gradient Boosting Classifier (GBC)

Random Forest Classifier

Support Vector Machine (SVM)

Logistic Regression

K Nearest Neighbors (KNN)

⚙️ Technologies
Python 3.x

Scikit-learn

XGBoost

NumPy, Pandas

Matplotlib, Seaborn

Jupyter Notebook

📈 Evaluation Metrics
Accuracy

Precision

Recall

F1-score

AUC-ROC Curve

🚀 Results
Gradient Boosting Classifier demonstrated superior performance due to its ability to model complex interactions and feature importance.

The study provides insights for better early screening of at-risk individuals.

📂 Project Structure
graphql
Copy
Edit
.
├── data/                         # FRAX dataset and BMD measurements
├── notebooks/                   # Jupyter notebooks for EDA & ML models
├── models/                      # Trained model files
├── src/                         # Source code for preprocessing and ML pipeline
├── results/                     # Graphs, plots, and evaluation metrics
├── requirements.txt             # Required Python libraries
├── README.md                    # Project documentation
└── LICENSE                      # MIT License

🔄 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/lk2626/osteoporosis-risk-prediction.git
cd osteoporosis-risk-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook
Open notebooks/Osteoporosis_Risk_Analysis.ipynb and run the cells.

📌 Key Findings
Females showed a higher risk (10.4%) compared to males (5.5%).

GBC outperformed other models in all major metrics.

Feature importance analysis provides interpretability for medical use.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙋‍♀️ Author
Lakshmi Kannan


⸻

❤️ Heart Disease Prediction using Machine Learning

This project predicts the likelihood of heart disease based on patient medical data using machine learning techniques. By analyzing attributes such as age, cholesterol levels, blood pressure, and more, the system aims to assist early diagnosis and preventive healthcare.

⸻

📌 Overview
	•	Developed using Python and scikit-learn
	•	Explores multiple ML models for comparison
	•	Visualizes data insights and feature correlations
	•	Evaluated using accuracy, precision, recall, and confusion matrix
	•	Deployed as a simple web app using Streamlit

⸻

🧠 Algorithms Used
	•	Logistic Regression
	•	Random Forest Classifier

⸻

📊 Model Evaluation

The best-performing model achieved:
	•	Accuracy: 87.3%
	•	Precision: 85.4%
	•	Recall: 86.1%
	•	F1-Score: 85.7%

Confusion Matrix

To save this plot, use:

from sklearn.metrics import ConfusionMatrixDisplay
ConfusionMatrixDisplay.from_estimator(model, X_test, y_test)
plt.savefig('images/confusion_matrix.png')


⸻

📁 Dataset

Based on the UCI Heart Disease Dataset, which includes:
	•	Age, Sex, Chest Pain Type
	•	Resting Blood Pressure, Cholesterol
	•	Fasting Blood Sugar, Max Heart Rate
	•	Exercise-Induced Angina, ST Depression
	•	Target: Presence or absence of heart disease

⸻

🔧 Installation

Install all dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn 


⸻

🚀 How to Run the Notebook
	1.	Clone the repository:

git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction


	2.	Launch the Jupyter Notebook:

jupyter notebook "Heart Disease .ipynb"


⸻

📬 Contact

Dheeraj Kattinti
📧 kattintidheeraj@gmail.com

⸻

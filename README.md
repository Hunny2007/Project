
Student Performance Analyzer (SPA)
This project analyzes student exam performance data using classification and clustering models. It explores how factors like gender, parental education, test preparation, and lunch types affect scores.

📂 Dataset
Source: StudentsPerformance.csv
Columns:
gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score
🔍 Key Features
Exploratory Data Analysis (EDA)
Feature Engineering
Created average_score
Classified students into Pass (≥ 50) or Fail (< 50)
Classification Models
Logistic Regression
K-Nearest Neighbors (KNN)
Clustering
K-Means Clustering (based on math, reading, writing scores)
📊 Models Used
Model	Description
Logistic Regression	Predicts Pass/Fail using score-related data
KNN	Uses neighbors to classify Pass/Fail
K-Means	Groups students based on performance
📈 Visualizations
Boxplots: Test prep vs. average score
Scatter plots: Clustered performance data
Heatmaps and score distributions
🛠️ Tools & Libraries
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
✅ How to Run
Clone this repo or download it.

Run the Jupyter Notebook (.ipynb) in VS Code or Jupyter.

Install required libraries with:

pip install -r requirements.txt
📌 Results Summary
Students who completed test preparation scored significantly higher.
Clustering helps identify performance groups visually.
Logistic Regression and KNN models achieved reasonable accuracy.
🙋‍♂️ Author
Hunny Thiran 
GitHub Profile
**A. Project Overview**

- This project 

**B. Dataset Information**

**Source**

- Titanic - Machine Learning from Disaster (from Kaggle): https://www.kaggle.com/datasets/dimplebathija/titanic-machine-learning-from-disaster

**How to process**

I. Cleaning
- Train data file:
    + Fill Column Age by median
    + Fill Column Embarked by Mode
    + Remove Cabin column
- Test data file:
    + Fill Column Age by median
    + Fill Column Embarked by Mode
    + Fill Column Fare by median
    + Remove Cabin column
II. Encoding
- Sex & Embarked
III. Split x and y for Training Set
IV. Train Logistic Regression Model
V. Predict on Test Data

**C. Insights**

- A Logistic Regression baseline model was built to predict passenger survival on the Titanic dataset. The model achieved around 80% validation accuracy and a ROC AUC of approximately 0.84, demonstrating a solid ability to differentiate between survivors and non-survivors.

**D. Appendix**

- Evaluate Model on Validation Data
    + Logistic Regression Validation Accuracy: 0.8044692737430168
    + Logistic Regression Validation Precision: 0.7931034482758621
    + Logistic Regression Validation Recall: 0.6666666666666666
    + Logistic Regression Validation F1 Score: 0.7244094488188977
    + Logistic Regression Validation ROC AUC: 0.8442687747035573
    + Confusion Matrix:[[98 12] [23 46]]

_**About Me**_

Hi, I'm Navin (Bao Vy) – an aspiring Data Analyst passionate about turning raw data into actionable business insights.
I’m eager to contribute to data-driven decision making and help organizations translate analytics into business impact.
For more details, please reach out at:

🌐 LinkedIn: https://www.linkedin.com/in/navin826/

📂 Portfolio: https://github.com/CallmeNavin/
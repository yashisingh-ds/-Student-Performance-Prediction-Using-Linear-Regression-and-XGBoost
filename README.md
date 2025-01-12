# Student-Performance-Prediction-Using-Linear-Regression-and-XGBoost

# 🎯 Project Overview

This project aims to predict student performance using machine learning algorithms. The prediction models were built using two datasets: stu_mat and stu_por. The models were evaluated using the Mean Squared Error (MSE) and R-squared (R²) metrics.The performance of the models showed significant improvement after applying the XGBoost algorithm, achieving an accuracy of 99.99% compared to 83.9% using Linear Regression.
The project utilizes two datasets — stu_mat and stu_por — that contain information about students' academic performance in Mathematics and Portuguese Language, respectively. By applying different machine learning models and evaluation metrics, we were able to achieve a significant improvement in accuracy by optimizing the model with XGBoost.

### 🧑‍💻 Technologies and Libraries Used
- **Python** 🐍  
- **pandas** – For data manipulation and analysis  
- **scikit-learn** – For implementing machine learning algorithms such as Linear Regression  
- **XGBoost** – For applying the Extreme Gradient Boosting algorithm to improve model accuracy  
- **matplotlib** – For creating static, interactive, and animated visualizations in Python  
- **seaborn** – For making statistical graphics and enhancing data visualizations  

# 🗂️ Datasets Used
We used the following datasets for this project:
# (i) stu_mat:
This dataset contains information related to students' performance in Mathematics.
It includes various features such as age, gender, study time, parental education, and previous academic performance.
The target variable is the final grade (G3).

# (ii)stu_por:
This dataset contains information related to students' performance in Portuguese Language.
Similar to the stu_mat dataset, it includes features such as study time, family relationships, and school support programs, with the target variable being the final grade (G3).
Both datasets were preprocessed to handle missing values and categorical features before applying the machine learning models.

# 🧪 Algorithms Implemented
In this project, we implemented and compared the performance of Linear Regression and XGBoost for predicting student grades.

# 1️⃣ Linear Regression
Linear Regression is a basic regression algorithm that fits a straight line to the data by minimizing the Mean Squared Error (MSE) between the predicted and actual values.
It was used as the baseline model for this project.
After training the model on the stu_mat and stu_por datasets, the accuracy achieved was 83.9%, indicating that Linear Regression was able to capture some relationships between the features and the target variable.
Evaluation Metrics Used for Linear Regression:
(i)Mean Squared Error (MSE)
(ii) R-squared (R²) Score
# 2️⃣ XGBoost (Extreme Gradient Boosting)
XGBoost is a powerful ensemble algorithm that builds multiple decision trees in a sequential manner, optimizing the model by minimizing the error at each iteration.
It is known for its high accuracy and efficiency in handling large datasets and complex relationships between variables.
After applying XGBoost on the same datasets, the model's performance improved significantly to 99.99% accuracy.

# 📈 Results and Insights
The project demonstrates that XGBoost is a more effective algorithm for predicting student performance compared to Linear Regression. The accuracy improved from 83.9% with Linear Regression to 99.99% with XGBoost, indicating that the boosting technique can handle complex data patterns more efficiently.
### 🔍 **Key Findings**  
- **Linear Regression** captured basic relationships but struggled with
- **non-linear patterns** in the data, resulting in a lower accuracy of **83.9%**.  
- **XGBoost** effectively captured both
- **linear and non-linear relationships**, leading to a nearly perfect accuracy of **99.99%**.  
- The improvement in performance highlights the importance of using **advanced machine learning techniques** for achieving better predictions.




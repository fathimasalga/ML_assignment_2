Objective:
The objective of this assignment is to understand and apply various regression techniques in supervised machine learning using a real-world dataset. Multiple regression models are implemented, evaluated, and compared to identify the best-performing algorithm.


Dataset:
- Dataset Name: California Housing Dataset
- Source: OpenML (california_housing)
- Description:
The dataset contains information about houses in California, including features such as median income, house age, average rooms, population, and proximity to the ocean. The target variable is Median House Value.


Technologies Used:
- Python
- Jupyter Notebook
- Libraries:
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn (for visualization)

Preprocessing Steps:
- Converted the dataset into a pandas DataFrame
- Checked and confirmed there are no missing values
- Applied square root transformation to reduce skewness in selected numerical features
- Encoded the categorical feature (ocean_proximity) using one-hot encoding
- Performed feature scaling using StandardScaler for scale-sensitive models

Regression Models Implemented:
The following regression algorithms were implemented:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor (SVR)
Each model was trained and tested using an 80–20 train-test split.

JUPYTER NOTEBOOK WITH CODES ARE ATTATCHED

# Student Performance Prediction with Decision Tree

This Jupyter Notebook demonstrates how to use a Decision Tree Regressor to predict student performance based on various features. The workflow includes the following steps:

1. **Data Import and Preprocessing**
   - Import necessary libraries: numpy, pandas, matplotlib, scikit-learn.
   - Load datasets: `student-mat.csv` and `student-por.csv`.
   - Combine the datasets and preprocess the data (e.g., convert categorical variables to numerical values, handle missing values, create dummy variables).

2. **Exploratory Data Analysis (EDA)**
   - Visualize the data distribution using histograms.
   - Describe the statistical properties of the data.

3. **Feature Selection and Splitting Data**
   - Define feature columns and target variable (`G3` - final grade).
   - Split the data into training and testing sets.

4. **Binary Classification**
   - Create a binary classification target based on the final grade (`G3_class`).

5. **Model Training and Evaluation**
   - Initialize and train the Decision Tree Regressor for regression.
   - Initialize and train the Decision Tree Classifier for classification.
   - Make predictions on the test set.
   - Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared Score (R2), accuracy, and classification report.

6. **Model Optimization**
   - Use GridSearchCV to find the best parameters for the Decision Tree Regressor and Classifier.
   - Train the model with the optimized parameters and evaluate its performance.

## Metrics Achieved
- **Mean Absolute Error (MAE)**: Updated value
- **Mean Squared Error (MSE)**: Updated value
- **Root Mean Squared Error (RMSE)**: Updated value
- **R-squared Score (R2)**: Updated value
- **Optimized R2 Score**: Updated value
- **Classification Accuracy**: Updated value
- **Classification Report**: Updated value

You can view the full notebook [here](https://github.com/kelvinadaisky/Student-Performance-Prediciton-With-Decision-Tree/blob/main/StudentPerformance.ipynb).

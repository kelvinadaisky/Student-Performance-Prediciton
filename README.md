Here is a summary with added style to improve readability:

---

# Decision Tree Regressor for Student Performance Prediction

This Jupyter Notebook demonstrates how to use a Decision Tree Regressor to predict student performance based on various features. The workflow includes the following steps:

1. **Data Import and Preprocessing**
   - Import necessary libraries: numpy, pandas, matplotlib, scikit-learn.
   - Load datasets: `student-mat.csv` and `student-por.csv`.
   - Combine the datasets and preprocess the data (e.g., convert categorical variables to numerical values, create dummy variables).

2. **Feature Selection and Splitting Data**
   - Define feature columns and target variable (`G3` - final grade).
   - Split the data into training and testing sets.

3. **Model Training and Evaluation**
   - Initialize and train the Decision Tree Regressor.
   - Make predictions on the test set.
   - Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared Score (R2).

4. **Model Optimization**
   - Use GridSearchCV to find the best parameters for the Decision Tree Regressor.
   - Train the model with the optimized parameters and evaluate its performance.

## Metrics Achieved
- **Mean Absolute Error (MAE)**: 1.32
- **Mean Squared Error (MSE)**: 5.45
- **Root Mean Squared Error (RMSE)**: 2.33
- **R-squared Score (R2)**: 0.63
- **Optimized R2 Score**: 0.78

You can view the full notebook [here](https://github.com/kelvinadaisky/Data-Mining/blob/main/Decision%20tree.ipynb).

---

This should help make the summary more readable and structured for your README file.

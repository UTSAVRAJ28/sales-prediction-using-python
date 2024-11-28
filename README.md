# SALES-PREDICTION-USING-PYTHON
My 4th Project of DataScience
          SALES PREDICTION USING PYTHON
1. Sales prediction involves forecasting the amount of a product that
   customers will purchase, taking into account various factors such as
   advertising expenditure, target audience segmentation, and
   advertising platform selection.
2. In businesses that offer products or services, the role of a Data
   Scientist is crucial for predicting future sales. They utilize machine
   learning techniques in Python to analyze and interpret data, allowing
   them to make informed decisions regarding advertising costs. By
   leveraging these predictions, businesses can optimize their
   advertising strategies and maximize sales potential. Let' embark on
   the journey of sales prediction using machine learning in Python.
Dataset:- https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input


### Explanation:
1. **Import Libraries**: Import necessary libraries such as pandas for data handling, scikit-learn for machine learning tools.
  
2. **Read Data**: Load your dataset using `pd.read_csv()`.

3. **Prepare Data**: Separate your features (`X`: TV, Radio, Newspaper) and target variable (`y`: Sales).

4. **Split Data**: Split the data into training and testing sets using `train_test_split()`.

5. **Model Selection and Training**: Initialize a linear regression model (`LinearRegression()`), train it on the training data (`model.fit()`).

6. **Make Predictions**: Use the trained model to make predictions on the test set (`model.predict()`).

7. **Evaluation**: Evaluate the model using metrics like Mean Squared Error (`mean_squared_error()`).

8. **Prediction**: Optionally, make predictions on new data points (`new_data_point`) using the trained model.

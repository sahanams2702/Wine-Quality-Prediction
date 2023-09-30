# Wine-Quality-Prediction
Sure, here's a short README file for your code:

# Wine Quality Prediction using Machine Learning

This Python script is designed to predict the quality of wine based on various features using machine learning models, specifically Logistic Regression and K-Nearest Neighbors (KNN). Below is a brief overview of the code and its functionalities:

## Overview of the Code

1. **Importing Libraries**: The code begins by importing the necessary libraries, including pandas, numpy, matplotlib, seaborn, and scikit-learn.

2. **Loading the Dataset**: It loads the wine quality dataset (CSV file) using pandas and displays the first few rows of the dataset to provide an understanding of the data structure.

3. **Data Exploration and Preprocessing**: Basic data exploration is performed, including checking for missing values, displaying summary statistics, and visualizing data distributions and correlations using seaborn and matplotlib.

4. **Creating a Binary Target Variable**: A new column named "goodquality" is created, which contains binary values (1 for good quality and 0 for others) based on a predefined quality threshold (in this case, a wine is considered good if its quality is 7 or higher).

5. **Data Splitting**: The dataset is split into training and testing sets using scikit-learn's `train_test_split` function.

6. **Logistic Regression Model**: A Logistic Regression model is trained using the training data to predict the "goodquality" target variable. The model's accuracy is evaluated on the test data.

7. **K-Nearest Neighbors (KNN) Model**: A KNN classifier is trained on the same data, and its accuracy is also evaluated on the test data.

8. **Model Comparison**: The accuracy of both models is compared, and it is noted that the Logistic Regression model performs slightly better in this case.

9. **Saving the Model**: The trained Logistic Regression model is saved using the `pickle` library so that it can be reused for future predictions.

10. **Predictions**: A sample wine data point is taken from the dataset, and the saved model is used to predict whether it's of good quality or not.

## Instructions for Running the Code

1. Make sure you have the required libraries (pandas, numpy, scikit-learn, matplotlib, seaborn) installed.

2. Ensure you have the wine quality dataset (CSV file) available at the specified file path (`C:\Users\PRIYAM\Documents\Jupyter\Wine Quality Prediction\winequality.csv`). You can replace this path with the actual path to your dataset.

3. Run the code, and it will perform data exploration, model training, and save the trained Logistic Regression model.

4. You can later load the saved model and use it for making predictions on new wine data.

This README provides a brief overview of the code's functionality. For more detailed information and explanations, you can refer to the comments and code in the Python script itself.

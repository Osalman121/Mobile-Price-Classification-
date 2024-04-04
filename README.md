# Classification Model Evaluation and Prediction

This repository contains Python code for a classification model to predict the price range of mobile phones based on various features. The dataset used for training and testing the model is stored in a CSV file named "train.csv". Additionally, the trained model is used to make predictions on a separate test dataset stored in a file named "test.csv".

## Dataset Description
- The dataset contains information about mobile phone features such as battery power, RAM, internal memory, and more.
- It includes a target variable named "price_range" representing the price range of mobile phones (0, 1, 2, 3).

## Exploratory Data Analysis (EDA)
- The dataset is loaded using Pandas and explored to understand its structure and characteristics.
- Descriptive statistics and visualizations (box plots, correlation heatmap) are used to analyze the distribution and relationships between features.

## Data Preprocessing
- Missing values are checked and handled appropriately.
- Outliers in certain features (e.g., "fc", "px_height") are identified and treated using median imputation.
- Feature scaling and normalization are performed as needed.

## Classification Models
- Three different classification algorithms are evaluated:
  1. Decision Tree
  2. Support Vector Machine (SVM)
  3. Random Forest

## Model Evaluation
- Each model is trained on the training data and evaluated using accuracy score on the test data.
- The trained models are used to make predictions on the test dataset to assess their performance.

## Conclusion
- The classification models are evaluated based on their accuracy in predicting the price range of mobile phones.
- The best-performing model is determined based on its accuracy score on the test data.

For any questions or further details, please refer to the code files in this repository or contact the repository owner.

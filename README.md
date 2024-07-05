## Machine Learning Project

* Price Prediction Of Diamonds
 ![image](https://github.com/uttejkumaro/DiamondPricePrediction/assets/117030083/2b1f506b-f68b-4481-b56f-8bdcb101f03a)

Dataset Source Link :
[https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)

* Table of Contents
Overview
Dataset
Installation
Usage
Model
Results
Contributing
* Overview
This project aims to predict the price of diamonds based on various attributes such as carat, cut, color, clarity, depth, table, x, y, and z. By using machine learning techniques, we aim to build a model that can accurately estimate the price of a diamond given its characteristics.

The dataset used for this project contains the following features:

Carat: The weight of the diamond.
Cut: The quality of the diamond's cut (Fair, Good, Very Good, Premium, Ideal).
Color: The color grade of the diamond (ranging from D to J).
Clarity: The clarity of the diamond (ranging from I1 (Inclusions) to IF (Internally Flawless)).
Depth: The depth percentage of the diamond.
Table: The table percentage of the diamond.
X: The length of the diamond in mm.
Y: The width of the diamond in mm.
Z: The depth of the diamond in mm.
Price: The price of the diamond in US dollars.
Installation
To get started with this project, follow these steps:

Clone the repository: https://github.com/uttejkumaro/DiamondPricePrediction

cd diamond-price-prediction
Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

pip install -r requirements.txt
Usage
* Data Preprocessing:

Clean and preprocess the dataset.
Handle missing values and outliers.
Encode categorical features.
Split the data into training and testing sets.
* Model Training:

Train the machine learning model using the training set.
Evaluate the model performance using the testing set.
* Prediction:

Use the trained model to predict the price of new diamonds.
Evaluate the model performance using various metrics.
Running the Code
To run the data preprocessing script:

python preprocess.py

* To train the model:

python train.py

To make predictions:

python predict.py
Model

The following models were evaluated during this project:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

XGBoost Regressor
* Results
  
The model performance was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). The best-performing model was Random Forest Regressor.
* Contributing

* Contributions are welcome! Please follow these steps to contribute:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/your-feature).

Create a new Pull Request.


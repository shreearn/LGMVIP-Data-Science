# LGMVIP-Data-Science
<br>
# LGMVIP_DECISIONTREE.IPYNB
# Decision Tree Classifier for Iris Dataset

Task Description:

Implementing a Decision Tree Classifier on the Iris dataset to classify iris plant species based on sepal and petal measurements.


Dataset:

The Iris dataset contains the following columns:

- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm
- Species


Steps:

1. Importing necessary libraries.
2. Loading the dataset and preparing it for training.
3. Visualizing the dataset using scatter plots.
4. Splitting the dataset into training and testing sets.
5. Building the Decision Tree Classifier using the Gini criterion.
6. Visualizing the decision tree structure using tree.plot_tree and graphviz.
7. Evaluating the model's accuracy and generating a confusion matrix.
8. Predicting the iris species for custom data.


Required Libraries:

- numpy
- pandas
- matplotlib
- sklearn
- graphviz






# Iris Flowers Classification ML Project
# LGMVIP_IRIS

Task Description:

Implementing a Logistic Regression model to classify Iris flowers into three species (setosa, versicolor, virginica) based on sepal and petal measurements.


Dataset:

The Iris dataset contains the following columns:

- Sepal_Length(cm)
- Sepal_Width(cm)
- Petal_Length(cm)
- Petal_Width(cm)
- Species_Flower

  
Steps:

1. Importing necessary libraries.
2. Loading the dataset and preparing it for training.
3. Checking for missing values in the dataset.
4. Performing statistical analysis on the dataset.
5. Separating the dataset into dependent (y) and independent (x) variables.
6. Splitting the dataset into training and testing sets.
7. Building a Logistic Regression model.
8. Evaluating the model's accuracy on the training and testing sets.
9. Predicting the species of Iris flowers for custom data.

   
Required Libraries:
- pandas
- numpy
- sklearn



# Stock Market Prediction and Forecasting using Stacked LSTM
# LGMVIP_LSTM

Task Description:

Implementing a Stacked Long Short-Term Memory (LSTM) model to predict and forecast stock prices based on historical stock data.


Dataset:

The dataset contains the following columns:
- Date
- Open
- High
- Low
- Last
- Close
- Total Trade Quantity
- Turnover (Lacs)

  
Steps:

1. Importing necessary libraries.
2. Loading and preprocessing the dataset.
3. Creating a new dataframe with only the 'Close' feature.
4. Splitting the dataset into training and testing sets.
5. Creating sequences of data for LSTM input.
6. Building a Stacked LSTM model.
7. Training the model on the training set.
8. Making predictions on the training and testing sets.
9. Evaluating the model's performance using Mean Squared Error (MSE).
10. Visualizing the actual vs predicted stock prices.

    
Required Libraries:

- numpy
- pandas
- sklearn
- keras
- matplotlib

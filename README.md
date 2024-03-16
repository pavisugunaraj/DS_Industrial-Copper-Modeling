<h1>DS_Industrial-Copper-Modeling</h1>

<h2>Introduction</h2>

This project aims to develop two machine learning models for the copper industry to address the challenges of predicting selling price and
lead classification. Manual predictions can be time-consuming and may not result in optimal pricing decisions or accurately capture leads. 
The models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, 
identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm, to predict the 
selling price and leads accurately.

<h2>Regression model details</h2>

The copper industry deals with less complex data related to sales and pricing. However, this data may suffer 
from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with 
these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning 
regression model can address these issues by utilizing advanced techniques such as data normalization, 
outlier detection and handling, handling data in wrong format, identifying the distribution of features, 
and leveraging tree-based models, specifically the decision tree algorithm.


<h2>Classification model details</h2>

Another area where the copper industry faces challenges is in capturing the leads. A lead classification model 
is a system for evaluating and classifying leads based on how likely they are to become a customer. You can use 
the STATUS variable with WON being considered as Success and LOST being considered as Failure and remove data 
points other than WON, LOST STATUS values.

<h2>Solution</h2>

<h3>The solution includes the following steps:</h3>

1) Exploring skewness and outliers in the dataset.

2) Transforming the data into a suitable format and performing any necessary cleaning and pre-processing steps.

3) Developing a machine learning regression model which predicts the continuous variable 'Selling_Price' using the decision tree regressor.

4) Developing a machine learning classification model which predicts the Status: WON or LOST using the decision tree classifier.

5) Creating a Streamlit page where you can insert each column value and get the Selling_Price predicted value or Status (Won/Lost).


<h2>Requirements</h2>

<h3>This project requires the following libraries to be installed:</h3>

1. NumPy

2. Pandas

3. Scikit-learn

4. Streamlit


<h2>Getting Started</h2>

1) Clone the repository.

2) Install the required libraries.

3) Run the Streamlit app using the command: streamlit run app.py.

4) Enter the values for each column to get the Selling_Price predicted value or Status (Won/Lost).

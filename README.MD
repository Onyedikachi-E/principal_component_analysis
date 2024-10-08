# Module 5 Assignment: Principal Component Analysis

This is project is about carrying a data anaylysis at Anderson Cancer Center using the breast cancer dataset from sklearn.datasets. It involves loading the dataset from the library and standardizing the selected feature using a Scaling technique. This scaled data will now be decomposed into two component using Principal Component Analysis (PCA). This scaled data will now be used to train a logistic regression model. This model will be tested and evaluated in-order to determine its efficiency and correctness.


## Key Features

- **Breast Cancer Dataset**: The program is able to load the breast cancer dataset from the sklearn.datasets.
- **Data Exploration**: The program is able to explore the dataset in-order to gain insight into the key features of the dataset.
- **Data Transformation**: The project made use of Scaling Technique to tranform the the data into a standardize format.
- **Data Decomposition**: Using Principal Component Anaysis (PCA), the program was able to do a dimensionality reduction of the data set into two principal components.
- **Data Model Creation**: A LogisticRegression model was created and was fitted with train datasets from the cancer datasets to be able to classify data and predict efficiently. 
- **Data Model Testing and Evaluation**: The use of the 'predict' attribute to compare test data and predicted outcome. Then use of the 'accuracy_score' to evaluate it's efficiency.
- **Error Handling**: Added Error Handling to track any exception and print the error as a string or character.
- **Lanuguage Stack**: The entire program was written using Python programming langguage and Jupyter Notebook.

## GitHub Repository
1. https://github.com/Onyedikachi-E/principal_component_analysis


## Packages Used in the project
- **For Python**
1. Pandas - This library is used to import data into a dataframe object. This object will now have access to all the attributes of a dataframe for manipulation.
2. PCA - This was utilized to decompose the dataset into two principal components.
3. StandardScaler - This technique was used to do data transformation using the Scaling technique.
4. Matplotlib - This is an extensive python library that is very rich in data visualization 
5. train_test_split - The dataset was splitted into test and train dataset to be used to fit the the regression model.


## How To Use The Program
- **For Python**
1. Load the neccessary packages that will be used in the program
2. Run the cell blocks step by step to perform the different sets of operation

# deep-learning-challenge

## Background

The nonprofit foundation Alphabet Soup requires a tool to help select applicants for funding with the best chance of success in their ventures. A machine learning and neural network approach is proposed to create a binary classifier predicting the success of applicants if funded by Alphabet Soup.

## Files

The repository "deep-learning-challenge" contains the necessary files and instructions for completing the challenge.

## Preprocessing the Data

- Upload the starter file to Google Colab.
- Read in charity_data.csv to a Pandas DataFrame.
- Identify the target(s) and feature(s) for the model.
- Drop the EIN and NAME columns.
- Determine the number of unique values for each column.
- Bin "rare" categorical variables together.
- Encode categorical variables using pd.get_dummies().
- Split the data into features array (X) and target array (y).
- Scale the features datasets using StandardScaler.
  
## Compiling, Training, and Evaluating the Model

- Design a neural network model using TensorFlow and Keras.
- Choose the number of neurons, layers, and activation functions.
- Compile the model.
- Train the model and save its weights every five epochs.
- Evaluate the model using the test data to calculate loss and accuracy.
- Save the model to an HDF5 file named AlphabetSoupCharity.h5.

## Optimizing the Model

- Create a new Google Colab file named AlphabetSoupCharity_Optimization.ipynb.
- Read in charity_data.csv to a Pandas DataFrame.
- Preprocess the dataset and make adjustments for optimization.
- Design a neural network model optimized for higher than 75% accuracy.
- Save and export the optimized model to AlphabetSoupCharity_Optimization.h5.

## Report on the Neural Network Model

### Overview of the Analysis

The analysis aims to develop a binary classifier predicting the success of applicants if funded by Alphabet Soup.

### Results

#### Data Preprocessing

- The target variable(s) for the model are identified.
- The feature variable(s) for the model are identified.
- Irrelevant variable(s) are removed from the input data.

#### Compiling, Training, and Evaluating the Model

- Neurons, layers, and activation functions are selected based on optimization goals.
- The target model performance is achieved with accuracy higher than 75%.
- Various steps are taken to increase model performance, including preprocessing adjustments and model architecture modifications.

### Summary

The deep learning model successfully predicts the success of Alphabet Soup-funded organizations. An alternative model, such as Support Vector Machine (SVM), could be used for its robustness, effectiveness in high-dimensional spaces, and interpretability.

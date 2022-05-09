# Neural_Network_Charity_Analysis
## Overview of the analysis:
The purpose of this project is to apply a machine learning and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup (Donations). To achieve it, we used the features in the CSV dataset obtained from Alphabet Soup’s business team. The data contain more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are several columns that capture metadata about each organization, such as: EIN and NAME—Identification columns, APPLICATION_TYPE—Alphabet Soup application type, AFFILIATION—Affiliated sector of industry, CLASSIFICATION—Government organization classification, USE_CASE—Use case for funding, ORGANIZATION—Organization type, STATUS—Active status, INCOME_AMT—Income classification, SPECIAL_CONSIDERATIONS—Special consideration for application, ASK_AMT—Funding amount requested, IS_SUCCESSFUL—Was the money used effectively.</br> 
The analysis consists of 3 steps: </br>
  *	Preprocessing Data for a Neural Network Model, </br>
  *	Compiling, Training, and Evaluating the Model, </br>
  *	and the Model Optimization. </br>
We used Python in Google Collab to a process and analyze the data. </br>

## Results:
#### Preprocessing Data for a Neural Network Model
*	We checked the data for any missing data, dropped features that were futile, reorganized and standardized the model features. </br>
*	We defined our target: the column IS_SUCCESSFUL contains binary data referring to whether the charity donation was used effectively. </br>
*	We defined the model features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT</br>
*	We split the dataset into training and testing datasets. </br>
#### Compile, Train, and Evaluate the Model
*	The initial model consisted of two hidden layers with 80 and 30 neurons. </br>
*	In the training process we used the activation function ReLU for the hidden layers, and we used a Sigmoid function for the output layer in the first model. </br>
#### Optimize the Model
*	We applied other activation functions (e.g., tanh) for the hidden layers and increased hidden layers and neurons to optimize the model or improve the model accuracy.
#### Summary
The initial model accuracy was about 73%, which was bellow our targeted 75%. And the model optimization did improve the model accuracy, it continued to be about the same as before. 

# Columbia_Fintech_Module13

# Project Title

This program demonstrates Neural Networks and a simple version of Deep Learning using multi-layer Neural Network 

---

## Technologies

This project is written in python. The required libraries are as follows
pathlib, pandas, tensorflow, sklearn


---

## Usage

This program demonstrates Artificial Neural Network

## Analysis Report

The data is preprocessed for Neural Network. 
Neural Network cannot handle categorical data. Hence all the categorical data is converted to numerical using OneHotEncoder function. Once transformed, then the dataframe is divided in to training and testing set.

I attempted to create 4 different Neural Networks. 
* Original Model
    No of Hidden layers - 2
    No of Neurons 88
    Loss 0.55, Accuracy is 0.73

* Alternate Model 1
    No of Hidden layers - 1
    No of Neurons 232
    Loss 0.59, Accuracy is 0.73

* Alternate Model 2
    No of Hidden layers - 2
    No of Neurons 349
    Loss 0.56, Accuracy is 0.73

* Alternate Model 4
    No of Hidden layers - 4
    No of Neurons 1744
    Loss 0.56, Accuracy is 0.73

From the above analysis, I derive that higher complexity of Neural Networks does not necessarily improve the model predicability. The accuracy hovers around 0.73 and loss is marginally improved when the number of hidden layers is reduced to 1. Hence I recommend to either enhance the data quality or do some PCA analysis. But with the given data, keep the model simple with just one hidden layer.


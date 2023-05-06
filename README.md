# Wine Quality Calssification Model

## Overview
The aim of this project is to develop a classification predictive model for wine quality using its physiochemical properties. Wine quality is influenced by various factors, such as alcohol content, pH levels, acidity, residual sugar, and more. However, alcohol content is known to have the highest correlation with wine quality.

To achieve the project goal, a random forest model was built using a dataset of wine samples with their respective physiochemical properties and quality ratings. The model achieved an accuracy of 94.21%, indicating that it can predict wine quality with high accuracy.

This model can have practical applications in the wine industry, where winemakers can use it to predict the quality of their wines based on their physiochemical properties. Additionally, it can also help consumers to make informed decisions when purchasing wines based on their quality predictions. However, it is important to note that the model's performance should be validated on new, unseen data to ensure its generalizability.

## The Dataset
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

For more information, read [Cortez et al., 2009].

## Contents
1. [Exploratory Analysis](#1-Exploratory-Analysis) 

   1.1. [Wine Quality and Physiochemical Properties](#11-wine-quality-and-physiochemical-properties)
   
   1.2. [Distribution of Variables](#12-distribution-of-variables)
   
   1.3. [Outliers](#13-Outliers)
   
   
2. [Feature Engineer and Data Preprocessing](#2-feature-engineer-and-data-preprocessing)

    2.1. [Dealing With Outliers](##21-Dealing-With-Outliers)
    
    2.2. [Distribution Transformation](##22-Distribution-Transformation)
    
    2.3. [Dealing With Imbalance Data](##23-Dealing-With-Imbalanced-Data)
    
    2.4. [Encoding Categorical Data](##34-Encoding-Categorical-Data)
    
    2.5. [Splitting the Data into Train Set and Test Set](##35-Splitting-the-Data-into-Train-Set-and-Test-Set)
    
    2.6. [Feature Scaling](##26-Feature-Scaling)
    

3. [Machine Learning](#3-Machine-Learning)

    3.1.[Model Building](##31-Model-Building)
        
      3.3.1.[Logistic Regression](###311-Logistic-Regression)
      
      3.3.2.[K-NN(K-Nearest Neighbors)](###312-K-NN)
      
      3.3.3.[SVM (Support Vector Machine)](###313-SVM(Support-Vector-Machine))
      
      3.3.4. [Kernel SVM](###314-Kernel-SVM)
     
      3.3.5. [Naive Bayes](###315-Naive-Bayes)
        
      3.3.6. [Decision Tree](###316-Decision-Tree)
      
      3.3.7. [Random Forest](###317-Random-Forest)
      
     3.2. [Hyperparameters Tunning](##32-Hyperparameters-Tunning)
      
      3.2.1. [Grid Search](###321-Grid-Search)
      
     4.[Conclusions](#4-Conclusions)
  
## Conclusions
In conclusion, this project aimed to develop a predictive model for wine quality using its physiochemical properties, with alcohol content being the most influential factor. The random forest model built in this project achieved a high accuracy of 94.21% in predicting wine quality based on the dataset of wine samples.
This model can have practical applications in the wine industry and benefit both winemakers and consumers. Winemakers can use it to predict the quality of their wines and make informed decisions about production and blending, while consumers can make informed decisions when purchasing wines based on their predicted quality.
However, it is important to validate the model's performance on new, unseen data to ensure its generalizability before implementing it in practical applications. Furthermore, there may be additional factors that influence wine quality beyond the scope of the physiochemical properties considered in this project, which could be explored in future research.
Overall, this project demonstrates the potential of machine learning and predictive modeling in the wine industry and highlights the importance of understanding the underlying factors that influence wine quality.


## Project on Fruits
 ## Define business problem
 Efficient and accurate classification of fruit types based on their external appearance features.
 ### Defining the Question
 1. How can we automate and streamline the classification of various fruit types based on their external appearance features?

 2.What are the most important external appearance features that determine the type of fruit?

 3.How can we improve the accuracy and performance of fruit classification models beyond the achieved 92.8% using logistic regression, artificial neural networks, and stacking models?


 #### Data
 Our dataset was from Kaggle  https://www.muratkoklu.com/datasets/ 898 columns and 35 rows
 ### Data grcery



 ## Experimental design

 1.Data Collection:

Obtain a dataset of 898 images of seven different date fruit varieties (Barhee, Deglet Nour, Sukkary, Rotab Mozafati, Ruthana, Safawi, and Sagai) through a computer vision system (CVS).
2.Data Preprocessing:

Apply image processing techniques to preprocess the images and extract relevant features.
Extract a total of 34 features, including morphological features, shape, and color, from the preprocessed images.
3.Model Development:

Select machine learning methods for classification, including logistic regression (LR) and artificial neural network (ANN).
Split the dataset into training and testing sets.
Train the LR and ANN models using the training set and optimize their respective parameters.
Evaluate the performance of each model using the testing set, considering metrics such as accuracy.
4.Stacking Model:

Combine the LR and ANN models to create a stacking model.
Utilize the predictions of LR and ANN models as input features for the stacking model.
Train the stacking model using the training set and optimize its parameters.
Evaluate the performance of the stacking model using the testing set, considering metrics such as accuracy.
5.Performance Evaluation:

Compare the performance of LR, ANN, and the stacking model based on their respective accuracies.
Analyze the results to determine the effectiveness of each method and the improvement achieved through the stacking model.
6.Conclusion:

Conclude the study by highlighting the success of machine learning methods in classifying date fruit types based on their external appearance features.
Discuss the implications of the findings and potential applications of the developed models.
![output.png](https://github.com/Derrick-Mulati/Fruits-project/blob/main/output.png)


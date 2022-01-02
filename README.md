# Linear Discriminant Analysis on Wine dataset

LDA is a supervised dimensionality reduction technique used in machine learning. The goal of using LDA is to find patterns and correlations within the data and excluding unimportant features within the data. Thus we have a dataset with lesser dimensions without compromising important informations needed for accurate predictions. 

This project includes a wine dataset with many features of wine samples and customer segment being the independent variable. The goal of this project is to determine which customer segments prefer what type of wines. Thus we will be able to recommend types of wine to the right customers. 

After applying feature scaling, LDA was used to reduce the dimensions of the dataset and then Logistic Regression was used to train the model. 

# Results and Discussion 

![alt text](https://github.com/taiftahmid/Linear-Discriminant-Analysis-on-Wine-dataset/blob/master/LDA_Training.png)

- The red portion represents customer segment 1
- The green portion represents customer segment 2
- The blue portion represents customer segment 3

The following figure shows the predictions made by the model from new users. (Test Set)

![alt text](https://github.com/taiftahmid/Linear-Discriminant-Analysis-on-Wine-dataset/blob/master/LDA_Test.png)

The accuracy of the model is 100%



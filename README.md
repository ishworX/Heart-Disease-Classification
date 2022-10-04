# Heart-Disease-Classification
Heart Disease Classification using ML.

Q1: Layout your question of interest. Remember to state your question as clearly and simply as you can (Mark 1), and what your ideal outcome would be (Marks 1). 
I am using the same dataset from Project 2 where I predicted Heart Disease with Fasting Blood Sugar. And for this project I am checking if Fasting Blood Sugar and other factors from the dataset causing Heart Disease. 
The ideal outcome is to see the coorelation between the chest pain, resting blood pressure, cholestrol and their effect on Heart Disease.

Q2: Identify and describe what data sources you'll use (Marks 1). Make sure to talk about one of the following: data accuracy, reliability, validity, or sample selection. (Marks: 1) 
==>I am using a dataset that provides the classification of heart disease provided by the Cleveland Clinic Foundation. This data contains data on 13 potential predictors of heart disease, as well as the diagnosis received by the patient. Talking about the reliability the dataset only has data of 303 patient which might not be enough data to make the best prediction. The "target" field has 1 and 0 value which is not clear that if the patient died due to Heart Disease or if that refers to the presence of heart disease in the patient. Since we dont have a lot of information on the target field and looking at other columns, it is more logical to assume that 0 means that the patiend does has heart disease and 1 means the patient does have. 


Q3: Layout what kind of ML problem you are facing and what kind of model you'll use to answer it (eg., is it unsupervised or supervised learning, and is it classification or regression). Make sure to say why. (Marks 1) 
I am using heart disease dataset. Since, its labelled data and I am predicting the final outcome based of the factors of the patents data, it will be a supervised learning. It is a Classification Model and I will be using a Random Forest to build my model because I am predicting if the predictors on the patients will determine the cause of Heart Disease or not.

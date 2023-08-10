# End to End Student Performance Prediction Project
## Problem Statement
 To understand how the Students Performance or test Scores are affected on various features like Gender,Parent level of Education,Lunch and Test Prepration course based on this we can Predict what will be the Subject score.
 
*Phase 1*:
- End goal(Problem Statement):
  
1. The main goal is Predict the Student Performance with the help of predictive machine learning models.
2. This is regression based Problem.So we have to predict only Scores.That will linearly Increasing or Decreasing.

*Phase 2*:
- Components:
1. Data_Ingestion-:In this step we read the data and divide into Train and Test.This file is all for Training model Purpose and also for validation.
2. Data_Transformation-:Defining seperate Categorical Column and Numerical Column.Convert some Categorical features into Numerical features with help of One Hot encoder and label Encoder.
3. Model_trainer-:In this step we are specially train model.Use various Machine Learning algorithms to train the model and select best accuracy model.

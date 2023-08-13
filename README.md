# End to End Student Performance Prediction Project
## Problem Statement
 To understand how the Students Performance or test Scores are affected on various features like Gender,Parent level of Education,Lunch and Test Prepration course based on this we can Predict what will be the Subject score.
 
*Phase 1*:
- End goal(Problem Statement):
  
1. The main goal is Predict the Student Performance with the help of predictive machine learning models.
2. This is regression based Problem.So we have to predict only Scores.That will linearly Increasing or Decreasing.

*Phase 2*:
- Logger and Exception:
  
 1.Exception-:The exception has occured and the file will raise and show where the error is occur.Also it shows which line number exception occur that will 
   helful for identifying your error easly.
  
 2.logger-:We get logging info in the text file.on which time,date your log will created it will show and log will created in working directory.

 3.Utils-:Reading the dataset from any database or API.


*Phase 3*:
- Components:
1. Data_Ingestion-:In this step we read the data and divide into Train and Test.This file is all for Training model Purpose and also for validation.
2. Data_Transformation-:Defining seperate Categorical Column and Numerical Column.Convert some Categorical features into Numerical features with help of One Hot encoder and label Encoder.
3. Model_trainer-:In this step we are specially train model.Use various Machine Learning algorithms to train the model and select best accuracy model.

*Phase 4*:
- Pipeline:
 1. Train_Pipeline-:In this file we all the code for training pipeline and from this pipeline we can try to trigger or call the componets.

 2. Predict_pipeline-:Predicting new the new data.

*Phase 5*:
- Creating Streamlit based web app:
  
1.Writing code for  web app which is created by Python-Streamlit library with 
     interactive UI.
     
2.Inserting ML model in software development and creating fields as input and summarizing 
    into prediction state.
    
3.Running the web app and trying with different inputs.

*Phase 6*:
- Deployment for end-users:

1.Deployed this Streamlit web app on render cloud platform.

2.Demo of these web app is [here](https://ml-project-student-performanceprediction.onrender.com/)

## [Run by yourself](#run-by-yourself)🏃🏽
1. Clone the repository: `gh repo clone Sourabh0921/Student_Performance_Prediction`
2. Create a virtual enviornment: `conda create -p your_env_name python==3.8 -y`
3. Activate virutal enviornment: `conda activate your_env_name/`
4. Install dependencies: `pip install -r requirements.txt`
5. In a **notebooks/** folder you can see `.ipynb` files which have been used for Data Analaytics, Model Building and evaluation.
6. **app.py** is an entry file to run Flask App: `python app.py`





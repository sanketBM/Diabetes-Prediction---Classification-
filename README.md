## End-to-End Diabetes Prediction Application using Machine Learning (MINI Project)  


### Table of Content
  * [Overview](#overview)
  * [Learning Objective](#Learning-Objective)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)
  * [To Do](#to-do)
  * [Installation](#installation)
  * [Run](#run)
  * [Bug / Feature Request](#bug---feature-request)


### Overview 
In this project, the objective is to predict whether the person has Diabetes or not based on various features suach as 
- Pregnancies
- Insulin Level
- Age
- BMI.
The data set that has used in this project has taken from the [kaggle](https://www.kaggle.com/) . "This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage." and used a simple [random forest classifier](https://en.wikipedia.org/wiki/Random_forest).   


### Learning Objective
The following points were the objective of the project . If you are looking for all the following points in this repo then i have not covered all in this repo. I'm working on blog about this mini project and I'll update the link of blog about all the points in details later . (The main intention was to create an end-to-end ML project.)  
- Data gathering 
- Descriptive Analysis 
- Data Visualizations 
- Data Preprocessing 
- Data Modelling 
- Model Evaluation 
- Model Deployment 

### Technical Aspect 

- Training a machine learning model using scikit-learn. 
- Building and hosting a Flask web app on Heroku. 
- A user has to put details like Number of Pregnancies, Insulin Level, Age, BMI etc . 
- Once it get all the fields information , the prediction is displayed on a new page . 
### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg) 

[<img target="_blank" src="https://github.com/scikit-learn/scikit-learn/blob/master/doc/logos/scikit-learn-logo-small.png">](https://github.com/scikit-learn/)
<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/heroku.png" width=170>
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/numpy.png" width=170>
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/pandas.jpeg" width=170>

### Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/issues) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/issues/new). Please include sample queries and their corresponding results.


### Installation 
- Clone this repository and unzip it.
- After downloading, cd into the flask directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute the command: python app.py




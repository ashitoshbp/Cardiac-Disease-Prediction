**Cardiac Disease Predictor: An effective machine learning algorithm for predicting risk of cardiac diseases.**
---------------------------------------------------------------

Ashitosh Phadatare and Dhiraj CD

## **Cardiac Disease Predictor**
### <a name="overview"></a>**Overview**
A simple web application which uses Machine Learning algorithm to predict the heart condition of a person by providing some inputs about the person health like age, gender, blood pressure, cholesterol level etc built using Flask.

<a name="motivation"></a>**A Demo of the Web App :**

Input values Webpage:

![input1](https://github.com/ashitoshbp/Cardiac-Disease-Prediction/assets/107021261/b95d52f8-1948-47b0-bd46-98ca3d103b7b)

![input2](https://github.com/ashitoshbp/Cardiac-Disease-Prediction/assets/107021261/e8823724-9349-4d27-932c-2ebf0c0d9d20)

*Result Webpage:*

![output1](https://github.com/ashitoshbp/Cardiac-Disease-Prediction/assets/107021261/7850a1c7-10ea-47f3-87ed-181b9675fdbf)


This Project is mainly divided into two parts:

1. Exploring the dataset and traning the model using Sklearn.
1. Building and hosting a flask web application.

**About the folders in submitted zip file :**

- Experimental results and screenshots are in their respective folders and source code for ML model is used to get the PKL files for the different models we are using.
- Project consist app.py script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- prediction.py contains code to build and train a Machine learning model.
- *templates* folder contains two files main.html and result.html which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.
- *static* folder contains file style.css which adds some styling and enhance the look of the application.
### <a name="deployement-on-heroku"></a>**Deployement on Heroku**
Install Heroku CLI as this makes it easy to create and manage your Heroku apps directly from the terminal. You can download it from [here](https://devcenter.heroku.com/articles/heroku-cli).

next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.
### <a name="technologies-used"></a>**Technologies used**
[](https://www.python.org/)

[](https://www.heroku.com/)

![Flask](Aspose.Words.336d64dc-30dd-4d1d-bd5b-ff20eecd6cff.004.png)
###
### <a name="future-work"></a>**Future work**
- improve model performance.
- Add more better styling to the user interface.


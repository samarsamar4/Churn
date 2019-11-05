# Customer Churn Prediction and Reason-for-leaving Prediction using Machine Learning

We have built a sample prototype to demonstrate how we will develop real industry level solutions. This prototype  helps to identify  about-to-withdraw customers  and act accordingly to ensure that the bank can take the best-possible course of actions. Also the prototype predicts the possible reasons of leaving for a customer which may give a better picture of customer thoughts.

The software (web-app) provides the following features: 

1. Create a *user-friendly* interface which will help DHFL with clear and easy-to-interpret visual data. 

2. Predict probability of a current customer to leave DHFL ranging from 0 to 1 
   where 0 will denote that customer will never leave DHFL and 1 will denote that customer is definitely going to leave DHFL. 
   
3.  Provide quick & on-demand data of top percentage of people likely to leave . Enables user to streamline their focus on required number of people . However choosing to predict for any customer from the data is always an option . 

4. Show all details , prediction of probability of a customer leaving DHFL along with its graph.
   Also show probability of different reasons of leaving for each customer and display easy-to-interpret pie-charts demonstrating each reason for in-depth analysis . 
This pie-chart graph shows that if probability of churn becomes true and customer really leaves, then what factors will contribute to  his/her leaving the organization, i.e. , reasons for leaving and it will show probability of each reason contributing to his/her withdrawal from services of organization.


Our web-app uses pre-loaded ```.h5``` models for prediction . These ```.h5``` models are built on our local machines using Python.
The models are based on *Keras and Neural networks* . So we need Keras and other Machine Learning libraries on our web environment to 
load this pre-defined models.
In our live web-app we have already made the environment.If you want to know how our models are trained on local machines and you want to see the working & code of models, check the code of ```howmodel1isbuilt.py``` and ```howmodel2isbuilt.py```


## How to run locally 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Pre-requisites

* Creating a virtual environment using [Anaconda](https://www.anaconda.com/download/). If you need to create your workflows in Python and keep the dependencies separated out or   share the environment settings, Anaconda distributions are a great option.

The following main Python-based libraries have been used :

* ```Flask```
* ```Numpy```
* ```Pandas```
* ```Tensorflow```
* ```Keras```

which will be installed during setting the environment.

Provided the requirements are already installed in your system , you can simply execute the .py script named ```flask_app.py```
However, for future deployment purposes it is essential to create a virtual environment.

#### Step 1 : Main Directory
Go to command prompt/terminal (for Linux users) and change to the project as the default directory.
Example: If current path is ```C:\Users\name>```
change to ```C:\Users\name>cd Desktop\flasksite```  (if downloaded to Desktop)

#### Step 2 : Create environment
Create a conda environment using ```conda create -n env```
This will create an empty Python environment with name ```env``` . 
Activate using ```activate env```
To exit from the virtual environment , simply execute ```deactivate env ```

#### Step 3 : Install required libraries
Anaconda distribution comes with many default downloaded libraries which the user can directly , however to efficiently manage the
environment , manually install libraries.
A simple way would be to use ```pip``` - Python default package manager
```pip install [nameOfPackage]```
Install the libraries specified in pre-requisites
Example:
* ```pip install flask```
* ```pip install numpy```

For more information about ```pip``` you can refer [documentation](https://docs.python.org/3/installing/index.html)

#### Step 4 : Execute script
When all python dependencies are installed , simply execute the .py script named ```flask_app.py```  
```python flask_app.py ``` in the cmd prompt should do the task.
Follow the link generated, and the flask code should be up and running !

## Creator
Samar Chebbi



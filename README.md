
![Boston Houseing market](https://i.insider.com/629a3ba659963a00189e3f4d?width=700)

![](https://img.shields.io/badge/python-3.8-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.4-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.21.2-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-blue)
![sickit](https://img.shields.io/badge/scikit--learn-compatible-orange)
### Boston Housing Pricing Prediction
This project builds a regression ML model on Boston Housing data and predicts a price based on the input. It includes steps for data loading, preprocessing, model training, evaluation, and prediction.

### Software And Tool Requirements

1. [Github Account](https://github.com)
2. [Heroku Account](https://www.heroku.com/)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

#### Create a new Environment for the project
```
conda create -p venv python==3.7 -y
```

#### Create a new requirement.txt file which has all the dependencies 

#### Install the requirement.txt file using pip
```
pip install -r requirements.txt
```

#### Git Commands in Order
1. git config --global user.name \<name\>
2. git config --global user.email \<email\>
3. git add \<file\>
4. git status
5. git add . 'Adds all files to commit'
6. git commit -m 'message to commit'
7. git push origin main

#### Create an app for taking in request and outputting results

#### Create a postman json file for accepting the input

#### Call in request from the [Postman](https://www.postman.com/)

#### Create a HTML file to accept the request

#### Create a Procfile for [Heroku](https://www.heroku.com/)

#### Deploy the app on Heroku using GitHub

#### Create a base image on the Dockerfile

#### Setup GitHub actions with description for this project

### Data Preparation
Creating a dataframe with the independent variables. In this case, our feature names are independent variables.

#### Exploratory Data Analysis
Correlation data where we need to check for correlation between the Independent vs Dependent features and between interdependence Independent Features themselves.

#### Model Training
For this analysis, we will be using the Linear Regression Model.

### Prediction on a Single Dataset
We can further use this model to do prediction on a single dataset which can be a user input or a new dataset.

### Pickling the Model File for Deployment
Pickle the model file for deployment and load it using the pickle library for predictions.

#### Usage
Run the Python script to process the data, train the model, and output job recommendations. The script includes functions for predicting house prices based on input features.

### Customization
You can customize the project by:
- Updating the datasets with real-world data.
- Modifying the feature engineering steps to suit specific criteria.
- Adjusting the model training and evaluation process.

### License
This project is open-sourced under the MIT License. Feel free to use and modify it for your Boston Housing Price Prediction needs.

---
*Note: This project is a demonstration and should be adapted based on specific data and requirements.*

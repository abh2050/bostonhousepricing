### Boston Housing Pricing Prediction
This project builts a regression ML model on Boston Housing data and predicts a price based on the input.

### Software And Tool Requirements

1. [Github Accounts](https://github.com)
2. [HerokuAccount](https://www.heroku.com/)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new Environment for the project
```
conda create -p venv python==3.7 -y
```
Create a new requirement.txt file which has all the dependencies 

Install the requirement.txt file using pip
```
pip install -r requirements.txt
```
Git Commands in Order
1. git config --global user.name
2. git config --global user.email
3. git add <file>
4. git status
5. git add . ' Adds all files to commit'
6. git commit -m 'message to commit'
7. git push origin main

Create an app for taking in request and outputting results

Create a postman json file for accepting the input

Call in request from the [Postman](https://www.postman.com/)

Create a HTML file to accept the request

Create a Procfile for [Heroku](https://www.heroku.com/)

Deploy the app on the Herkoku using the github

Create a base image on the Dockerfile

Setup the github actions
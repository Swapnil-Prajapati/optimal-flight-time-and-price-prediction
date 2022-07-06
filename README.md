
# Optimal Time Predicting For Flight Pricing


## Table of Contents

  * [Demo](#demo)
  * [Overview](#overview)
  * [Installation](#installation)
  * [Deployment](#deployment)
  * [Directory Tree](#directory-tree)
  * [Technologies Used](#technologies-used)
  * [Future scope of project](#future-scope-of-project)


## Demo

Link: https://optimal-flight-time-prediction.herokuapp.com/predict





## Overview
This is a Flask web app which predicts optimal time to book a flight.
## Objective

As someone who purchases flights frequently, I would like to be able to predict when the best 
time is to buy in order to get the best deal. I chose to look at flights in a
short- ‐term range, which I defined as up to three weeks in advance.
Given some information about the flight and the time
of request, we should be able to predict whether we should book the flight or wait.


## Installation
The Code is written in Python 3.9.12. If you don't have Python installed you can find it [here](https://https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:
```bash
    pip install -r requirements.txt
```

## Deployment
There are many cloud platforms out there but the one i used was Heroku. 
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.
![Heroku](https://github.com/Swapnil-Prajapati/optimal-flight-time-and-price-prediction/blob/main/Screenshots/heroku.JPG?raw=true)



## Directory Tree
```bash
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── MLpart.py
├── xgboostregressor.pkl
├── requirements.txt
├── runtime.txt
```
## Technologies Used
![madewith](https://raw.githubusercontent.com/Swapnil-Prajapati/optimal-flight-time-and-price-prediction/f35412262d3b5a9e1668c56f007abaf4efa9bcb7/Screenshots/madewith.svg)

![Flask](https://github.com/Swapnil-Prajapati/optimal-flight-time-and-price-prediction/blob/main/Screenshots/flask.png?raw=true) 
![Gunicorn](https://github.com/Swapnil-Prajapati/optimal-flight-time-and-price-prediction/blob/main/Screenshots/gunicorn.png?raw=true)
![Sklearn](https://github.com/Swapnil-Prajapati/optimal-flight-time-and-price-prediction/blob/main/Screenshots/scikit.png?raw=true)


## Future scope of project
- According to given optimal time build flight reccomender system
- Improvement on app.py and front-end.
- Optimizing Machine Learning Model and look for better substitute in future.

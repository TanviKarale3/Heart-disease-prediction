## Heart-Disease-Prediction 

<p align="left"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRc7Lwj4uhxSTeHgGIq6_MWcKbUgNz2KYKnbmeEzhCzMoUXD_O8FKpJ8BP4HhcSIrjMimY&usqp=CAU"="tanvikarale3" /> </p>

### Overview

A simple web application which uses Machine Learning algorithm to predict the heart condition of a person by providing some inputs about the person health like age, gender, blood pressure, cholesterol level etc built using `Flask` and deployed on `Heroku`.

### Motivation 

As being a Data and ML enthusiast I have tried many different projects related to the subject but what I have realised is that Deploying your machine learning model is a key aspect of every ML and Data science project. Everything thing I had studied or been taught so far in my Data science and ML journey had mostly focused on defining problem statement followed by Data collection and preparation, model building and evaluation process which is of course important for every ML/DS project but what if I want different people to interact with my models, how can I make my model available for end-users? I can't send them jupyter notebooks right!. That's why I wanted to try my hands on complete end-to-end machine learning project. 

* You can access the project from here

https://github.com/TanviKarale3/Heart-disease-prediction/blob/main/heart%20resources/heart_disease.gif.gif

**A Demo of the Web App :**

![Heart_disease](https://github.com/TanviKarale3/Heart-disease-prediction/blob/main/heart%20resources/heart_disease.gif.gif)
 
 
 ### Technical Aspect
 
 This Project is mainly divided into two parts:
 
 1. Exploring the dataset and traning the model using `Sklearn`.
 2. Building and hosting a `flask` web app on `Heroku`.

**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- `prediction.py` contains code to build and train a Machine learning model.
- *templates* folder contains two files `main.html` and `result.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.  
- *static* folder contains file `style.css` which adds some styling and enhance the look of the application. 

### Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

```
pip install -r requirements.txt 
```

### Run 

*To Run the Application*

```
python app.py
```

### Deployement on Heroku

### Future work 

- improve model performance.
- Add more better styling to the user interface.

### credit 

- A big thanks to [Ajay Gaddicha Sir] our mentor of this project.

**Some Useful Resources**

- **Flask Quickstart Documentation** : [https://flask.palletsprojects.com/en/1.1.x/quickstart/](https://flask.palletsprojects.com/en/1.1.x/quickstart/)

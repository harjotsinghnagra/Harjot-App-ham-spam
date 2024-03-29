# Harjot-App-Ham--Spam
It is a text-classification app which detects whether the message/email is spam or not. I've used Naive-Bayes along with NLP (TF-IDF, Bag of Words and more). <br>
In order to perform an experiment I've combined two datasets (Enron email spam/ham and SMS spam classification) into one to gather more data. [See this notebook](https://github.com/harjotsinghnagra/Harjot-App-ham-spam/blob/main/machine_learning_section/SpamHam.ipynb) to get what I am saying.
<br>
To check out this project in action I've deployed it on heroku
[Click on this link to check](https://span-or-ham.herokuapp.com/)

__Live Link__ - https://span-or-ham.herokuapp.com/

### Built With

1. Django 2.1
2. Python 3.6
3. Scikit-Learn
4. Numpy
5. Pandas
6. Matplotlib
7. Seaborn
4. HTML5
5. CSS
6. Bootstrap-v4
7. Love
<br>
<br>
<h2> FLOW CHART </h2>

![image](https://user-images.githubusercontent.com/80465715/137627786-a75d6ec5-aaeb-4398-88a1-6f5754b77db5.png)




<br>


<br><br>
<h2>IO Screenshots</h2>

![image](https://user-images.githubusercontent.com/80465715/137627450-b49a3720-0a77-4594-8c10-87c69fbb61cd.png)

![image](https://user-images.githubusercontent.com/80465715/137627465-12e700d3-d7db-4b14-961a-16e28d408287.png)




<br>

### Installing/ Things you need to install the Web App and how to set up the project locally?

1. Python3
2. Pip
3. Django(2.1)
4. Conda

#### Steps
- Make a virtual environment using "conda create -n envname python=3.6 pip"
- source activate envname (for mac/linux) | activate envname (for windows)
- Download or clone this repo by [git clone https://github.com/harjotsinghnagra/Harjot-App-ham-spam.git](https://github.com/harjotsinghnagra/Harjot-App-ham-spam.git)
- pip install -r requirements.txt
- Run the app using python manage.py runserver

### Milestones for version 2
- Implement login and tailor experience for each user
- Collect the result reported by user for false classification of messages/email
- Model will self-learn from the reported data




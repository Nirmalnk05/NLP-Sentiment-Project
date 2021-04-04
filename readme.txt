Medibuddy health assist 

Intorduction 
Medibuddy health assist is a platform to assist customers and doctors in order to know a drug and related conditions for which it can be used, vice versa as well as doctors can know the customers track record of conditions and the drugs prescribed by the assist.

Data 
Data for the assit used in sentiment mining was taken from the https://www.kaggle.com/jessicali9530/kuc-hackathon-winter-2018 which was the UCI ML Drug review dataset. The dataset is stored in a MySQL database and can be accessed using SQL queries. 

Tables used are:
1. Predvalue - This contains 4 columns. 
		a. predvalueid : Primary key of the table.
		b. disease  : the name of various diseases/ conditions.
		c. drugname : the drug which can be used to cure a particular disease.
		d. predmean : the final predicted value which is used to rate the drugs.

The data in this table comes after the model has run to predict the scores.

2. CustInfo - The table that stores customer information such as custid, firstname, lastname, age, symptom, drug, and pkcustid.


Usage

Follow the below steps to install the project and use it on your system:

1.Download the complete folder NLP Project in your system.
2.Open your MySql workbench, create a d.b by the name nlp.
3.Create the tables custinfo and predvalue 	
4.Open the sql files which contain the insert queries for the tables to insert the data into the table .
5.Download an IDE(preferably pycharm) with django and python into it.
6.Create a virtual environment by the command mkvirtualenv myproject(only for pycharm).
7.Install the below dependencies in the django virtual environment:
   7.1 pip install numpy
   7.2 pip install django-pandas
   For any other queries refer https://pypi.org/project/django-pandas/.
8.Open the project folder into pycharm.
9.Now run the server once you have set up all the libraries and dependencies by python manage.py runserver.
10. Go to http://127.0.0.1:8000/, it should run.

Reach out to Tushar Mehta (+65 84590936) in case of any other concerns.
		
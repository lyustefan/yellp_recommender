# Final Project: Yelp Recommender
Term: Spring 2018

+ ** Author ** 
	+ Yang Lyu (yl3795)

+ **Link to deployed Shiny-App:**
http://zh2290.pythonanywhere.com/

## Introduction:

In this project, we used the yelp challenge dataset to deploy a database-based end-to-end website application using Pythonanywhere cloud environment. The recommendation engine includes collaborative filtering(user-user, item-item), content-based (NLP representation), SVD, and hybrid model to recommend restaurants based on users' preferences.


## Motivation:
Many people nowadays use Yelp to find the restaurants near them. But Yelp does not really provide recommendation to users based on their experience in the past. Our website application serves as an complimnent to Yelp's core functionality.

+ **Our Method:**
	+ **Data Preprocessing.**
		+ We filtered out all the restaurants in Las Vegas as an subset to run recommendation algorithm

	+ **Recommendation Engine.**
    + Built different recommendation engine and evalute using recall/precision

	+ **User Interface.** 
	 	+ Editted HTML/CSS file and deployed application on Flask

+ **Our App:**
	+ **Introduction: Project Framework**
![intro](lib/intro.png)
	+ **Unemployment Rate: Unemployment rate by states and years**
![unemploy](lib/unemploy.png)

	


## Data Sources:
+ From Yelp Challenge Dataset website: https://www.yelp.com/dataset

## Contribution statement: 

Team members: Zhejing Hu, Yang Lyu, Chi Ma, Lan Jiang


```
proj/
├── app/
├── img/
```
Please see each subfolder for a README file.



# Module 

Title : Hey Where To Eat (HWTE) -> Simple API Intergration

Version : 1

## Introduction
---
Food has become acculturated in our generation mindset. While the act of choosing what one would eat determine the perception and thinking behaviour of that person and his surrounding. Thus, along the numerous grow of food stalls especially in this region, civilization perceptive thinking has been blundered with confusions backing up with such huge buying power. Needless saying, human has become indecisive in the very basic aspect of life (eating). 

By the decree of the "lord" , you have been summoned to this world to bring mankind into a more structured and organized path, while preserving the self preferences at the same time accomodate to the societal need in making eating decisions. 

You as a desktop/web application developer has been appointed to develop a system that will select the food stalls to eat within the area. 

## Description of project
---
Your task is to build an application that will, learn the user preferences, randomized the food stall, and make a solid suggestions based on all the important parameters like: stalls condition ,crowded levels, operating hours, self preservations, distance walk and more. 

##### Basic features

>- A user can login (and logout) into the system on the start page of the application.
>- After login there are the following links to sub-pages: “Nearest Food Stalls”, “History”. 
>- These links are always visible on the top part of the page while logged in.

##### Integration Features

>- On the page "Nearest Food Stalls", the user will see a maps embeded with a circle radius ring of 5km distance from user current position. 
>- In that ring the top 10 available (in term of operating hours, preferences, and all those points above) food stalls will appear. 
>- At below of the maps, there will be a button "Suggest to me" allowing the user get a solid suggestions out of the listed stalls and at the same time cater to the user prefrences.
>- On the page "History", the user will see a list of the selected stalls based on his previous dine sessions. 

##### Federated Learning Features

>- Since this is a method learning on user preferences, you should not be training your model to be too generalize as that will ignore the very aspect of preference itself. Thus you are requried to train with federated learning, in which the generalize model will be hosted in the cloud and learn while update the distributed models weight on each of the users devices.

## Requirement
---
- Basic ML, basic of GCP ML Engine
- Understanding How to use API to integrate with the application. 
- Web programing language (html, css, js)
- Hybrid desktop application (electron) 

## References
---
```
- Invigour Eating pattern 

```

## Contributors & Authors
---
1. [Neonexxa](https://github.com/neonexxa)

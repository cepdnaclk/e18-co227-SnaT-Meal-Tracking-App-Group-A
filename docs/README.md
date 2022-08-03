---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e18-co227-SnaT-Meal-Tracking-App-Group-A
title: SnaT Meal Tracking App
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# SnaT Meal Tracking App

---

## Team
-  E/18/013, Ravindran Abilash, [e18013@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/128,Raveendran Hariharan , [e18128@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/366, Yogashwaran Thulasiyan, [e18366@eng.pdn.ac.lk](mailto:name@email.com)

## Table of Contents
1. [Introduction](#introduction)
2. [Technology Stack](#technology-stack)
3. [Solution Architecture](#solution-architecture)
4. [Features](#features)
5. [Links](#links)

---



# Introduction

&emsp;SnaT(Snap and Track) is a first application available in both iOS, and Android that is built based on Sri Lankan food style so that Users can maintain their meal progress and maintain their health by taking AI assisted food statistics.<br/>

&emsp;Promoting mHealth for the betterment of community health is an ongoing intervention which is timely. The world is passing through a digital era, and Sri Lanka has also shown a rapid tendency towards this in recent times. This is currently being used mostly to create a healthy dietary modification in the community. According to the literature, person informatics and self-tracking systems are most useful to proceed personal dietary modification and its ths self reflection towards healthy eating. For this, the most widely used meal tracking application in the world is new to Sri Lanka. Also, self-reflecting on one's eating pattern by tracking the photos of the food one has taken is another unique thing.<br/>

&emsp;Therefore SnaT is a novel meal tracking app which has been developed in a Sri Lankan context to fulfill those identified gaps in the community. Currently SnaT has been developed in which to track meals in adult population and it is  consisting with a very simple concept of balanced meal by all food groups which is very easy to understand by the normal population spontaneously. Therefore, SnaT, combined with digital technology , will make a great contribution to promoting a healthy diet in the Sri Lankan community.


<p align="center">
  <img width="500" src="https://aaps.ca/wp-content/uploads/Aug-6-sport-and-nutrition-training.jpg" alt="Taking picture of food">
</p>




# Technology Stack

These technologies were used to create the application.

  ### Flutter 
  
  Why Flutter?
  - Available in many platforms for the same code base
  - Various Widget Libraries
  - Hot Reload
  - Easy to integrate with all Google services
  ### Firestore and Firebase 
  
  Why Firestore and Firebase?
  - Has both real time, and No-SQL database
  - Scalability, and Security
  - Cloud functions
  - Handling concurrent users
  - Provides all type of authentication services

  ### Git
  
  Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. 


<p align="center">
<img src="./images/technology_stack.png" width="700" height="430"></p>







# Solution Architecture

<p align="center">
  <img width="900" src="https://user-images.githubusercontent.com/73680106/176661576-ca4a83ce-e40a-40f3-ac42-a2d733c445e0.png" alt="drawing">
</p>


<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73664068/176867110-5b655532-0b7f-4265-8002-f80434fbffec.PNG" alt="storage">
</p>





# Features

### Login 
This app provide two sign in methods. User can first sign up using an email and a password and then they can proceed with sign in.Other than that user can simply use google sign in method.

How does it work?

To sign in, first the app should get authentication credentials from user. For this app credential can be email and password or the oAuth token from google. Then the app pass these credential to Firebase Authentication SDK.After that it will verify those credentials and return respose to the app.Now, the app can access the user's basic profile information.

<img src="https://user-images.githubusercontent.com/73664068/176868525-1bbaa1f2-7c06-456c-ac37-6b295261776f.jpg" width="300" />


### User Registration 
For the registration purposes, the user is required to enter username, date of birth, gender, height and weight.This details use for other features.

Ex:- BMI calculator

<img src="https://user-images.githubusercontent.com/73664068/176868581-04c3f756-8d95-4573-b20d-5f61ceefc771.jpg" width="300" /> 

### BMI calculator 
* Show the BMI value of the user.
* It gives additional feedback about BMI using gender and age.

<img src="https://user-images.githubusercontent.com/73664068/176869561-27bf16ee-6508-4773-9ebb-5db62918a562.jpg" width="300" />


### Maintain images  of meals
* Users can select the date ,meal type and upload the images.
* Users can open the camera  from the app  and upload  the image. These images store in cloud space.
* The app loads images from the cloud storage and show them in a attractive gallery.


<img src="https://user-images.githubusercontent.com/73664068/176869895-720b7bd8-c395-434f-9bea-105afff19a1f.jpg" width="300" /> 
  

### App Notification
* If user forgot to add a meal, this will pop up a notification.

<img src="https://user-images.githubusercontent.com/73664068/176871011-41fc0255-499b-4fe1-96ec-f6e31af034df.jpg" width="300" /> 

### Language Translation 
* App supports English(US), Sinhala & Tamil.



<video src='https://user-images.githubusercontent.com/73680106/176605718-151da18b-c280-426a-8ec4-26e54d5f44ea.mp4' width=900/>




## Links

- [Project Repository](https://github.com/cepdnaclk/{{ page.repository-name }}){:target="_blank"}
- [Project Page](https://cepdnaclk.github.io/{{ page.repository-name}}){:target="_blank"}
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

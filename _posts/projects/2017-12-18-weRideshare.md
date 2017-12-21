---
layout: page
title:  "WeRideShare"
date:   2017-12-18 14:38:00 -0500
categories: projects
---

For my Android class, I was part of a 3-person team which created WeRideshare. The goal of the app is to provide an easy-to-use and consistent system which connects users with similar commutes and facilitate carpooling. 

#### Tech Stack
* Java
* Android SDK
* Firebase Authentication + Cloud Messaging + Realtime Database
* Goolge Maps Android API
* Google Places Web API
* Google App Engine

#### Highlights
* The architecture was done through group effort, but I was responsible for coding all Firebase functionality
* Firebase Cloud Messaging and Notifications to send messages and push notifications to respective users
* In order for that to work, I wrote a standalone servlet application hosted on Google App Engine to route messages
* Firebase Authentication was used to manage user credentials

#### Screens

<figure>
<img src = '/assets/wrs-splashScreen.png' height='400px' alt='Splash'>
<figcaption>Splash Screen</figcaption>
</figure>

<figure>
<img src = '/assets/wrs-login.png' height='400px' alt='Login'>
<figcaption>Login</figcaption>
</figure>

<figure>
<img src = '/assets/wrs-firebaseAuth.png'>
<figcaption>Snapshot of user (rider/driver) credentials</figcaption>
</figure>

<figure>
<img src='/assets/wrs-realtimeDatabase.png' height='350px'>
<figcaption>Snapshot of messages</figcaption>
</figure>

<figure>
<img src='/assets/wrs-locations.png' height='350px'>
<figcaption>Locations Activity</figcaption>
</figure>



[Find it on GitHub]({{'https://github.com/huyenbnguyen/mobile-final-project.git'}})
---
layout: post
title:  "Wave Radio (WIP)"
date:   2017-12-18 13:46:00 -0500
categories: projects
---

For my WebWare class project, I teamed up with one of my MQP mates to create WaveRadio. The goal was to develop a crowd-sourced radio app, based on the Spotify platform. In summary, users would get music recommendations based on what was currently being played by the Spotify listeners around them. Ideally, parameters such as the catchment radius and refresh rate can be set to the user's preference. However, for our prototype, users have the option of listening to songs from their Spotify playlists since there might not be enough data for the recommendation engine. 

#### Tech Stack
* Java
* SparkJava
* JavaScript
* HTML5 & CSS3
* Heroku
* Postgresql
* Spotify Web API
* Google Maps API 

#### Highlights
* I chose to develop the app server using the SparkJava API rather than the popular Node.js primarily due to familiarity and experience with Java
* Heroku was the most cost-effective and convenient hosting platform, and contained an integrated Postgresql service which simplified database interactions

#### Screens

<figure>
<img src='/assets/wave-homePage.png' height='350px' alt='Home'>
<figcaption>Home Page</figcaption>
</figure>

<figure>
<img src='/assets/wave-radio.png' height='350px' alt='Radio'>
<figcaption>Radio</figcaption>
</figure>

<figure>
<img src='/assets/wave-songSelection.png' height='350px' alt='Song Selection'>
<figcaption>Song Selection</figcaption>
</figure>

<figure>
<img src='/assets/wave-musicPlaying.png' height='350px' alt='Music Playing'>
<figcaption>Music Playing</figcaption>
</figure>


[Website]({{'https://wave-radio.herokuapp.com'}})
<br>
[Find it on GitHub]({{'https://github.com/mrampiah/CS4241.git'}})
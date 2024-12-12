---
layout: default
modal-id: 2
date: 2020-10-22
img: asteroids-start.png
alt: image-alt
project-date: October 2020
client: School Project
category: 2D Game development
description: The primary goal of this project was to learn about 2D game implementation in C++. We learned about 2D collision detection; Verlet integration for movement; and vector graphics. I decided to approach this project by changing some aspects of the original game to make it different. See below for more details
sections:
  - header: "Full Playthrough"
    video: "https://www.youtube.com/watch?v=u0wxGXvl3yc"
    text: "This project was my first time working with vector graphics. I decided to customise my graphics by making them different than the original game. This includes the alphabet which I created myself by plotting the vectors. The split asteroids are created by dividing the polygons into smaller pieces."
  - header: "Convex Polygon Generation"
    img: "img/portfolio/asteroids-convex.gif"
    text: "I decided to make my asteroids' shapes randomised by generation convex polygons. So, I created a simple algorithm which uses a random angle to determine how much a vector should be rotated. Then we randomly set the length between a certain range."
  - header: "Collision Detection"
    img: "img/portfolio/asteroids-collision.gif"
    text: "I implemented collision detection for my generated convex polygons. The ship turns blue when collision is detected. This was done by determining if the ship lies within a certain radius of the centerpoint of the asteroids."

---
---
layout: project
type: project
image: images/tama.png
title: Tamagotchi
permalink: projects/tamagotchi
# All dates must be YYYY-MM-DD format!
date: 2017-05-01
labels:
  - C++
  - GitHub
  - OOP
summary: My team developed a single-player game to simulate caring for a virtual pet for a final project in EE 205.
---

<img class="ui medium right floated rounded image" src="../images/egg.png">
For this project, my team and I programmed a single-player game in C++ to simulate caring for a virtual pet based on the popular toy [Tamagotchi](https://en.wikipedia.org/wiki/Tamagotchi).  After learning about object-oriented programming in our course that semester, we utilized classes to contain the details of the shop items and of each tamagotchi including its name, evolution, age, wealth, health, hunger, and mood. 

### Instructions-
To start the game, you enter a name for your tamagotchi.  After a short animation, (created by quickly changing between two sprites by using a wait function and system commands to manipulate the display), you are shown the status of your tamagotchi, which starts off healthy, full, and in a good mood along with a starting amount of $5, which you can later spend.  You are also given a menu of actions to take care of your pet.  Those actions include: feed tamagotchi, play a game, go to the store, check inventory, check status, and next day.  We implemented two mini-games: a memory game and a guessing game.  The Memory Game requires that you correctly repeat a string of random characters of increasing length.  These characters are randomly selected using the srand function.  The Guessing Game requires that you correctly guess a randomly chosen value between 1 and 100 in a maximum of 6 tries.  After every guess, you get a hint telling you whether the number you guessed was too high or too low.  
<div class="ui medium rounded images">
  <img class="ui image" src="../images/game2.png">
  <img class="ui image" src="../images/game1.png">
</div>

### My experience-
My role was primarily as a tester and debugger of our program while also providing conceptual ideas about the structure of our tamagotchi game.  In addition, I provided the code for the guessing game mini-game.  Through this project, I was able to practice the object-oriented programming skills I developed that semester.  

Source: <a href="https://github.com/kekupua/WDK-Homework/tree/master/Final%20Project"><i class="large github icon"></i>WDK-Homework/Final_Project</a>

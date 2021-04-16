---
title: Sprint 1 Project - PoseMan
layout: page
---
## Inspiration
Every single coder suffers from "cant-stop-wont-stop", "how did is it 8 pm already?" coding sprees but breaks are needed, and here's a fun game to help us with it. Given that we are now spending more and more time in front of the screen it is important that we take care of ourselves with 5-minute breaks. PoseMan Gamify this

## What it does
Through a game of combined hangman meets pose, this game helps the play move around for a few minutes.
The game takes in webcam feed passes it to an ML model which transposes an animated SVG onto the screen.
The user needs to use his body to Guess letters for an object shown on the screen before time runs out.

## How we built it

- Given that the team consisted of Python and C++ developers we decided to do the application exclusively in -JavaScript.
- A pre-trained Tensorflow.js neural network called Posenet is used for detection of poses and transposing an animated SVG. 
- The second neural network was used for guessing the Words from poses. This required us to train models using images captured using the webcam. After this ML5.js library was used to make an interface with model and application.
- The entire application is bundled using parcel and a CI/CD pipeline to Netlify was set up which will automatically build and deploy app on pushing the staging branch.

## Challenges we ran into
- Making 2 neural networks run together in a browser
- A game has a lot more moving components, keeping track of changes and thinking of proper designs was challenging.
- Bundling and deploying introduced other set of challenges
- JavaScript Async programming was initially difficult 


## Accomplishments that we're proud of

- Asynchronous Programming in Javascript
- Bundling/minifying of application 
- CI/CD using Netlify and GitHub

## What we learned
- JavaScript
- Async programming 
- Machine Learning
- Tensorflow.JS and ML5.js
- Pretrained networks and training new models with output from another neural network

## What's next for PoseMan
Multiplayer abilities so you can compete against your fellow coders, you code together, you pose together. 
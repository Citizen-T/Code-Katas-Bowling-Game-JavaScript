Bowling Game: A Code Kata in JavaScript
=======================================
A JavaScript implementation of the Bowling Game code kata

This repository is intended to be used for practicing the Bowling Game code kata in JavaScript.  The master branch contains a skeleton project to get you up and running quickly.  The idea is to remove as much inertia as possible from the process to make it easy for you to get started with your daily code kata practice.

The Rules
---------
In Bowling Game, the challenge is to write a program that can correclty score, well, a bowling game.  If you are rusty on what exactly the scoring rules are, here's a quick guide.

- There are 10 frames
- In each frame, the player rolls up to 2 balls
- In each frame, the player can knock down up to 10 pins
- The player's score for that frame is the total number of pins knocked down
- If all 10 pins are knocked down with the first throw in a frame, that is called a "strike"
  - The player's score for that frame is 10 + the number of pins knocked down with the next two throws
- If all 10 pins are knocked down by the second throw, that is called a "spare"
  - The player's score for that frame is 10 + the number of pins knocked down with the first ball from the next frame
- The final score of the game is the sum of the scores from each frame

The Code
--------
If you want to use this repository to help you out with your own kata practice, there are a few things you need to know.

### Prerequisites
#### NPM
This project has a package.json file that lays out some dependencies that you'll need to install in order to get started.  The easiest way is to just run the `npm install` command.  

If you don't have NPM installed and configured, refer to the documentation at https://nodejs.org

#### Karma CLI
I like using Karma to automatically run my tests each time I save a source file.  To that end, I've configured this project so that all you have to do is run the `karma start` command.  In order for this to work you'll need to have the Karma CLI installed and configured.

See the Karma documentation at https://karma-runner.github.io/0.13/intro/installation.html

### Usage
#### Master Branch
Contains an empty template for practicing this code kata

1. clone this repository
1. cd into the repository directory
1. execute `npm install`
1. execute `karma start`
1. open src/Game.js
1. open test/GameTest.js
1. start coding

#### Solution Branch
The branch aptly named "solution" contains my solution to this code kata (as of this writing at least).  If you get stuck or you just want some reference point to judge your own solution against, check it out.

I make no promises that my solution is the best one.  It is just one of many possible solutions.
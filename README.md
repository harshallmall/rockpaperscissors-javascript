# Rock, Paper, Scissors Game – JavaScript

## What is Rock, Paper, Scissors ("RPS")?
- "RPS is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock" (a closed fist), "paper" (a flat hand), and "scissors" (a fist with the index finger and middle finger extended, forming a V). As RPS is a simultaneous, zero-sum game, it has three possible outcomes: a draw, a win, or a loss. Rock beats Scissors, Scissors beats Paper, and Paper beats Rock." 
- Rock Paper Scissors, https://en.wikipedia.org/w/index.php?title=Rock_paper_scissors&oldid=1088384363 (last visited May 24, 2022).

## Version Updates
- The 1st version of RPS will not include a Graphical User Interface ("GUI") and only runs inside the console.
- The 2nd version of RPS will improve upon the first via the addition of a GUI, buttons, and text.

## Problem Solving Checklist
### Step One – Identifying the Problem
### Problem
- Create a JavaScript program that runs in the console and plays a single round of RPS against the Computer. 
- The results of the game will be returned from a function call and not from the console.log() method.
### Step Two – Planning for Solving the Problem
### Questions for Planning
#### (1) Does the program have a user interface? 
- What will it look like? 
- What functionality will it have? 
#### (2) What inputs will the program have? 
#### (3) Will the user enter data or will it get input from elsewhere? 
#### (4) What is the desired output? 
- Given the outputs, what are the steps necessary to return the desired output?
### Step Three – Dividing and Conquering the Problem
#### Start a new Git repository for the project.
#### Create a blank HTML document with a script tag.
- Yes, I understand that the best practice is to link an external .js file.
#### Subproblem # 1 - Write a function named "computerPlay" that randomly returns either "Rock" or "Paper" or "Scissors" as a choice. 
- This function is used to make the computer play against the user. 
- I will use the console to make sure this function is returning the expected output before moving to the next step.
#### Subproblem # 2 - Write a second function that plays a single round of RPS. 
- The function will need to take two parameters - playerSelection and computerSelection. 
- The function will need to return a string that declares the winner of the round, e.g., "You Lose! Paper beats Rock." 
- The function parameter "playerSelection" will be case-insensitive, i.e., users can input text in any variation, e.g., "rock, ROCK, RocK."
- Return the results of the second function call, not to console.log() method. 
- What is returned will be used later in the game, so I will test this function by using console.log to see the results.
#### Subproblem # 3 - Write a third function called "game()" and call the "playRound" function inside of the function. 
- The playRound function is used in order to play a 5-round game that keeps score and reports a winner or loser at the end. 
- This is a good opportunity to use a loop to iterate through the entire code 5 times in order to play 5 rounds of the game at once.
- Use console.log() to display the results of each round and the winner at the end.
- Use prompt() to get input from the user.
---
## V2 Update

### Added GUI, Graphics, EventListener, and JS File

#### (1) Created three images with each image representing an option.
#### (2) Created GUI using Bootstrap and CSS.
#### (3) Updated JavaScript file - See comments in file.
#### (4) Merged separate branch and main on Git.
#### (5) Updated README.md

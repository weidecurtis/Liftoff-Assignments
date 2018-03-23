# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
My project will have a database of baseball players and their statistics. It will import DraftKings position and prices. With DraftKings, you're given a budget of 
X dollars, and are to fill out a team (2 pitches, C, 1b, 2b, 3b, SS, OF OF OF) of players under who's total cost is less than X. My project will predict the best
combination of players with the weights given.

It will feature 3 pages. User signup, weight manipulation / results, user page / user history.
The weight manipulation / results page will feature a form with how 'weighted' the user wants the stat to be (i.e. one homerun is worth 4x as much as one single).
The user page / user history page will show the previous day(s) accuracy with the weights given. So if it predicted playerA would get 10 points, and playerA got 9 points, it was 90% accurate.


### Features
User Login / Sign up - Users will be able to create accounts and visit their page.
Weight Manipulation - Allow users to change what a stat is worth.
Display Results - This will calculate what players would provide the most value given their cost and their projections using the weights given.
User History / Historical Results - This will show what the user has used and the actual results. So if my project predicts teamA will score 200 points, and actually
				     scored 220 points, it would add the 200 to the projected total, and 220 to the actual total. Giving me a 110% result. The next day, 
					 if I project 200 points, and get 150 points, my running totalProjected is 400, my totalActual is 370, and my totalAccuracy is 92.5% 
					 for the history of that set of stat weights.

### Technologies
C#
JavaScript

### What I'll Have to Learn
I will probably focus on learning some JavaScript for front-end. I will also look for any DraftKings API and see if there's any good ways to use it in this project.
# NFLLivePrediction
Makes predictions for final score of NFL game based upon prior points scored in the game.

This was part of a cloud computing course as part of my masters in applied data science program.  The code in this folder was ran in google colab.  You can run this code too after altering source file locations.  Here is the external data used in the project:

Play by Play data: https://www.kaggle.com/datasets/maxhorowitz/nflplaybyplay2009to2016?select=NFL+Play+by+Play+2009-2018+%28v5%29.csv

NFL Team Data: https://www.kaggle.com/datasets/nickcantalupa/nfl-team-data-2003-2023

2023 play by play data: https://nflsavant.com/about.php


To run the live streaming...

Set the team values to 1 (home) or 0 (away).  After, run the loop function.  Ensure that a game is occuring live at time of playing the loop.  Every 10 or so seconds you should get live estimates for the games in question.
You might get error messages that the code is out of date, this is because of the free API we used, not because of any code written.  This doesn't impact the usability or reliability of the data or predictions.

Partners:
Aiden Tirney
Jace Vayhinger

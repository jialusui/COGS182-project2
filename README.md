# COGS182-project2

This repository contains source code for my COGS182 project2 in Winter 2021.

In this project, I and my partner Lehan Li applied reinforcenement learning algorithms, including Q learning and Monte Carlo Exploring Start, to solve the casino card game Mississippi Stud.

The code file - project2_code.ipynb - contains the source code of my project. 5 subsections are contained in this source code file.

The first section is draw method. This method sets up the initial conditions of our game by randomly selecting 2 player's cards and 3 community cards and set up the initial ante of 100 dollars.

The second section is step method. This method takes as an input a state s and an action, and returns a sample of the next state s’ and reward r

The third section is the implementation of Q learning algorithm and the visualization of its result.

The fourth section is the implementation of Monte Carlo Exploring Start algorithm and the visualization of its result.

The fifth section is the calculation of the mean squared error of the q_values returned by two algorithms.

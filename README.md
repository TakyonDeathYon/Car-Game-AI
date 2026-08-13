# Car-Game-AI

This code is for training and demonstrating the capabilities of a neural net on a simple car game. 

The scripts are broken up into two parts: one for the training and one for the demonstration.

For the training, a simulated instance of the game is used to allow quick and efficient parallel
training. This then stores the resulting output model weights in `winner-feedforward`. 

For the demonstration, pygame is used to graphically show the game, with a feedback loop allowing the
neural net to control the game while the user watches.

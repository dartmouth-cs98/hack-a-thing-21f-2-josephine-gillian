# Hack Technology / Project Attempted


## What you built? 

Advanced AI in UE4 that runs away from player when first detects the player (through AI sight perception). 


![run](https://user-images.githubusercontent.com/15352560/134787020-925d9f6d-6527-4c00-9772-280ceca0242b.jpg)

![run2](https://user-images.githubusercontent.com/15352560/134787023-14417402-4d52-43a9-a82f-850d6722a403.jpg)


## Who Did What?

Josephine did the first half of the tutorial, and Gillian did the second half.

## What you learned

The basic AI behavior was set up and worked correctly.

AI could detect player and calculate the best hiding spot based on

1) whether the spot is outside of the player's line of sight 

2) distance from player to the spot

3) distance from AI to the spot

4) dot product to favor spots that are to the two sides of player



In the later part of the tutorial, the instructors tried to tweak the math for calculating the best weight for hiding spot options, as well as make the state machine transitions work more smoothly, but to no avail. In addition, when achieving feature 4 above (favoring sides of player), the tutorial's implementation was quite hacky and we had to play with random values to see results. In terms of following the tutorial, we did not encounter too much difficulty.


## Authors

Josephine Nguyen

Gillian Yue

## Acknowledgments

Tutorial at: https://youtu.be/NZZtMNdJk5o

**Setting Up Advanced AI | Live Training | Unreal Engine**

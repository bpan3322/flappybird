# Flappy Bird README
Personal Project that simulates the popular online game, Flappy Bird. 

# How does it work?
The game starts out with the bird being positioned in the middle of the screen. Once you start the game, in order to move the bird, you have to make it "jump" by pressing the up key on the keyboard. The goal of the game is to make sure that the bird does not touch any of the pillars that are set up (using a random timer interval) on the webpage. Because the bird is "jumping",
I also integrated a "gravity" sort of mechanic in the game to simulate each flap meaning going upwards. Instead of making the bird itself move forward, I decided to make each obstacle or pillar, be randomized and move to the left side of the screen to simulate the bird moving forward. The game ends once the bird runs into an obstacle.

# Challenges I faced
The biggest challenge I faced involved the setting up and functions of the obstacles. Because I decided to go with the approach where the obstacles move instead of the bird, I had to somehow make it that each pillar is a randomized pixel amount, that also fit within the cosntraints of the screen, while also making sure that it would end the game if the bird touches it.
It was particularly difficult orienting all the variables involved in the game, starting from the obstacles themselves, as well as the obstacles moving, then the starting position of the bird, as well as the jumping feature of the bird.



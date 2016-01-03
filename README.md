# Graphics Project-2015

# Brick Breakers
##Graphics Programming
### Pauric Boyle

##Introduction

This project is Based on designing an Game for a company called GaCo. 

The Game I intend on designing is Brick Breaker which is a replica of an influential 1976 arcade game by Atari.


##Gameplay
Brick Breaker is were the player must smash a wall of bricks by deflecting a bouncing ball with a paddle. The paddle may move horizontally and is controlled with the left and right arrow keys. When all the bricks have been destroyed, the player wins. The player has 3 lives in which he loses one each time the ball touches the bottom of the canvas. If the lives hit 0 then you lose and have to restart the game.



##Problems Encountered
The first problem I encourted in designing this game was getting the collision detecting on the ball and paddle i solved the ball easilly enough by following our lectuers excercises and solutions.

The paddle was harder and i didnt quite get it solved as the paddle collides as its meant to with the left of the canvas but it over laps to much on the right of the canvas. At first I thought it was because I had added features to the paddle to make it look rounded so I deleted the rounded edges still with no joy. The next approach was to try hard code in the co-ordinates but still no joy so i had no other option but to leave it with the minor overlapping.

The next problem was trying to get the balls to collide with the bricks and make them dissaper i knew i would have to loop through the two dimensional array for each brick that was present in the array checking for colsions but i didnt know how to put it into code. I found a good tutorial online for which helped me with the logic of the code.https: //developer.mozilla.org/en-US/docs/Games/Workflows/2D_Breakout_game_pure_JavaScript/Collision_detection 

##Conclusion
Overall I'm with the outcome of the game although there are a few bugs within the game which with more time I would like to fix. 

One of those bugs is the movement of the paddle when you are moving the paddle right it takes a pause before turning to go left which doesnt help the flow of the game.

Another aspect of the game I tried to change but couldnt was the end game function what I want was for the ball when it hit the bottom restarted from the start position but i could only achieve this by hard codeing co-ordinates into the function. i would also prefer get rid of the alerts and instead have it so that there would be image pop ups.

## References
https://github.com/ianmcloughlin?tab=repositories

http://jsfiddle.net/robhawkes/gHCJt/light/

http://sixrevisions.com/html/bouncing-a-ball-around-with-html5-and-javascript/

http://stackoverflow.com/questions/5127937/how-to-center-canvas-in-html5

https://developer.mozilla.org/en-US/docs/Games/Workflows/2D_Breakout_game_pure_JavaScript/Build_the_brick_field


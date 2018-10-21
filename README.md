PROJECT ARCADE GAME CLONE:


Fourth project for Udacity's FEND nanodegree program.


Instructions to play:

After cloning or downloading the file,use the index.html file to run the game.

APPROACH:


I utilized a Game class,from which both Player and Enemy classes inherit their showing properties(image and location).Then I made some Enemy objects and set them all in the allEnemies array,in request to show the canvas properly.(canvas was not shown with the beginning given code). After succesfully showing the canvas, I utilized the Enemy's update(dt) strategy to influence the foes to move constantly,having a diferrent speed and distinctive beginning stage each time they began over.In this method,we likewise check continually for collisions. On the off chance that there is an impact, our player loses a heart. There is a variable called lives,which decrements each time a crash happens. After three collisions, the diversion stops(enemies stop moving),and a modular seems to illuminate that the amusement is finished. The variable lives is a Player's reference variable. In Player class,we likewise increment the score by 100 each time the player achieves the water. In the event that the score achieves 1000 , a modular seems to praise the player.


Tools used in this game:
Object-Oriented JavaScript Scopes, closures and prototype chains The 'this' keyword Superclasses and subclasses HTML5 Canvas


Resources
https://developer.mozilla.org/en-US/docs/Games/Techniques/2D_collision_detection http://eloquentjavascript.net/ http://stackoverflow.com/questions/5915096/get-random-item-from-javascript-array
<h2>Design a box with the following functionalities and ensure they all work independently and in any combination.</h2>


i. The right button click on a mouse will generate random movable points with different  colours  going  in   any   random   direction   diagonally. 
   For instance, if a point is generated at (0,0), it can go to (-1, 1), (-1, -1), (1,1), or (1, -1), and so on. 
   The  points should be spawned where the  right button  click will be given in the box and the colour and direction of movement should be random.
   

ii. Pressing the “up arrow” key on the keyboard will increase the speed of all the points generated so far and pressing the “down  arrow” key on the
    keyboard will decrease the speed.
    
    
iii.The left button click on a mouse will make the points blink i.e. if a point is in red, it will go background colour(here it’s black) and return to red, and
    this transition should take place within a second while the transition cycle goes on.
    
    
iv. Pressing the “Spacebar” on the keyboard should freeze all the points and none   of   the   above   functionalities   will   work   when   frozen.   The   same
   “Spacebar” should unfreeze them.
   

```
The right button click on a mouse will generate random movable points with different  colours  going  in   any   random   direction   diagonally.
For instance, if a point is generated at (0,0), it can go to (-1, 1), (-1, -1), (1,1) or (1, -1), and so on. The  points should be spawned where the  right button  click will be given in the box and the colour and direction of movement should be random.
I have created an object and assigned it inside another list to update its movements. Inside the object, I have declared initial positions and updated positions of x, y and color variables. 
created a blank list and updated updated x y and color variables, the values are assigned using random variable within (-1,1) range to gererate random number of balls and color, if the list is empty. 
If not, started a loop upto the length of the list. There, assigned list values with variables. By Increasing or decreasing speed, made the balls go forward diagonally. And when the balls hit the wall(from (0,0) to (500, 500)), it bounces back.

```
[Magic_Balls.py](https://github.com/Mouly22/Computer_Graphics/blob/main/Magic_Balls.py) 



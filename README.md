# Game_Engine_exam
100784071 - Evrett Upshall

Even

*The exe is in the build folder


Object Pooling,

Object Pooling is implemted by having one duck go first and 
then having all other ducks start moving once that has either been killed or hits the wall.
This implemtation optomizes the scene by only creating ducks once the first has gone so that way the player knows the game is starting
and by having one go first the player would not notice the delay of spawning the ducks since in later rounds more ducks spawn so having
one start the ducks respawning makes the game run smoother and keeps the player interested.


Command Design Pattern,

The command pattern is implemted by having a bullet that the player controls with the W and S keys.
Once the player misses two ducks the controls will switch.
This benefits the game by giving the player feedback when they are doing bad and it makes the game harder.
The controls being changed on the player forces them to adapt or perform well.


7)

I would implement a score manager. The score manager would track how many ducks the player has hit.
The score maanger benefits the game becasue is give the player a goal and a sense of how they are doing.
The score manager would track how many ducks the player has hit and increase by 1 for each duck hit.
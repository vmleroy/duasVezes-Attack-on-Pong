# duasVezes Attack on Pong | **트와이스 아딱 온 퐁**

Computer graphics discipline project. A small game based on the iconic Pong made in C language with some extras things that I like.
Project base: https://github.com/fegemo/cefet-cg/blob/master/assignments/tp1-ping-phong/README.md

**Made by :**
<li> Julio Cesar Rocha (julioCROS)</li> 
<li>Pablo Felipe </li>
<li>Victor Le Roy (vmLeroy) </li><br/>


**Linux required libraries**: 
- sudo apt-get install libsfml-dev   
- sudo apt-get install libglew-dev          
- sudo apt-get install libsoil-dev         
- sudo apt-get install freeglut3 freeglut3-dev      

<details><summary>Items</summary>
<p>

#### duasVezes attack on Pong is "Pong" game that has some items that bring advantages to both sides or whoever catches them, depending on the item.
**1) TWICE Coin** - A beneficial coin for both players, regardless of who picks it, inspired by the group that gives the item its name, such as in-game music and the practical work 1 of computer graphics, the one who scores a goal while the effect of the item is active, earns 1 extra goal, that is, its as if the goal is being counted **twice** times.

**2) AoT Coin** - acronym for "Attack on Titan", is an item that will cause a wall to appear that prevents the ball from passing through it to the player who catches it, inspired by the great manga and hit anime by Hajime Isayama, Shingeki no Kyojin (Attack On Titan).

**3) Mirro World Coin** - An item that turns both players into mirrors, if the effect of the activated item, the one who did not pick up the item cannot hit the ball of the player who picked up the item, every time there is a collision with the player who did not pick up the item, the ball will not be hit in the direction of the other player, but will be teleported to the other player, it is as if the player who did not pick up the item if it became a "gateway", and the player who took the item became a "exit portal". Inspired by the power of one of the various characters in One Piece (Brulee) in which his power consists of entering mirrors and go out in another dimension (Mirro World), full of mirrors in which she can go in and out anywhere else that there is a mirror.

**4) Reverse Coin** - A very simple item, the ball when colliding with this item will cause its direction to be reversed, returning from where it was hit.

**5) Za Warudo Coin** - An item that causes the ball and the players to be in slow motion while its effect is active, as if there was a "time manipulation" by the item. Inspired by the great manga and successful anime, JoJo no Kimyo na Boken (JoJo's Bizarre Adventure), in which "Za Warudo" is the main power of the antagonist of the third part Dio Brando, making time stop and only he can move and do other things while time is stopped.

</p>
</details>

<details><summary>Game commands</summary>
<p>

The basic movement keys are:

<pre>
z -(Z) Move player 1 up.   | o (O) - Move player 2 up </br>
w -(W) Move player 1 down. | l (L) - Move player 2 down </br>
</pre>

In addition, some "cheats" have been included within the game to facilitate testing the game during the development phase: </br>

<pre>
M (**UPPERCASE**) - Activates autonomous mode, makes the computer "play" against itself; </br>
1 - Turn off item randomness and only item 1 (TWICE Coin) appears; </br>
2 - Turn off random items and only item 2 (AoT Coin) appears; </br>
3 - Turn off random items and only item 3 (Mirro World Coin) appears; </br>
4 - Turn off item randomness and cause only item 4 (Reverse Coin) to appear; </br>
5 - Turn off item randomness and cause only item 5 to appear (Za Warudo Coin); </br>
0 - Turn on item randomness, if it has been turned off, making the next item to appear to be completely random. </br>
</pre>

Other commands: </br>

<pre>
p - Pause the game / Pause menu.  </br>
ESC - Exit the game.  </br>
</pre>

</p>
</details>



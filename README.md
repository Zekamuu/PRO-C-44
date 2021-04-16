# PRO-C-44
Project for class 44. Self design game stage 1


1. What is the title, and the inspiration/motivation of the game.
   Tower Parkour, and the inspiration was just thinking about the sky

2. What is the storyline of the game.
  The main character, which is a ball(for now) jumps accross a series of sky scrapers and other platforms to reach the end, while competing against other players.

3. What is the goal of the game.
  The goal is to reach the end of all the levels, with the shortest time out of the set of players competing.

4. How many characters are present in the game? List the out...
  There are 3 players that play the game, and NPCs, like the scrolling background, the sky scrapers, the various platforms, bird and electric wire obstacles.

5. What are the playing and non playing characters?
  The playing characters are the 3 players interacting with the game, and the NPCs listed in the section above are the non playing characters

6. Describe the behaviour of each character in detail
  The three players, currently squares using matter.js, move around using arrow keys or the WASD keys to move around. The left and right keys, or the A and D keys, move the players left and right. The up key, W key and space bar makes the character jump while the S key and the down keys make the character duck to avoid obstacles. 
  The skyscrapers scroll across the screen as the player moves and must be jumped on, or else the player will fall into the void, making them restart the level. They will be rectangles using matter.js. The skyscrapers are platforms and have to be jumped on top of, or else the player will slide down the side of the tower. 
  The background scrolls accross the screen with the players movement. It is 800px wide and 600px tall. The platforms, for example clouds(not realistic at all) can be jumped on top of and can be used to cross big gaps. These are also bodies using matter.js
  The birds fly near you, and if you run into them, or if they run into you, you have to restart the level. Sometimes to avoid them, you can duck under them by pressing the S key or the down arrow
  The electric wires are jumbled in random areas, and if ran into, you will have to start from the beginning of the level
  
7. What are the elements of skill?
   The elements of skill are the timings of jumps, movement and maneuvering.

8. What are the elements of chance?
   Elements of chance are the height of the birds spawning. Sometimes they can be ducked under and sometimes you have to jump over it.

9. How does the game create and mantain the balance between elements of skill and chance?
   Since the only element of skill is the timing of jumps, movements and maneuvering, it is actually decently hard. However, the chance of the height of bird spawning can also make jumps alot easier.

10. How does the game provide feedback to the player?
   As the players move around, the background and the map(skyscrapers, platforms, and obstacles) move with him/her. Also, there will be a little box in the corner that keeps updates on what levels the players have reached. In another corner, there will be a line showing who has gotten the farthest in the level. 

11. What technologies and softwaries will be used to develop the game?
   Visual studio code, several .js libraries, and Firebase database will be necessary

12. Which javascript libraries are used to develop the game?
  a. p5.js
  g. p5.play.js
  h. matter.js
  i. firebase-app.js
  j. firebase-database.js
  
13. Gather all media files (sound, animations, etc)

14. Describe each stage of development
   Firstly, the bodies of the characters will be created, and given the basics of code, like how to move around. After that will be the Firebase area, where I put data into the firebase, like the username, distance, level, rank, etc. Once that is done, the next step is to do the main coding, where I design the game, all of its elements, classes, functions, and the others. The final steps would be to add the images, and possibly sounds, and wrap up the code.

15. How to play the game
   The players use arrow keys or WASD keys to navigate through the map of the level. A and D and Left Arrow and Right Arrow move the player left and right, while the up arrow, W key, and space bar makes the player jump, and the S key and down arrow make the player duck

16. Cheat codes
There will be no cheat codes.
17. 

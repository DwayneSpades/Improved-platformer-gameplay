# Improved-platformer-gameplay
Improved collision, controls, mechanics, run speed, alot of extra features... Made with modularity in mind.

-This game uses a design pattern that mimics a finite-state machine. 
Different systems such as the 'start screen' operate with adifferent update method when its time to move to the main game state the start screen state deactivates and the main game state starts. individual objects such as the player have there own states to be manipulated for things such as deactivating player movement while in debug mode.

-has gamepad/controller suppport which can be taken out and put in other projects with no issue.
-no stage editor here but instead game objects are able to be placed in a less restrictive 32x32 tile coordinate among the level which is scaled to 64X64 tiles after reading the 2d array produced form the Chroma Stage editor.
-cutscenes are in the game. theres a script to make more. Could be more modular with less hassle to use.
-there are other levels that are accessable vie the 'options' menu there test area's to deomstrate the concept.
-wall jump mechanic is improved with some insiration from 'Celest'. hold forward into walls to slow desent. press jump while held into wall to jump off it. press down while held into while to slide down faster than if you fell.
-debug mode accessible by press 'D' key. you can fly around and place objects while th eplayer charater is frozen switch back by pressing 'D' key again. to save item placement press left mouse-click.



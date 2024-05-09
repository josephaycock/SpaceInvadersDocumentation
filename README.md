Took inspiration from original game "Space Invaders"

# Description of Project
This project was made for CSC 2463 - Programming Digital Media
Game was created using P5.js, P5play.js, Tone.js, and Aurduino
- P5.js and P5play.js were used to make the graphics of the game
- Tone.js was used to create sound for the game
- Aurduino was the physical computing of the game

How To Play
The menu screen is first shown to give instructions on how to use the controls.
- LMB is used to alternate between screens.
- Spacebar is for the user to shoot lasers at the aliens.
- The thumb stick is for the user to move left and right of the screen to dodge the lasers from the invaders.
In the game screen the user will have only three lives.
- If the ship been hit the life will go down to 0 and the game will end.
- Shoot using spacebar at the aliens to destroy to gain points and survive.
- There is a time on the screen to show how long the user survived.
- If the aliens make it to the bottom of the screen it is game over.
The end screen shows the user score and time they survived.
- To restart the game click the LMB on the screen.

The graphic of the games that were made using P5.js and P5play.js
- Three screens which are the Start, Game, and End screens
- The ship were made from the P5.js and P5play.js consisting of two rectangles together
  - The lasers were also made from a rectangle which was used by both th user and aliens
    - Green ship but when hit turns red for a few seconds
- The aliens were images and consist of two different types of aliens
- Imported a font that gives the test and retro style feel
  - The text in the Start screen includes Title and Controls of the game
  - In Game screen Time, Score, and Lives were recorded on the top screen
  - In End screen the Time Survived and Score Gained were recorded

The sound of the game that were made using Tone.js
- The game consists of four sounds.
  - Alien laser
    - Created using BitCrusher into a PolySynth instrument
  - Ship laser
    - Created using BitCrusher into a MonoSynth instrument
  - Ship and Alien destroyed
    - Created using Synth instrument with a 'sawtooth' oscillator
    - Connected a 'filter' with type 'lowpass'
    - Controlled the volume to be lowered
    - LFO was also used that connected into the filter
  - Background music
    - Created using a Pattern of 5 different keys
      - 'A3, B3, C3, E3, G3'

The physical computing were made using Aurduino
- Contoller was connected into the Aurduino board and coded into the .ino file and javascript file
- LED was used to tell user when the user ship was hit

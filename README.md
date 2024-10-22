# ZType-Game
ZType word shooter game inspired by Dominic Szablewski's original [ZType](https://zty.pe/) game.

This game was made using Java in Eclipse IDE using Northeastern Univeristy's [Image Library](https://course.ccs.neu.edu/cs2510h/image-doc.html). Source code can only be accessed by request due to plagarism standards. 

## Game Rules
- Type the words as they appear on the screen
- When a word turns from blue to red it has changed from an *Inactive* to an *Active* word, & the shooter character will align with the word being reduced (you may only remove letters from the current *Active* word & there can only be one *Active* word at a time)
- If there are 2 *Inactive* words on the screen that start with the same letter, the uppermost word will be reduced
- The game will end when a word reaches the very bottom of the screen and your score will be displayed
- To play again, click anywhere on the screen of the "Game Over" screen
- Have Fun!

https://github.com/user-attachments/assets/926c3251-05fe-46e8-8db6-c816d1593abd

## Instructions for Download (with requested source code)
1. Install and set up EclipseIDE application
2. Download ZType.java file and javalib.jar, tester.jar files
3. In the File Menu, select *New* then *Java Project*. Select *Finish* and name the file whatever you would like
4. Highlight your new project in the Package Explorer pane, then right-click it and select *Properties*. Select the *Java Build Path*, then the *Libraries* tab, then click *Add External JARs*. Select the javalib.jar and tester.jar files to import
5. Then, in your project, highlight the *src* tab. In the File Menu select *Import*. Navigate to your directory that contains the ZType.java file, select the file and click *Finish*

## Instructions to Play Game
1. Open the *ZType.java* file in the *src* folder under your project
2. Click the *Run* tab, then *Run Configurations*
3. Name the configuration whatever you would like, select the *Project* as your project, the *Main Class* as tester.Main, then (under the *Arguments* tab) enter "ExamplesZTypeWorld" for *Program arguments*.
4. Finally click *Run* and play the game

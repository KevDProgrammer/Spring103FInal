# Spring103FInal (Kaboomboom: Musical Striker)

Game Objective:  
The main goal is to eliminate all visible (lighted up) targets through timing.  
LED pin(s) will light up throughout the strip in two colors (Yellow and Pink); the number varies by level. These are known as the Target(s).  
A single LED (white) will cycle through the strip, and it is the player's task to stop it when it lands on any Target. This is known as the striker.  
Targets can come in two colors, and the player must use the left and right buttons, respectively, to strike the specific target when in range.  
Each time a target is struck, a music note will play. Once all visible targets are struck, a short melody will play, and the level will end.  
  
Basic Rules:  
Strike all targets to advance to the next level.  
The player only gets 3 misses throughout a playthrough.  
  
Scoring System:  
Once all the levels are been cleared, the player's accuracy score will be displayed on the scoreboard.  
Failing to strike the target too many times will also lead to the scoreboard.  
The scoreboard will come in the form of an LED bar.  
Each time a miss occurs, the player will lose 25% of the total score.  
If the player's score reaches 0%, the game will end.  
  
Scoreboard Examples:  
100% - Represented by 10 LEDs in Green (0 miss)  
75% - Represented by 7 LEDs in Green (1 miss)  
50% - Represented by 5 LEDs in Green (2 miss)  
25% - Represented by 3 LEDs in Green (3 miss)  
0% - Represented by 1 LED in Red (4 miss)  
  
Control (input/output):  
Left Button: For striking yellow targets  
Right Button: For striking pink targets  
Levels: Changning Difficulty (Range: 1-2)  
Scores: Keeping track of Accuracy (Range: 0-100%)  
Music: The playing of melodies  



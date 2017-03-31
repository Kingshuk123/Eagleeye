# SuperHardProject

## Description
 - Our app is a random color grid where you have to find the color that is different and click it. As you click the different button, your level will increase.

## FAQs

### Why does the timer stop at one second?
The timer does not stop at one second, however, the timer never displays "0:00." After 29 seconds and 999 milliseconds, the timer stops, therefore it never actually hits 0 seconds.

### Why are the different colored squares so hard to see sometimes?
In our code, we use a function that increases the ease of the grids as they increase in size. However, the different color has a possibility of only being six rgb values away from the rest of the colors, which makes it hard to see.

## Changelog

### Version 1.0
This is out first version with a working play button, 4x4 grid, and 5x5 grid. We hope you enjoy!


### Version 1.1
Changed homepage and fixed grids.

#### Bug fixes
 * Fixed a bug where the play button would go straight to the 5x5 grid
 * Fixed a bug where if you made the screen less than 400px in firefox, the buttons on the homepage would overlap.

#### Changes
 *  Added all grids 4-15
 *  Added name of game on homepage


### Version 1.2
Added changes to the way things interacted.

#### Bug fixes
 * Fixed a bug where the play button would not work if it was quickly tapped twice.
 * Fixed a bug where if you made the screen less than 400px in firefox, the buttons on the homepage would overlap with the text.
 * Fixed a bug where the background color would change to white if certain brackets were not in placeu.
#### Changes
 * Added transition between all grids 4-15 when the different colored button was clicked
 * Game adapts to smaller screen sizes
 * Changed difficulty of different colored button
 * Changed the text on the homepage
 
 
### Version 1.3
Added other functions and additional things to make the game look better

#### Bug fixes
 * Fixed a bug where the 3 second setTimeout function that played on the click of a button could play multiple times depending on how many tomes the button was clicked in that three second period.
 * Fixed a bug with the countdown that made it to where when the play button was clicked, the options button would lose its animation
 * Removed the chance that an invalid color would appear
#### Changes
 * + Added a countdown transition and a blur effect
 * + Countdown adapts to smaller screen sizes
 * + Added a timer
 * + Added a story
 * + Made code more compact
 * + Added sound
 
## Credits
* Cameron Maloney
* Indy Nalagandla 
* Kingshuk Daschowdury
* Nathan Lewis
* Prithvi Patel


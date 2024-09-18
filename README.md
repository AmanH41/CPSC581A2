# Capture Light 

## [link to code](https://github.com/AmanH41/CPSC-599/blob/main/A0.ino)

### What is Capture Light? 
This project is a reaction-based game using an Arduino Due, a set of 8 LEDs, and a button. The LEDs light up in a sequence, bouncing back and forth between two green LEDs on the middle with red LEDs at the ends. The player’s goal is to press the button when either of the green LEDs is lit. If they press the button on a red LED, they lose. The game speeds up when the player wins, making it progressively more challenging. The game is ment to capture the challenge and fun of a game that is commonly found in a arcade.
## Project Documentation 
### How Does it Work?
1. LED Sequence:

There are 8 LEDs in total: two green LEDs at positions 3 and 4, and six red LEDs in the left right ends.
The LEDs light up sequentially, starting from the first red LED and moving toward the LED at the other end.
When the sequence reaches the end, it reverses direction, bouncing back to the first red LED.
Only one LED is lit at a time, and when the next LED lights up, the previous one turns off.
2.Player Input:

The player must press the button when either green LED is lit.
If the player presses the button when a green LED is on, they win. As a reward, the green LED will blink, and the game will speed up.
If the player presses the button when a red LED is lit, they lose. The red LED will blink, and the game resets after a short pause.
3. Speed Mechanism:

The game starts with a moderate speed and increases after each win by reducing the delay between LED transitions.
The speed caps at a certain level to prevent the game from becoming impossible.
### Demo Video 
 

### Circuit Schematic Diagram
Circuit pic 

## Initial idea to final iteration

![alt text](https://github.com/AmanH41/CPSC-599/blob/main/Assets/IMG_0279.jpg)

![alt text](https://github.com/AmanH41/CPSC-599/blob/main/Assets/IMG_0279.jpg)
![alt text](https://github.com/AmanH41/CPSC-599/blob/main/Assets/IMG_0280.jpg)
![alt text](https://github.com/AmanH41/CPSC-599/blob/main/Assets/IMG_0281.jpg)
![alt text](https://github.com/AmanH41/CPSC-599/blob/main/Assets/IMG_0282.jpg)


### Refrences 
refrence 

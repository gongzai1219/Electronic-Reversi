# Electronic-Reversi IDMT Cruftfest Project

This project replicates the traditional Reversi game and aims to develop a new way to play. What I've done is building a marker pens matrix instead of the real board and creating an interface on the computer screen to show the state of game playing.

### Ingradients
16 marker pens (cruft)
16 buttons
one LCD 16 x 1
one Potentiometer 10k Ohm
Arduino
Processing

### Schematics & Breadboard image for Arduino Board
This part shows the circuit of this project's Arduino part. If you also want to try to build such project, just follow this. When building the button matrix, I referred to Michael Pilcher (2014). He mentioned about how to control multiple buttons using one analog pin. The way to achieve that is to do tricks on the resistors connect to each button. Buttons with different resistors can input different value to the analog pin, therefore, which button is pressed can be known.
![My image](https://gongzai1219.github.com/Electronic-Reversi/img/Reversi.png)
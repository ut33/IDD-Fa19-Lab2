# Digital Timer

## Part A. Solder your LCD panel

Picture: https://github.com/ut33/IDD-Fa19-Lab2/blob/master/IMG-1192.JPG

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?** 5 V

**b. What voltage level do you need to power the display backlight?** 3.3 V
   
**c. What was one mistake you made when wiring up the display? How did you fix it?** Before I connected the arduino to the computer, when I was comparing my circuit to the given diagram, I realized that I had accidentally connected RS on the LCD to pin 11 (1011 on the diagram) instead of connecting it to pin 12. 

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?** In void setup() I changed the line lcd.print("Hellow World"); to lcd.print("Vini Tripathii");
Picture: https://github.com/ut33/IDD-Fa19-Lab2/blob/master/IMG-1205.JPG
 
**e. Include a copy of your Lowly Multimeter code in your lab write-up.**
Please see repository for Multimeter code.
https://youtu.be/ifi3GJ1nCHE

## Part C. Using a time-based digital sensor

Video of rotary encoder: https://youtu.be/XUsaTZPZtdg


## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**
Decrease the duration of each note by half -- that is double the value of the numbers in int noteDurations[], as they are inverses.
For example, the original line of code was: int noteDurations[] = {4, 8, 8, 4, 4, 4, 4, 4};
To make the song play twice as fast, it was changed to: int noteDurations[] =  {8, 16, 16, 8, 8, 8, 8, 8};
 
**b. What song is playing?**
Star Wars!

## Part E. Make your own timer
We (Yuxin, Fei and I) created a game that tests and enhances your reflexes over repeated games. A ball falls from the top of the LCD -- the movement (it can bounce between columns 0 and 1) and speed of the ball are random. Press the button when you think the ball has reached the barrier at the bottom of the screen. If you press too early or too late, you lose -- given that the average human has a reaction of 0.25 seconds, there is a margin of saftey permitted. 
Note: the on button and the restart button are one and the same.

Video: https://youtu.be/IUFlvdQyQvI

Code is on repo.


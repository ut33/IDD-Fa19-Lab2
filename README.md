# Digital Timer

## Part A. Solder your LCD panel

**Take a picture of your soldered panel and add it here!**

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?** 5 V

**b. What voltage level do you need to power the display backlight?** 3.3 V
   
**c. What was one mistake you made when wiring up the display? How did you fix it?** Before I connected the arduino to the computer, when I was comparing my circuit to the given diagram, I realized that I had accidentally connected RS on the LCD to pin 11 (1011 on the diagram) instead of connecting it to pin 12. 

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?** In void setup() I changed the line lcd.print("Hellow World"); to lcd.print("Vini Tripathii");
 
**e. Include a copy of your Lowly Multimeter code in your lab write-up.**
Please see repository for Multimeter code.

## Part C. Using a time-based digital sensor

**Upload a video of your working rotary encoder here.**


## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**
 
**b. What song is playing?**


## Part E. Make your own timer
We (Yuxin, Fei and I) created a game that tests and enhances your reflexes over repeated games. A ball falls from the top of the LCD -- the movement (it can bounce between columns 0 and 1) and speed of the ball are random. Press the button when you think the ball has reached the barrier at the bottom of the screen. If you press too early or too late, you lose -- given that the average human has a reaction of 0.25 seconds, there is a margin of saftey permitted. 
Note: the on button and the restart button are one and the same.

**a. Make a short video showing how your timer works, and what happens when time is up!**


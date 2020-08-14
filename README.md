# Interactive-Systems-Project

This repository includes the code of my current interactive systems project. It will be constantly updated in the future. The project will be focused around creating a simple "reaction game" using the Arduino Uno circuit board and some conductive materials. The code for my final code iteration will be included, as well as code of prototypes.


The first prototype ("1: BASIC") has a simple purpose: when one of the 8 LEDs turns on, it can be turned off by pressing the corresponding button (1-8). If the incorrect button is pressed, nothing happens. When the correct button is pressed, the LED turns off and another, randomly chosen LED turns on. A randomly chosen LED turns off when the correct button is pressed, the Arduino is turned on or if the Arduino is reset (with the big red button).
Tinkercad link to this prototype: https://www.tinkercad.com/things/lpC6MyJbtSr-first-basic-prototype


The previous prototype did not have much game logic integrated into it yet, this has all been added in this second prototype ("2: LOGIC"): Here, the basic game logic is included. Pressing the correct button will turn off the corresponding LED and will result in a short delay, after which another random LED will turn on. If an incorrect button is pressed or the user does not manage to press the button in time, the game ends, indicated by all LEDs turning on and off again. If the game ends, it has to be reset with the red button on the Arduino. The delay between LEDs glowing up and button presses will constantly decrease to make the game progressively harder, but the delay will not drop below an unmanagable point. Once the user reaches this point, it becomes an endurance game, where the user tries to not end the game, since this would erase all progress.
Tinkercad link to this prototype: https://www.tinkercad.com/things/aIsevziiuiO-first-working-prototype


In the third prototype ("3: PHYSICAL"), I mainly experimented with the physical Arduino, since I did not own an Arduino before, nor have I worked with a physical one yet. This prototype still has the main game logic, although I have only 4 buttons in use instead of 8, since the Arduino starter kit simply came only with 4 buttons included. But this does not matter that much, since for my finished prototype I have to replace my button mechanism with something different, because I will have to use conductive materials.  What I have also done is add more functionality, like a piezo sound output, or a display to show how many times I pressed the button correctly. The code can be found in the file "3: PHYSICAL", but pay attention that the file "pitches.h" is also needed, since it controls the sound outputs of the little speaker. In the file "Setup Instructions PHYSICAL" I will also tell the exact way all the different Arduino components have to be used to get the prototype to run, like cables and resistors.


Now comes the final version of my project ("4: FINAL). Here we are using 8 LEDs instead of 4 like in hte previous prototype. We also no longer use buttons and use conductive materials to simulate buttons instead. We have a contact zone on each finger (including the thumb) and also the palm of the hand. This way, we can send signals to the Arduino by pressing the thumb or the palm of the hand against any of the fingers. This way we can send a total of 8 signals to the Arduino, one signal per LED. I wanted to include a display to show the current/final score, but it used a total of 11 pins, which are sadly not available to me because we are using up too many of the other pins. Instead, the final score can be seen when connecting the Arduino to the PC and activating the serial monitor. Instructions on how to set up this final version can be found in the file "Setup Instructions FINAL". Note that for the programm to work, "pitches.h" is needed, just like in the previous prototype.


Still getting to know GitHub, checking how to operate it.

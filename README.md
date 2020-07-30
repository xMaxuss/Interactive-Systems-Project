# Interactive-Systems-Project

This repository includes the code of my current interactive systems project. It will be constantly updated in the future. The project will be focused around creating a simple "reaction game" using the Arduino Uno circuit board and some conductive materials.


For now, only the code of my 2 first prototypes are included. The first prototype (First BASIC prototype) has a simple purpose: when one of the 8 LEDs turns on, it can be turned off by pressing the corresponding button (1-8). If the incorrect button is pressed, nothing happens. When the correct button is pressed, the LED turns off and another, randomly choosen LED turns on. A randomly chosen LED turns off when the correct button is pressed, the Arduino is turned on or if the Arduino is reset (with the big red button).
Tinkercad link to this prototype: https://www.tinkercad.com/things/lpC6MyJbtSr-first-basic-prototype


This first prototype does not have much game logic integrated into it yet, this has all been added in the second prototype (First WORKING Prototype): Here, the basic game logic is included. Pressing the correct button will turn off the corresponding LED and will result in a short delay, after which another random LED will turn on. If an incorrect button is pressed or the user does not manage to press the button in time, the game ends, indicated by all LEDs turning on and off again. If the game ends, it has to be reset with the red button on the Arduino. The delay between LEDs glowing up and button presses will constantly decrease to make the game progressively harder, but the delay will not drop below an unmanagable point. Once the user reaches this point, it becomes an indurance game, where the user tries to not end the game, since this would erase all progress.
Tinkercad link to this prototype: https://www.tinkercad.com/things/aIsevziiuiO-first-working-prototype


In the third prototype (First PHYSICAL Prototype), I mainly experimented with the physical Arduino, since I did not own an Arduino before, nor have I worked with a physical one yet. This prototype still has the main game logic, although I have only 4 buttons in use instead of 8, since the Arduino starter kit simply cam only with 4 buttons included. But this does not matter that much, since for my finished prototype I have to replace my button mechanism with something different, because I will have to use conductive materials.  What I have also done is add more functionality, like a piezo sound output, or a display to show how many times I pressed the button correctly. The code can be found in "First PHYSICAL Prototype", but pay attention that the file "pitches.h" is also needed, since it controls the sound outputs of the little speaker. In the file "Setup Instructions 1" I will also tell the exact way all the different components have to be used to get the prototype to run, like cables and resistors.


Still getting to know GitHub, checking how to operate it.

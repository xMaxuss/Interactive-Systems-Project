This file will explain, how exactly "4: FINAL" needs to be created. It will list all the necessary materials and will tell how they need to be used.

Materials needed: 5 10kOhm resistors, 8 1kOhm resistors, 1 220Ohm resistors, a piezo sound output, 8 LEDs (any color, although 2 different colours times 4 LEDs is optimal), a medium breadboard (contains + and - lines, has 10x63 pin slots) an Arduino Uno (or similar), a bunch of wires, any conductive material (preferably deformable). Should you add more wire to the Arduino, keep in mind that A0 has to be kept free, or else the randomization of the game logic will not function correctly.

This is the system that I will use to tell you, what part belongs where. I will first take a part, for example, "Wire", and then give pairs, like (a 1). Since the breadboard contains the letters a-j and numbers 1-64, each spot can be represented by a pair. Should I write "(- a 1)", this means that the part has to be inserted in the "-" part in line 1 on the side of a. Should I write "(- j 1)", this means that the part is inserted into the opposite side of the breadboard. Same goes for "+". Should I write "(Arduino 1)", this means that the part is inserted into the Arduino on pin 1. Finally, should I write "(Finger 1)", this part has to be connected to conductive material, which is then placed on the index finger. "Finger 2" stands for middle finger and so on. "Thumb" and "Palm of hand" are self explanatory. With this out of the way, here is the construction plan:

1)  LED 1: (- a 5),(b 5) (for LEDs, make sure the cathode (shorter foot) is placed into -!)
2)  LED 2: (- a 9),(b 9)
3)  LED 3: (- a 13),(b 13)
4)  LED 4: (- a 17),(b 17)
5)  LED 5: (- j 5),(j 5) (if possible, use different colored LED from now on)
6)  LED 6: (- j 9),(j 9)
7)  LED 7: (- j 13),(j 13)
8)  LED 8: (- j 17),(j 17)
9)  1k resistor: (j 3),(f 5)
10) 1k resistor: (j 7),(f 9)
11) 1k resistor: (j 11),(f 13)
12) 1k resistor: (j 15),(f 17)
13) 1k resistor: (a 3),(e 5)
14) 1k resistor: (a 7),(e 9)
15) 1k resistor: (a 11),(e 13)
16) 1k resistor: (a 15),(e 17)
17) 10k resistor:(- j 19),(i 19)
18) 10k resistor:(- j 21),(i 21)
19) 10k resistor:(- j 23),(i 23)
20) 10k resistor:(- j 25),(i 25)
21) 10k resistor:(e 21),(e 25)
22) 220 resistor:(b 21),(a 26)
23) Piezo: (g 28),(f 30)

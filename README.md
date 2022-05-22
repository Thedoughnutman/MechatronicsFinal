# MechatronicsFinal
Robot uses servo to tension the long piece of wire in the front of the basket// Another wire on the back put into the breakboard to act as the anchor point to pull the basket back

Once servo turns right, adds too much tension for anchor wire to hold causing the wire to get pulled out and the basket to quickly swing the other direction to make the ball drop out

The anchor wire and servo needs to get reset after every use 

<img src = assets/BoeBot.jpg>

### Usage
Robot centers servo (going farthest left) in initialization 
Waits for 2 inputs from irRemote
Goes to location (only 2/ 3)
Plays NOKIA song, giving time to place trash/ ball into the basket
Goes to second location from irRemote (1, 2, 3, 4)
Moves into forward orientation and moves servo farthest right to drop ball
Turn around to exit maze until QTI detectes the white tape then make the correct right/ left turn to exit and follow the line on the entrance of maze

### Ports
PORT 3 = irDetector for remote
PORT 4 = SPDT
PORT 5 = QTI

PORT 11 = Initialization LED
PORT 10 = Initialization Speaker
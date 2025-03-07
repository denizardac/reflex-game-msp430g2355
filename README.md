# reflex-game-msp430g2355
a reflex game to play with your friend based on MSP430G2355 microprocessor

**Overview**
This project implements a two-player reflex game using the MSP430G2553 microcontroller. 
The game tests players' reaction times based on visual cues displayed on a 7-segment display. 
Players interact with the system using buttons, and the results are indicated through LEDs. 
The game starts with a countdown displayed on the 7-segment display (3 → 2 → 1 → "-"). 
Players must press their respective buttons only when the dash ("-") symbol is displayed. If a 
button is pressed prematurely (during 3, 2, or 1), the other player wins, and their LED lights 
up. If both players wait until the dash, the first player to press their button wins. Each session 
resets automatically after 3 seconds, or players can manually reset the game using a 
designated reset button.

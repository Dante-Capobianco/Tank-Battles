# Tank-Battles - Introduction
We are heading back to the Wii-era with this 2-player tank action game making use of a PS2 keyboard, 2 joysticks, and 2 arcade buttons! In this game, 2 tanks
are displayed using a birds-eye 2-D view within a maze-like map. Each tank is spawned into
random locations in this map (without overlapping with boundaries). Using 8 keys (4 per player) on the PS2 keyboard, as
well as 2 joysticks (for cannon rotation) and 2 buttons (for cannon shooting), each player can
navigate the battlefield and rotate their tank cannon (using the joystick) to attack the enemy
player (3 lives will be allocated per tank). 

# Next Steps
To add extra flavour to the game, power-ups can be added! Examples include ricochet bullets that bounce off walls several times (be careful because your own bullets can
still hurt your tank), bomb bullets that hit anything within a certain vicinity of its explosion,
speedy bullets (faster bullet speed), slowness bullets (normal bullet speed, but will slow tank
movement & cannon rotation if it hits a tank), and potentially more.

And if you do not happen to have access to the hardware needed for the current application, modifications can be made to work on basic laptop/desktop keyboards!

Finally, extra add-ons could be created, such as a countdown timer and a 1-player mode against waves of computer opponents!

# How to Operate the Game (currently accessible via University of Toronto FPGA Labs)
To operate our game, please follow the below steps:
1. Compile the game in your desired software environment
2. Click push buttons 0 and 1 on the DE1-S0C display, corresponding to Players 1 & 2
indicating they are “ready to start”
3. Once both buttons are clicked, start playing!
   
   a. Use the joysticks to move around & aim your cannon at the opponent  
   b. Click on the arcade button to shoot a bullet  
   c. Dodge the bullets (because even your own bullets can hurt you) and outlast the opponent
4. Once one player loses all 3 lives, tracked through the HEX displays on the board, the
game will transition to a Game Over screen, the HEX displays indicate who won, and the
game can be reset by clicking the 2 push buttons again

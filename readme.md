# Turn-Based Strategy Battle system
## Introduction  
An alternative battle system for RPGMMZ like on the game series Suikoden.
It would need to add a grid-based war system, turn-based combat, and the ability to issue commands like attack defend move, or tactics
- 4 or 3 man units
- player side start with 2 units, gains up to 6
- each character placed in a unit an active ability and a passive ability
- each unit has a leader, the leader is specifically chosen and determines HP of the unit.
- active abilities have static values, including damage but can be affected by passive abilities and their own internal function
- defense can only be improved via abilities
- movement is 2 squares at base and can only be changed via abilities
- active abilities have limited uses, as dertermined by the individual ability, unless its the unit leader, then it has unlimited uses.
- characters may have a passive that disables them from becoming a unit leader if their ability is deemed too strong to have infinite uses of.
## Variables
``` javascript
let health = 100;
let attack = 20;
let defense = 15; 
let morale = 0.8;
let speed = 98 // for turn order
```

## Control devices 
- Mouse, keyboard
- Touch Screen
- joystick ???

## Mechanics
### Movement
Each character moves differently in dependence on its type

![](https://i.ibb.co/1MT79Pj/Pasted-image-20230703001845.png)
![](https://i.ibb.co/59P7QHW/chrome-Om-LNn-P6-URN.png)

I guess the movement will be the same as in Chessboard
### Action list
After moving the character, they have to do some action to end the turn 

![](https://i.ibb.co/q95CXtC/Pasted-image-20230703002257.png)
#### Attack
if the enemy is in range of the character they can do attack action

#### Wait
Skip turn

#### Rune
Not sure what it is. Some sort of magic that you can use before battle?
### Battle 
Compare two groups (characters) stats and with some calculation decide the winner
![](https://i.ibb.co/qnY7Wjy/Pasted-image-20230703003325.png)

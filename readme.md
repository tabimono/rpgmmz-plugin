# Turn-Based Strategy Battle system
## Introduction  
An alternative battle system for RPGMMZ like on the game series Suikoden.
It would need to add a grid-based war system, turn-based combat, and the ability to issue commands like attack defend move, or tactics
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
![](https://i.ibb.co/1MT79Pj/Pasted-image-20230703001845.png)![[Pasted image 20230703001906.png]](https://i.ibb.co/SdS4bqg/Pasted-image-20230703001906.png)
I guess the movement will be the same as in Chessboard
### Action list
After moving the character, they have to do some action to end the turn 
![[Pasted image 20230703002257.png]](https://i.ibb.co/q95CXtC/Pasted-image-20230703002257.png)
#### Attack
if the enemy is in range of the character they can do attack action

#### Wait
Skip turn

#### Rune
Not sure what it is. Some sort of magic that you can use before battle?
### Battle 
Compare two groups (characters) stats and with some calculation decide the winner
![[Pasted image 20230703003325.png]](https://i.ibb.co/qnY7Wjy/Pasted-image-20230703003325.png)

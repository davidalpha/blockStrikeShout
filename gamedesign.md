block, strike, shout!

'the medieval rock paper scissors game'

features:
- singleplayer
- customizable heraldry
- scoreboard

Game flow

<Logo>
* menu
- new game
- scoreboard
- exit

* New game
- make knight
- random knight

  * make knight
   - select banner
   - select weapon
   - select heraldry
    [ok]
  * random knight
    [ok]  

* Game
- Strike!
- Block!
- Shout!

logic: strike > shout / block > strike / shout > block
oppponent picks random action
resolve action

<you won!>
games played+1
score +1
<draw!>
games played+1
<you lose!>
games played +1
score -1

[again] go to * Game
[exit] go to * menu

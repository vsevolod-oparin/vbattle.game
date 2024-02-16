# Virus Battle Game

## Rules

Battle of Viruses is a turn-based paper-game that was popular in tech schools in USSR.
It is played on a checkered piece of paper in the square 10 x 10.
Two players play the game. On each turn a player has three actions.
At each action the player can either make a virus or infect a virus
of the opponent, transforming it into own tower. You cannot infect
a tower of the opponent.

Below is an example game.

<img src="pictures/demo.gif" width="300"/>

Each player starts from the corner.
All next moves should be done in connection (by side or diagonal) with an alive 
figure of the player. Every virus is alive. A tower of the player is 
alive if it is connected with another virus of that player or another alive tower.
If there is no connection between a tower and a virus (direct or indirect), the tower
is dead. You can make it alive back, if you reconnect the tower with an alive virus.

The player who cannot make an action loses the game.

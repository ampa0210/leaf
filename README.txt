Objective: Implement min-max algorithm

Problem: Develop software to play a relatively simple chess endgame using a mini-max
algorithm. PlayerX has a rook, knight, and king and PlayerY has only the king and knight. With
more chess pieces, PlayerX has higher chance to win this game. So PlayerX should try to win the
game as quickly as possible avoiding any infinite loop or dead end. On the other hand, PlayerY
should try to delay as long as possible, end in a draw, or even win the game if possible when
PlayerX makes mistakes.

Requirements:
	- Anaconda 4.1.1
	- Python 3.5.2
	- Python-chess (pip install python-chess==0.15.3)

~~~ Starting Board Position ~~~
= chess.Board('2n1k3/8/8/8/8/8/8/4K1NR w - - 0 0')

~~~ Test Board Positions ~~~
1. chess.Board('7k/3K4/8/8/3R4/8/8/1N6 w - - 0 0')
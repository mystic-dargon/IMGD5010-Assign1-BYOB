# IMGD 5010 - Assignment 1 - BYOB: T1C-TAC-T0E

*T1C-TAC-T0E* can be used to describe boardstates in tic-tac-toe game using commands composed of a single bit and a 4-digit nibble.
To write a single command in *T1C-TAC-T0E*, start by denoting who is playing, and then what location on the board they are placing their mark.
A full board state can then be defined by listing the moves taken in sequental order.

## WHO IS PLAYING
Who is playing is defined by a single bit, where 0 = X and 1 = O.

0 = Xs

1 = Os

## WHERE THEY ARE PLAYING
Board postition is defined by a 4-digit nibble, starting at the top left corner with 0 (0000) and ending at the bottom right corner with 8 (1000).

| 0 | 1 | 2 |
|---|---|---|
| 3 | 4 | 5 |
| 6 | 7 | 8 |

For example, an X placed in the middle square can be denoted with the following command: 0 0100

## THE CHALLENGE

Using this system, draw out the current boardstate as defined below and find the command for the winning move.

0 0100 1 0001 0 0000 1 1000 0 0110 1 0011

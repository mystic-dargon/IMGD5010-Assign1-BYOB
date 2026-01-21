# Challenge Solutions

## Challenge 1:

Using this system, draw out the current boardstate as defined below and find the command for the winning move.

0 0100 1 0001 0 0000 1 1000 0 0110 1 0011


**DRAWING THE BOARD**
| X | O |   |
|---|---|---|
| O | X |   |
| X |   | O |


**THE WINNING MOVE**

0 0010

| X | O | X |
|---|---|---|
| O | X |   |
| X |   | O |

## Challenge 2:

Write out the command string for the following set of moves:

O plays top-right, X plays middle-left, O plays top-middle, X plays top-left, O plays bottom-left, X plays center


**COMAND STRING**

1 0010 0 0011 1 0001 0 0000 1 0110 0 0100


**FINAL BOARD STATE**

| X | O | O |
|---|---|---|
| X | X |   |
| O |   |   |

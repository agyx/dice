# dice
Randomness from loaded dice

Use 5 D6 dice, loaded or not.
After each roll of all dice:
- Put the dice in line without looking at them
- Starting from the right, remove any dice which have the same value as those on their left
- Roll the removed dice again
- Repeat until all dice have different values
- Enter the result and press return

eg:
- 5 1 2 1 5  : first throw
- 5 1 2      : remove 1 5 on the right
- 5 1 2 4 2  : second throw
- 5 1 2 4    : remove 2 on the right
- 5 1 2 4 6  : Ok! Enter 51246

```
roll: 
32451
1 rolls, 0 bits: 0
roll: 
34216
2 rolls, 8 bits: dc
roll: 
54326
3 rolls, 16 bits: dc02
roll: 
12543
4 rolls, 16 bits: dc02
roll: 
64123
5 rolls, 24 bits: dc0201
roll: 
```

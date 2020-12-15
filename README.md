# Mario on Terminal
This is a terminal based game built in python that tries to simulate the classic Mario0

## Description

* Written in python3.5 without using pygame or curses
* ***colorama*** is the only additional package that has been used apart from core packages
* The game has been built for Linux distributions (specifically Ubuntu 16.04)

### Prerequisite

- First, install all the requirements using the requirements.txt
```bash
pip install -r requirements.txt
```
- Run the game using python3.5
```bash
python3.5 main.py
```

### GamePlay
Mario has 5 lives. Make sure you play carefully to get to level 3.<br/>
Higher levels have :
* Faster enemies
* Scenic Changes
* Bridges that move

##### Controls
- `d` to move right
- `a` to move left
- `w` key to jump
- `q` to quit the game

| Activity | Scoring | Notes |
|----------|---------|-------|
|Collecting Coins| 1000 | - |
|Kill enemies by jumping over them| 1000 | If Mario gets hit from the side, he loses a life. |
|Covering distance (x-coordinate) | As per setting | - |

***Note:*** Mario dies if he falls into a pit.

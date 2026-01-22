# Assignment 1
CodeBase: [text](https://gitlab.com/csteach323-488/source/-/tree/master/week1/examples/01-intro-arcade)

Add a Menu and "3 lives" features to the game 

## 
- Pygame setup: window, clock, main loop
- Events + input handling
- Game state: title → playing → game over
- Update/draw separation and delta time (`dt`)
- Simple collision using `pygame.Rect`
- Score + high score saved to `save.json`

## Run

```bash
python -m pip install pygame
python main.py
```
## Menu

## Controls
- Arrow keys / WASD: move
- Enter: start / restart
- Esc: quit

## Save data
Writes `save.json` (high score only). Delete it to reset.

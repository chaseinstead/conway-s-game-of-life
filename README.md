# conway's game of life
a simple version of conway's game of life. canvas size, amount of rounds, cell size and output format (.gif image or .mp4 video) can be adjusted flexibly.

![Alt text](/animation_examples/1544103943.gif?raw=true)

# installation
for now, just download "game-of-life-v2.ipynb", adjust the variables in the "config" dict and play and play it in jupyter notebook.

# sample output
[8000 cells, 300 rounds, enlarged pixels by 4](../animation_examples/1544164863.mp4)
[small square](../animation_examples/1544110288.mp4)

![Alt text](/animation_examples/1544110298.gif?raw=true)
![Alt text](/animation_examples/1544108284.gif?raw=true)


# to do:
- improve performance (especially conversion from float64 to uint8)
- add templates and start figures (glider etc.)
- enable flexible coloring
- add infite mode and possibility to watch the game live (pygame?)

# conway's game of life
a simple version of conway's game of life that starts with random noise. canvas size, amount of rounds, cell size and output format (.gif image or .mp4 video) can be adjusted flexibly.

![Alt text](/animation_examples/1544103943.gif?raw=true)

# installation
for now, just download "game-of-life-v2.ipynb", adjust the variables in the "config" dict and play and play it in jupyter notebook.

# sample output

![Alt text](/animation_examples/1544167529.gif?raw=true)

[8000 cells, 300 rounds, enlarged pixels by 4](/animation_examples/1544164863.mp4)

[800 cells, 400 rounds, enlarged pixels by 15](/animation_examples/1544167102_aslink.gif)

[800 cells, 200 rounds, enlarged pixels by 15](/animation_examples/11544167193.gif)

[static](/animation_examples/1544166975.gif)


# to do:
- improve performance (especially conversion from float64 to uint8)
- add templates and start figures (glider etc.)
- enable flexible coloring
- add infite mode and possibility to watch the game live (pygame?)

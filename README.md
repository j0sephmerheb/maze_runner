# A mix betweena a pacman and a maze runner done using Python.
# The code contains 3 classes:
# Reader, runner, launcher
#
# The reader for reading a maze from a text file. The maze will contain the following:
# 0 for path
# 1 for wawll
# Ghosts: 2, 3, 4. Depending on their eye sight.
# Keys: a,c, f, h
# Doors:b, d, g, i
# The reader will detect the eye sight of the ghost and convert it into inaccessible cells.
# The reader will return the grid as a list of lists.
# 
# The Launcher will use the grid as a starting point
# Using algorithms it get the shortest path between the start and the end, and return it a tuple.
#
# The launcher class will take the tuple, then use PyGame to draw the grid elements, and the movement of the pacman on that grid which will be automatic not manual.



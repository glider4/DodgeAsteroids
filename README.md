# DodgeAsteroids
C program to randomly create X,Y,Z coordinates of asteroids and alert a spaceship of their movement.

 This program is designed to calculate and display the
 distances from a spaceship to an asteroid.  It is set up so
 that the user has to input a correct user name and password,
 which are given in the "ident.txt" document.  If the user
 enters in a correct user/password combo, the program runs.
 
 First, a set of asteroids (amount is controlled by "n" in main)
 are given a name, X, Y, and Z coordinates as random integers (in km) between
 1 and 1000.  These are then written to a file, "asteroids.txt".  The name
 of each asteroid is a single letter from the alphabet.
 
 This file, "asteroids.txt", is read and the distances to each asteroid
 are calculated based on the simple formula D = sqrt(X^2 + Y^2 + Z^2).  Each
 asteroid's distance is then written to a file with it's name, X, Y, and Z
 coordinates.  This file is called "distances.txt".
 
 The new file "distances.txt" is then read.  If the distance to an
 asteroid, any asteroid, is <750 kilometers away, a warning is displayed to the
 user about it.  A chart is also printed on the screen to display relatively,
 how close each asteroid is in a standard horizontal bar-chart format.
 Current position: need to sort and display sorted asteroids.

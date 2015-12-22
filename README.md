#Two dimensional triangular lattice ising model
The purpose of this program is to model characteristics of a lattice at different temperatures using an ising model.  
This model analyzes neighboring spins and calculates the magnetization, magnetic suseptibility and specific heat at different temperatures within a certain range.
This code was created by building upon a similar program for a square lattice which analyzes two neighboring spins (x and y) and calculates these characteristics at this point.
It then continues to scan down one point at a time and when it reaches a boundary, loops back to the beginning of the lattice.  
This turns the 2d lattice into a toroidal shape and allows for continuous scanning of the lattice.  
The lattice was altered by adding two new "diagonal" neighbors and by allowing scanning across a range of temperatures.
This was done by adding proper variables and altering the loops accordingly, as well as adding a loop to scan over multiple temperatures.  

Results: As the temperature rose, I found that specific heat followed a parabolic pattern, peaking around 3.5
Magnetic suseptibility and average magnetism converged as temperature grew

# LangevinChantrell
Numerical methods to solve Langevin Chantrell equations for equivalent magnetic diameter from hysteresis curve.

This code’s purpose is to calculate the effective magnetic diameter of a population of magnetic nanoparticles to a log-normal distribution from a dataset of magnetization vs magnetic field of magnetic nanoparticles in solution. 

The governing equations can be found at the following publication:  

DOI: 10.1021/acsnano.7b00609

Using equations 1-3 in the publication. 

This code fits a magnetic diameter to the data set by guessing a value, integrating the equations with the value for magnetic diameter over the set of magnetic field values, returning magnetization values from the set of equations, and minimizing the error between the dataset of magnetization and the calculated values of magnetization. 

The code returns the value of the effective volume-weighted magnetic diameter, the natural log of the standard deviation, the time it took for the code to execute, and a plot containing the fitted values plotted as a red line and original dataset plotted as scattered blue circles. 

Sample data for testing and a sample of the resultant plot are attached to the main branch of the repository.

Exercises using the Wright-Fisher application
===============

Open the coalescent-plot application from http://www.phytools.org/PopGen/.


It is possible to use this animator to follow the reproduction process forward in time and the coalescent process backwards in time one generation at a time. A new simulation is created by setting the parameters and pressing the "new plot" button. The simulation can then be controlled by the buttons in the bottom (right) part of the window, e.g. one generation at a time.

Set N = number of individuals = 10, and G = number of generations = 15.

## 1 - Thinking forwards in time

We will compute the sample mean and sample variance of various quantities. If you need the formula for the sample mean and sample variance, you can find them here: http://www.math.uah.edu/stat/sample/Variance.html 

- a) For each of gene copies of the first generation (i.e. each of the colored "balls" in the top row), write down how many generations they persist in the population. Are all gene copies still present in the population in the present (bottom row)? Do the recorded lengths of time (number of generations) tend to be similar to each other? If not, what phenomenon is driving the differences in survival time between gene copies?
- b) Calculate the mean and variance in the number of descendants of the first-generation gene copies in the next generation.
- c) Calculate the mean and variance in the number of descendants of the first-generation gene copies in the present (bottom row) generation.
- d) Compare the means from b) and c) and the variances from b) and c). Do these numbers fit your expectations about the Wright-Fisher process, given what we covered in lecture?

## 2- Thinking backwards in time (coalescence)

- a) Start a new simulation and choose 3 gene copies at random in the present (bottom row) generation. Do all these chosen gene copies in the present generation coalesce within the time span of our simulation (G)? If so, record the number of generations to coalescence (the first time they have a common ancestor) of all 3 gene copies. If they have not all coalesced by the time to get to the first generation, record that the copies did not coalesce and write down how many ancestors there are in the first generation.
- b) Repeat exercise a) 5 times, writing down the time to coalescence of all 3 gene copies (if it occurs). This should give you an idea about the variance of the process.
- c) Repeat exercises a) and b) above with N=5 and N=30. How does the time to coalescence for the 3 gene copies in the present scale with N? In other words, do they tend to coalesce faster when N is large or when N is small?

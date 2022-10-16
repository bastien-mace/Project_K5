# Project_K5
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bastien-mace/Project_K5/HEAD)

This project is based on Chapter 5 of Hannah Kokko's book "Modelling for Field Biologists and Other Interesting People". We translated into Python the MatLab script given in this chapter to build the optimal strategy matrix.
We went further this code to make it dynamic by simulating individuals playing the best strategies depending on their condition.
We finally implemented a simulation for a continuation of days, like a whole winter. To do that, we add two parameters: d_night the probability of death by predation during the night; and c_night the probability of consuming resources, so to decrease of one condition, during the night. Both parameters do not change with condition of the individual.

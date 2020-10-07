# Monte Carlo Animation: Project Overview

## Background
A Monte Carlo method is a computational algorithm which uses repeated random sampling from a probability distribution in order to approximate some numerical result. More information can be found on the Wikipedia page: https://en.wikipedia.org/wiki/Monte_Carlo_method.

In this project, I implemented a classical example of a Monte Carlo simulation to approximate the value of pi. For every iteration, a random point is drawn from a uniform distribution on the square with both x and y coordinates in the interval [[-1, 1]]. This square has an area of 4, while the unit circle lying inside the square has an area equal to pi * (1)^2 = pi. Thus, as the number of samples increases, the percentage of points which fall inside the circle will approach pi/4, allowing us to approximate the numerical value of pi.

The animation was created using Python's matplotlib library. The number of iterations was 10,000.

## Result
![Monte Carlo Animation](monte_carlo_animation.gif)

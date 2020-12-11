# Stochastic Processes 
some exercises for the stochastic processes course

### 1. Box-Muller method to create normally distributed data
In this exercise, firstly, a series of random numbers that are uniformly distributed is generated. Then the Box-Muller method is used to create a normally distributed dataset from them. Then, the probability distribution function p(x) for both of these datasets is constructed. In every case, a normal graph and logarithmic graph with error bars are included. Finally, I plot x<sup>n</sup> p(x) versus x for different n values.

### 2. Solving the Wiener Equation Numerically
Wiener process is a stochastic process that describes Brownian motion. It is a continuous process described with the equation:

dW/dt = η(t) .dt

where η(t) is a random function. It can be a uniformly distributed white noise.
Here I solve this equation numerically, plot a set of paths that are following this equation, and verify this relation for a Wiener process :

⟨ (W (t))<sup>2</sup> ⟩ = t    (this is an ensemble average)

### 3. Langevin Equation and Kramers-Moyal coefficients

The aim of this exercise is two solve a specific Langevin equation numerically. Then, calculating its correlation length and Markov length. And also computing the first, second, and fourth of Kramers-Moyal coefficients.

### 4. 2-dimensional Langevin Equations
in this exercise, two Langevin Equations are coupled. As before, we can solve them using the Euler method. After that Kramers-Moyal coefficients are calculated and plotted, each as a surface on 3-D space.


### 5. Poisson Process
Here I solve the equation for a Poisson Process numerically and then calculated the first 6 moments for this process. From those, we can find some characteristic parameters of our process.
A Poisson jump-diffusion process is a process where as well as our normal drift and diffusion terms, like in the Langevin equation, there is another term indicating jumps. The time difference between jumps obeys a Poisson distribution.


# Taming complexity with Approximate Master Equations

Mean-field arguments are often used to model the dynamics of complex systems by tracking the average state of the system. In many systems, these approaches fail to capture the discreteness of available states, often counted in discrete number of agents or connections. For example, by assuming an infinite population, mean-field arguments ignore the possibility of a stochastic extinction of a dynamical process.

Master equations differ from mean-field approaches, even though they are also described through systems of differential equations. Instead of only tracking the average state of a system, master equations track the temporal evolution of the probability distribution of finding the system in a given state, over all possible states for that system.

Here are some references that might be of interest in combination with this tutorial:
- **_Modelling with the Master equation_** {cite}`haag2017modelling`
- **_Stochastic numerical methods: an introduction for students and scientists_** {cite}`toral2014stochastic`. This is a general book on modeling methods for stochastic processes which features an extremely useful introduction to master equations as well as related numerical solution methods.

Our main goal is to provide a tutorial on the *conceptual* design of master equations and on *computational* to solve them. As applications, we will cover classic models from the study of complex systems: Lotka-Volterra predator-prey dynamics, or Susceptible-Infectious-Susceptible dynamics from disease modeling.

## Table of content
```{tableofcontents}
```

## References
```{bibliography}
```

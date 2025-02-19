# Compartmental Model (S.I.R.):
Compartmental model for the spread of an infectious disease is the SIR (Susceptible-Infected-Recovered) model. 
Here we consider three compartments (S,I,R) and aim to understand the dynamics between these groups through differential equations that describe how one compartment transitions to another.
 -	Susceptible (S): Individuals who have not yet been infected but are at risk.
 -  Infected (I): Individuals who are currently infected and can spread the disease.
 -  Recovered (R): Individuals who have recovered from the disease and are assumed to be immune.
Three first order differential equations represent number of individuals in these compartments with respect to time.
Python code for S.I.R. model results presented by using Scipy (odeint) solver.

## S.I.R. Model Parameter Estimation:
Many infectious disease cases parameters $\beta_{est}$ , (transmission rate) and $\gamma_{est}$ (recovery rate) are often unknown and must be 
estimated from observed data. One way to do this is by minimizing the difference between model predictions and 
real-world data using optimization methods. Here, we will use least square fitting to estimate parameters from noisy data.

## Sensitivity Analysis: 
Sensitivity analysis helps assess how changes in parameters affect the model's outcome. In epidemiological models, this can show how sensitive the disease spread is 
to changes in transmission or recovery rates. This is essential for understanding key drivers in disease dynamics. 

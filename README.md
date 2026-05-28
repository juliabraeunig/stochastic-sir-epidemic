# Stochastic SIR Epidemic Simulation with Peak Detection

## Overview
This project implements a stochastic Susceptible-Infected-Recovered (SIR) 
model to simulate epidemic dynamics and develop methods for detecting 
epidemic peaks in real time. The work bridges theoretical simulation and 
empirical application using New York State COVID-19 testing data.

## Methods
- Discrete-time stochastic SIR model with binomial sampling
- 1,000 Monte Carlo simulations per scenario
- Rolling average smoothing (3, 5, and 7-day windows)
- Log-log phase plane analysis for peak characterization

## Repository Structure
- `Analysis_newupdates2.Rmd` -- main simulation and analysis
- `New_York_State_Statewide_COVID19_Testing_20260522.csv` -- empirical data

## Dependencies
R packages: `dplyr`, `ggplot2`, `zoo`

# Secondary_band

This project comprises part of my Master's Thesis. 

The aim of the project is to compute the value of an american option on the Spanish secondary band market for 
the following day. For this purpose, a Machine Learning (ML) model has been developed to forecast the secondary band price. The pipeline includes 
several ML algorithms, where the input data for the models are different Spanish electricity system variables. 

The output obtained from the model is used as a baseline to evaluate an american option. The Last-Squares Monte Carlo 
apporach [1] is the framework used to approximate the value of the american option via simulation.

#### Diagram of the ML model:

![machine learning pipeline - page 1](https://cloud.githubusercontent.com/assets/23661636/24581055/52b2046a-1714-11e7-843a-ac559f3b1361.png)

---
References:

[1] F. Longstaff and E. Schwartz, "Valuing American Options by Simulation: A Simple Least-Squares Approach," _Rev Financ Stud_,
vol 14, (1), pp. 113-147, 2001. DOI: https://doi.org/10.1093/rfs/14.1.113

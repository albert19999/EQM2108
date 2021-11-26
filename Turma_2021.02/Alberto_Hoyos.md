## Final project. Course: EQM 2108
## Title: Modeling and optimization of methane oxidative coupling using machine learning (Optuna and Particle Swarm)
## Student: Carlos Alberto Castro Hoyos
## Professor: Amanda Lemette 

## Introduction
### The oxidative coupling of methane (OCM) is an important route for the direct transformation of methane (from natural gas) to more valuable hydrocarbons. Nowadays, based on the importance of producing hydrocarbons for any human needs, it is required to develop new methods for obtention of these compounds (including: modeling, simulation and optimization). 
### Precisely, the main aim of this article is to show an optimization method sourced on Machine Learning, testing two techniques (Optuna and Particle Swarm) validating the perfomance of the model, according the variation/influence of a meta estimator´s hyperparameters.  This estimator (random forest) fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fittin  

## Methodolody
## This evaluation is divided in 3 steps:
## The first step: It consists on defining the input and output variables provided from the dataset (OCM). According to the database, five variables are set as input variables (methane molar fraction, methane/oxygen feeding molar flow, temperature, pressure and volumetric flow) and seven variables as output variables (methane conversion, oxygen conversion, selectivity for C2, yield for C2, ethane yield, carbon dioxide yield and carbon monoxide yield).
## The second step: It consists on setting the output variables used on the model (yield of C2, ethane yield and carbon dioxide yield). For the proposal of this article, these output variables are selected randomly. On this step, the assessment of the relation among variables is done through the analysis of the correlation matrix.
## The thrid strp: 

The performance assessment of the models is calculated based on the obtained acurracy (R^2).  it is requiered to validate the influence of the selected hyperparameters on them. T  
## Results
## Discussion
## Conclusion
## References

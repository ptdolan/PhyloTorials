# Week 2
## Installing BEAST and BEAUTI
To preform Bayesian Phylogenetic Inference, we will need to install two programs, BEAST and BEAUTI. These programs are built to perform Markov Chain Monte Carlo (MCMC) sampling of phylogenetic trees to perform robust estimation of tree parameters.

[BEAST Paper](https://academic.oup.com/ve/article/4/1/vey016/5035211)

[Article on MCMC](https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo)


### BEAUTI
BEAUTI is used to generate the instruction file for the MCMC. It takes an alignment as input and then allows you to choose the parameters to optimize during MCMC simulation, and the length and details of the MCMC chain run. It outputs an .xml file that is used by BEAST to run the simulation. 

### BEAST
BEAST is the workhorse program for running the MCMC based on the .xml instructions from BEAUTI. Once loaded, BEAST runs the MCMC as directed in BEAUTI. 


# Next week:
How do we run a beast MCMC run? 
What do we do with the output from BEAST?





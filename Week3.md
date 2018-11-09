# Week 3

## Concepts and Activities
We are going to start running and interpreting phylogenies we get from our BEAST runs. How do we interpret an MCMC run? How do we know when we have successfully searched tree space?

## Tools
### Running BEAUTI
1. Load alignment (fasta, or other input format)
2. Choose and intialize parameters and priors
3. Export .xml

### Running BEAST
1. Load .xml
2. Set up run and log files
3. Set random number seed (if desired).
4. BEAST will run in window, and output .log files as directed in .xml. Confirm files and location before running too long.

### Viewing Trace with Tracer
1. Load .log file into Tracer by dragging or selecting.
2. Explore the convergence of the parameters.


## Terms and Definitions

Important to remember is the way in which Bayes' Rule is implemented here.

Bayes' Rule: Pr(A|B)=(Pr(B|A)*Pr(A))/Pr(B)

Check out the [BEAST glossary](http://beast.community/glossary.html)

>The posterior (or posterior probability density) is the entity that an MCMC analysis attempts to obtain an estimate of. The posterior is the probability distribution over the parameter state space, given the data under the chosen model of evolution. The posterior P(Parameters, Tree|Data) is the (normalized) product of the likelihood, *Pr{Data|Parameters, Tree}*, and the prior P(Parameters, Tree).

Joint = Posterior x Prior
Pr(Parameters,Tree|Data)= Pr(Data|Parameters,Tree) x Pr(Parameters,Tree)

# Next week:
Analyze outputs from our tree in python or R!

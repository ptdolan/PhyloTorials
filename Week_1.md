# Week 1: Alignment and tree inference

_We are building a toolkit that will enable you to do your own analyses of molecular evolution. We first need to establish a few concepts and get the necessary software to get you going._

## Concepts and activities.

Using our protein alignment from last time ("Week 0"), we generated your first phylogenetic tree using FastTree, a software for estimating a maximum likelihood (ML) tree based on a multiple sequence alignment (MSA). 

We also discussed likelihood (https://en.wikipedia.org/wiki/Likelihood_function), and how comparing likelihoods between models can tell us how well the tree ('the parameters') explains the relationship of sequences in the MSA ('the data’).

And we talked about the BLOSUM matrix, one example of a substitution matrix for scoring sequence alignment. 
 * Wikipedia has a nice article on it [here](https://en.wikipedia.org/wiki/BLOSUM)
 * The original paper reporting BLOSUM is [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC50453/)
 
## Software.

We also discussed how to install software from the command line. The software tools we installed were found in the homebrew repository. We installed muscle for sequence alignment and FastTree for inferring the tree from the MSA. 
>/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

This is the site for homebrew-bio, the biology-focused software repository we use to install software for the analysis.

[homebrew-bio](https://github.com/brewsci/homebrew-bio)

After adding the correct repositories (see link [here](https://github.com/brewsci/homebrew-bio)), we installed the programs with:

>  brew install muscle

>  brew install fasttree

We can run these programs using the commands:

>  muscle -in myUnaligned.fasta -out myAligned.aln

>  FastTree myAligned.aln > myFastTree.tree

---

## Next week: Visualizing Trees and Installing BEAST: Bayesian Evolutionary Analysis by Sampling Trees

We will discuss all of this next week, but here are the links, in case you want to look anything over. 

[BEAST](http://beast.community/install_on_mac)

[BEAST Tutorials](http://beast.community/first_tutorial)

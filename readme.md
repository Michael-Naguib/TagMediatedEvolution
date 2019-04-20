# TagMediatedEvolution
 This code is based off of the paper: http://sandip.ens.utulsa.edu/aamas05LAMAS_LNAI-tags.pdf 
- Tag Mediated evolution in 5 sentences or less is where a population of Cooperators and Defectors play 
the Prisoner's Dilemma Game. Only individuals with identical tags may play, and if an individual's tag 
is unique (no one has the same tag) an opponent is chosen at random. The payoffs are calculated for the 
players and the next generation is computed using Stochastic Universal Sampeling.
- The result of this paper is that there was a critical tag length for which the population 
would converge to becoming Defectors vs Cooperators. 

## Dependencies
- Recommended: use Anaconda
- Deps: random, copy, tqdm, math, matplotlib, numpy

Code By Michael Naguib 
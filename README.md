# Simple implementation and application of genetic algorithms
### Disclaimer
This code was written over the course of one or two nights in February of last year. I am now deciding to make it public because I think it's cool. However, this should not be taken as anything more than it is: code written by a teenager in one or two nights. So forgive me for how messy or stupid it is.

### Aim
This notebook aims at creating a simple trading strategy using a genetic algorithm approach. The algorithm works by randomly generating actions for the different types of situations that can occur. Then, the strategy is given a score based on performance and the different randomly generated strategies can reproduce, with higher weight on more successfull parent strategies, while still keeping some genes random. Then, these strategies are left to reproduce and evolve for some generations, and the idea is that by incentivizing more successful strategies to reproduce, over the course of many generations the initially random strategies will become more and more successful.

### Limitations
This project is just a proof of concept and has some clear limitations: the different "situations" that a strategy can see are very limited, and the "situations" are only a string of binary digits. Additionally, any investor would probably laugh at strategies so simple. However, this was still a fun exercise to put in practice what I've seen online about genetic algorithms.

### Potential uses
I strongly suggest anyone who cares about their money not to use a strategy trained in this fashion to handle their savings. However, the code used for the strategies and evolving them can be re-used and expanded for more ambitious projects regarding Genetic Algorithms.

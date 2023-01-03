# Six Degrees of Reddit Bacon - Social Media as a Small-World Network
This project aims to construct a small-world network model of Reddit communities to investigate interconnectivity on social media. 
## Table of contents
* [Background](#Background)
* [Methodology](#Methodology)
* [Results](#Results)
* [Conclusion](#Conclusion)

## Background
Frigyes Karinthy introduced the concept of 'six degrees of separation' in a short story in 1929. The idea proposes that any given person can be connected with any other person by a chain of familiarity that is comprised of no more than 6 individuals. The concept later found colloquial implementation as a game called "Six Degrees of Kevin Bacon" in which participants attempt to connect actor Kevin Bacon with any other actor by films the actors have mutually appeared in.

Small-world networks serve as an intuitively useful mathematical model for these chains of interconnectivity. This type of graph consists of nodes which are connected by edges and is characterized by the traits that no single node is neighboring most other nodes, but most nodes are connected by a small number of node-edge steps. The extent of connectivity of a small-world network is mathematically constrained such that the average distance $L$ between two arbitrary nodes grows proportionally to the logarithm of the total number of nodes $N$.
$L\propto \log N$

Testing to see if a small-world network could be constructed using the personal familiarity of all people would certainly be an impossible task. However, social media may offer a parallel which is much more quantifiable. Reddit is a site where users post content and have discussions accross many sectionalized communities called 'subreddits.' These communities span a wide bredth of topics and interests and attract users from all walks of life.

## Methodology
In this project subreddits are modeled as nodes and users serve the role of edges. Using the 
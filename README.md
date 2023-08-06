# Rare Events Sampling in Python

Python implementation of the Uniformly sampled, Pruned and Enriched Rosenbluth Method (FlatPERM) algorithm used on variations of Self-Avoiding Walks (SAWs) meaasuring different parameters - Interactions and Spikes. 

Self-Avoiding Walks with interactions (Interacting SAWs or ISAWs) are simple SAWs where any pair of non-consecutive, adjacent sites of the walk are characterized as 'interacting'. This model may be reflective of the energy of a polymer; a configuration with a high number of interactions would be reflective of a high energy polymer, vice versa. 

Self-Avoiding Walks with spikes (Cactus Walks) are simple SAWs where each site of the walk can have a maximum of one unit-length 'spike' in any direction that still ensures self-avoidance. In this case, the length of the walk is measured by the spine - counting all steps of the walk that are not spikes. An example of a Cactus Walk would be U(RL)L(DU), where U D L R correspond to steps Up Down Left and Right respectively. This would be a 2 step and 2 spike configuration with the spikes highlighted with parentheses and the spine being all other (not highlighted) steps. This model may be used to reflect the rigidity of a polymer; spike-dense configurations resemble more rigid polymers, vice versa.

Both SAW variations can be visualized in their respective Jupyter Notebooks (.ipynb) along with the data collected from running FlatPERM on them.

This project builds on last year’s research done by Kane Kelser (https://github.com/Kane-Kesler?tab=repositories). 
Research done by Pedro Villegas and Ahmad Naveed.

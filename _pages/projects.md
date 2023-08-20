---
layout: page
title: Research
permalink: /research/
description: 
nav: true
horizontal: false
---

<b> <font size="5">  
Origins and evolution of endosymbiosis
</font>  </b> 

<i> June 2021 - Present. <br>
Supervisor: Dr. Chaitanya S. Gokhale </i>

How did biological organisms become so complex? 
Endosymbiosis is the prototypical example of an egalitarian evolutionary transition and is central to the origins of many complex biological systems. 
Why do only some symbioses undergo evolutionary transitions, and how does the host-symbiont relationship change during this process? 
Here, we characterise endosymbiosis by two emergent collective-level properties: the relationship between the host and symbiont (mutual dependence) and reproduction (reproductive cohesion). 
Using methods from adaptive dynamics, we study the co-evolution of the traits underlying these properties. 
Our central result is a robust demonstration that even when investments in dependence and cohesion are uncorrelated, host-symbiont mutual dependence arises faster than reproductive cohesion. 
Further, we show that the collective’s formation and shared fate, coupled with different generation times of the host and symbiont, leads to an emergent asymmetry in how much they invest in the collective. 
Lastly, we account for biological realism that previous models have ignored and show that this can preclude a successful evolutionary transition towards stable endosymbiosis. Together, this work uncovers a fundamental property of endosymbioses, highlighting the immense effects of simple ecological factors and providing a clear way forward for theoretical and empirical investigations.

This work, joint with Dr. Peter Czuppon, resulted in a manuscript currently under review. It can be found on biorXiv here: [https://doi.org/10.1101/2023.07.17.549359](https://doi.org/10.1101/2023.07.17.549359)

<b> <font size="5">  
Antibiotic-mediated interactions and stability in microbial communities
</font>  </b> 

<i> June 2021 - Present. <br>
Supervisors: Dr Chaitanya Gokhale, Dr Prateek Verma. </i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="https://gauravathreya.github.io/assets/img/lattice_model.png" alt="" title="example image" />
    </div>
</div>
<div class="caption">
    A lattice model of a microbial community with three microbes - one that produces a particular antibiotic (red), one that is sensitive to this antibiotic (yellow), and another that degrades the antibiotic by producing another chemical (blue). For certain values of diffusivities of the antibiotic and degrader molecules, this community shows stable co-existence via cyclical dynamics. 
</div>

The immense diversity observed in natural microbial communities is surprising in light of the numerous weapons microbes have evolved to inhibit each other’s growth. 
It is thus imperative to understand which interaction patterns can sustain a biodiverse community when individual species antagonistically affect one another. 
In this study, we leverage potent methods from theoretical ecology to show how antibiotic-mediated interactions between microbes drive biological diversity.
Building on previous experimental and theoretical results, we analyse the dynamics induced by various interaction graphs involving antibiotic production, resistance, and degradation. 
Previous work has recognised the importance of a particular producer-sensitive-degrader (PSD) motif in the interaction graph. 
We study this motif in detail and elucidate the mechanistic reason for this importance. 
Concretely, we give exact rules for coexistence in some simple cases where exhaustive enumeration of the interaction graphs is feasible. 
More generally, our results suggest that the PSD motif, in combination with a cyclic interaction structure, is sufficient for stable coexistence in well-mixed populations. 
Using individual-based simulations, we then study the importance of the PSD motif in spatially structured populations. 
We show that community coexistence is robust for an extensive range of antibiotic and degrader diffusivities. 
Together, these findings illuminate the interaction patterns that give rise to diversity in complex microbial communities, stressing that antagonism does not imply a lack of diversity and suggesting clear approaches for culturing synthetic microbial consortia.

This manuscript resulted in a publication currently under review. It can be found on biorXiv here: [https://doi.org/10.1101/2023.02.15.528676](https://doi.org/10.1101/2023.02.15.528676)

<b> <font size="5">  
Reading project on stochastic processes
</font>  </b> 

<i> February 2021 - May 2021. <br>
Supervisor: Dr Deepak Dhar. </i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="https://gauravathreya.github.io/assets/img/2d_bm.png" alt="" title="example image" />
    </div>                                              
</div>
<div class="caption">
    A sample path of 2-dimensional Brownian motion starting at the origin.
</div>

We began with the prototypical example of a discrete stochastic process - the simple random walk on $$\mathbb{Z}$$. After studying it in some detail, we proceeded to study processes that take place over continuous time and in continuous space, and with different memory structures. In particular, I studied discrete-time Markov chains, continuous-time Markov chains, with birth-death processes and branching processes in detail. We then moved on to the construction and properties of Brownian motion, with a focus on the zero set and recurrence-transience results. We ended with an elementary introduction to martingales and stochastic integration. 

This project, outside of dealing with topics fundamental to theoretical biology, introduced me to multiple results and ideas that I found interesting. Some that I particularly liked are the fractal nature of the zero set of Brownian motion, the Polya recurrence theorem, and its counterpart for Brownian motion. There are also several results relating to the simple random walk - such as the arc sine law and the formula for the probability of $$r$$ changes of sign - that show how intuition and the central limit theorem do not correspond to reality when waiting times are large and fluctuations are important. 

<b> <font size="5">  
A Subgraph Mining Approach to Detecting Structural Motifs in Local Environments
</font>  </b>

<i> June 2020 - December 2020. <br>
Supervisor: Dr M.S. Madhusudhan. </i>

A protein's tertiary structure is determined by its amino acid sequence, and often involves residues which are far apart in sequence but in close physical proximity. This arrangement is difficult to predict from the residue sequence alone, and it is therefore of much interest to obtain a mechanistic understanding of this sequence-structure mapping. In this project, we aimed to understand the mechanisms of structure stabilization via the examination of three-dimensional packing in known protein structures.  

Based on earlier work in the group, we constructed a description of the local environment around an amino acid in terms of certain labelled graphs, with labels depending on the amino acid identities and the distance between them (which determines the type of interaction). Iterating this process over a large set of known protein structures gives us a collection of possible local environments around each amino acid. We used these collections to quantify the types of interactions that are most commonly found around a given amino acid. For our purposes, I used a modified version of a well-known graph algorithm called [gSpan](https://sites.cs.ucsb.edu/~xyan/software/gSpan.htm) that uses iterative depth-first searches to efficiently search a collection of graphs for subgraphs that appear frequently.

We found preliminary evidence for differential preferences in neighbourhood size across the amino acids, and observed some non-trivial correlations between the frequent presence of some types of interactions. This analysis enabled us also to identify groups that occur frequently around multiple centres, indicating that there are some groups that are especially important for imparting local stability in varied contexts.

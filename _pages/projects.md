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
Supervisor: Dr Chaitanya Gokhale </i>


Lynn Margulis and her theory of endosymbiosis singularly reshaped our understanding of the origin of eukaryotes and their complexity.
In this project, we build on a diverse body of knowledge on these topics by developing a theoretical framework for understanding the eco-evolutionary dynamics of endosymbiosis. 
Specifically, we aim to understand how the generation times of and ecological relationships between the host and symbiont affect the transition from facultative to obligate symbiosis.    
We have little theoretical understanding of this question, and previous work has shown that a multitude of interactions, and other factors such as differences in generation times, are important for the facultative-obligate transition. 
Even if there is an immediate benefit such as in the case of mutualists, obligate endosymbiosis can arise only if lower-level conflicts can be resolved in favour of the host-symbiont association. 
In this context, we combine the frameworks of evolutionary game theory and adaptive dynamics to develop practical ideas applicable to more general settings, and aid in generating testable hypotheses.

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

The immense diversity observed in natural microbial communities is surprising in light of the numerous weapons microbes have evolved to inhibit each other's growth. 
In this study, we study antibiotic-mediated interactions between microbes using classical models from theoretical ecology. 
Building on previous experimental and theoretical results, we analyse the ecological dynamics induced by various interaction graphs that involve antibiotic production, resistance, and degradation. 
For some simple cases where exhaustive search of interaction graphs is possible, we give exact rules for the strain phenotypes required for the existence of a stable, steady-state of the community dynamics. 
Sufficient conditions for community stability for more complex cases are determined computationally.
These results strengthen an earlier observation - a particular producer-sensitive-degrader (PSD) motif is crucial for community stability. 
By relaxing the assumption of well-mixed populations, we study the importance of the PSD motif in spatially structured populations.
Using individual-based simulations, we show robust community coexistence for an extensive range of values of the diffusivities of the antibiotic and degrader chemicals. 
Thus we explicitly characterise our understanding of which (and how) patterns of biotic interactions are essential for stability in both structured and unstructured microbial communities.

<b> <font size="5">  
Stochastic Processes
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


The aim of this reading project was to gain an understanding of the theory of stochastic processes. My motivation to study these topics came from a desire to understand probabilistic models of biological evolution. We began with the prototypical example of a discrete stochastic process - the simple random walk on $$\mathbb{Z}$$. After studying it in some detail, we proceeded to study processes that take place over continuous time and in continuous space, and with different memory-structures. In particular, I studied discrete-time Markov chains, continuous-time Markov chains, with birth-death processes and branching processes in detail. We then moved on to the construction and properties of Brownian motion, with a focus on the zero set and recurrence-transience results. We ended with an elementary introduction to martingales and stochastic integration. 

This project introduced me to multiple results and ideas that I found interesting. Some that I particularly liked are the fractal nature of the zero set of Brownian motion, the Polya recurrence theorem, and its counterpart for Brownian motion. There are also several results relating to the simple random walk - such as the arc sine law and the formula for the probability of $$r$$ changes of sign - that show how intuition and the central limit theorem do not correspond to reality when waiting times are large and fluctuations are importatn. 

<b> <font size="5">  
A Subgraph Mining Approach to Detecting Structural Motifs in Local Environments
</font>  </b>

<i> June 2020 - December 2020. <br>
Supervisor: Dr M.S. Madhusudhan. </i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="https://gauravathreya.github.io/assets/img/subgraph_diversity_with_support.png" alt="" title="example image" />
    </div>
</div>
<div class="caption">
   The number of frequent subgraphs as a function of the minimum support, defined in the algorithm. 
</div>

A protein's tertiary structure is determined by its amino acid sequence, and often involves sequentially distant residues in close proximity. This arrangement is difficult to predict from the residue sequence alone, and it is therefore of much interest to obtain a mechanistic understanding of this sequence-structure mapping. In this project, we aimed to understand the mechanisms of structure stabilization via the examination of three-dimensional packing in known protein structures.  

Based on earlier work in the group, we constructed a description of the local environment around an amino acid in terms of certain labelled graphs, with labels depending on the amino acid identities and the distance between them (which determines the type of interaction). Iterating this process over a large set of known protein structures gives us a collection of possible local environments around each amino acid. We used these collections to quantify the types of interactions that are most commonly found around a given amino acid. For our purposes, I used a modified version of a well-known graph algorithm called [gSpan](https://sites.cs.ucsb.edu/~xyan/software/gSpan.htm) that uses iterative depth-first searches to efficiently search a collection of graphs for subgraphs that appear frequently.

We found preliminary evidence for differential preferences in neighbourhood size across the amino acids, and observed some non-trivial correlations between the frequent presence of some types of interactions. This analysis enabled us also to identify groups that occur frequently around multiple centres, indicating that there are some groups that are important for imparting local stability in varied contexts.

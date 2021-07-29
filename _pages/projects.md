---
layout: page
title: Projects
permalink: /projects/
description: 
nav: true
horizontal: false
---

<b> <font size="5">  
Production and Maintenance of Biodiversity in Microbial Communities with Antibiotic-mediated Interactions    
</font>  </b> 

<i> June 2021 - Present. <br>
Supervisors: Dr Chaitanya Gokhale, Dr Prateek Verma. </i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="/al-folio/assets/img/PD_SP_DS.jpg" alt="" title="example image" />
    </div>
</div>
<div class="caption">
    A simplex plot of the path to coexistence in a community with two antibiotics and three species.
</div>

Microbes often form multi-species communities via antibiotic-based interactions. This project attempts to understand how the evolution of ecological interactions within the communities drives the production and maintenance of biodiversity. Kelsic et al. (2015) showed that pairwise production-inhibition interactions can be mediated by degraders to give robust, stable coexistence in both the well-mixed and spatially distributed settings. Their results demonstrate this effect of higher-order interactions for communities with as many as 6 species with the ability to produce and degrade 5 distinct antibiotics. However, it is unclear which of these community configurations can be realized during the process of evolution. Work in this direction by Vetsigian (2017) showed that allowing production and degradation of one antibiotic can, after many cycles of reproduction, give rise to a 3-strain community that is both ecologically and evolutionarily stable, and two antibiotics can similarly give rise to a stable 5-strain community. Notably, the interaction graph of the stable 1-antibiotic community can be identified as a subgraph of the stable 2-antibiotic community, suggesting a type of modularity in the interactions that induce stability.  

We aim to systematically study the evolution of these communities when a progressively larger amount of phenotypic diversity i.e., number of antibiotic molecules can be accessed by the evolving strains. In particular, which patterns of interaction are sufficient for stability, and which of these are actually realized in nature? 

<b> <font size="5">  
Stochastic Processes
</font>  </b> 

<i> February 2021 - May 2021. <br>
Supervisor: Dr Deepak Dhar. </i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="/al-folio/assets/img/2d_bm.png" alt="" title="example image" />
    </div>
</div>
<div class="caption">
    A sample path of 2-dimensional Brownian motion starting at the origin.
</div>


The aim of this project was to gain an understanding of the theory of stochastic processes. My motivation to study these topics came from a desire to understand probabilistic models of biological evolution. I began from the prototypical example of a discrete stochastic process - the simple random walk on $$\mathbb{Z}$$. After studying it in some detail, I proceeded to study processes that take place over continuous time and in continuous space, and with different dependence-structures on the past. In particular, I learnt about discrete-time Markov chains, continuous-time Markov chains, with some notable examples being birth-death processes and branching processes. Then I learnt about the construction and properties of Brownian motion, with a focus on the zero set, and recurrence-transience properties. For the last part of the project, I decided to begin familiarizing myself with martingales and stochastic integration. 

This project introduced me to multiple results and ideas that I found interesting. Some that I particularly liked are the Polya recurrence theorem and its counterpart for Brownian motion, which speak to the puzzling nature of random walks and the effect of introducing continuous time and space. There are also several results relating to the simple random walk that show how intuition and the central limit theorem do not correspond to reality when waiting times are large and fluctuations are present. Another idea that I thought was interesting was that the discrete versions of the processes were fundamental to understanding the continuous versions - both with the notion of embedded Markov chains and the construction of Brownian motion from discrete random walks. To learn more about these topics, I am taking advanced undergraduate courses on measure theory and integration, measure-theoretic probability, and stochastic processes over the next two semesters.  

The books that I consulted for this project are as follows. For the parts relating to random walks, I used <i> An introduction to probability theory and its applications, Volume 1 </i> by William Feller. For the rest of the project, I used <i> Introduction to Stochastic Processes </i> by Greg Lawler and <i> Brownian Motion </i> by Peter M&ouml;rters and Yuval Peres. 

<b> <font size="5">  
A Subgraph Mining Approach to Detecting Structural Motifs in Local Environments
</font>  </b>

<i> June 2020 - December 2020. <br>
Supervisor: Dr M.S. Madhusudhan </i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="/al-folio/assets/img/subgraph_diversity_with_support.png" alt="" title="example image" />
    </div>
</div>
<div class="caption">
   The number of frequent subgraphs as a function of the minimum support, defined in the algorithm. 
</div>

A protein's tertiary structure is determined by its amino acid sequence, and often involves sequentially distant residues in close proximity. This arrangement is difficult to predict from the residue sequence alone, and it is therefore of much interest to obtain a mechanistic understanding of this mapping. In this project, we aimed to understand the mechanisms of structure stabilization via the examination of three-dimensional packing in solved protein structures.  

Based on earlier work in the group, we constructed a description of the local environment around an amino acid in terms of certain labelled graphs, with labels depending on the amino acid identities and the distance between them (which determines the type of interaction). Iterating this process over a large set of previously discovered protein structures gives us a collection of possible local environments around each amino acid. We used these collections to quantify the types of interactions that are most commonly found around a given amino acid. This was done using a Python implementation of the [gSpan](https://sites.cs.ucsb.edu/~xyan/software/gSpan.htm) algorithm, which finds all subgraphs present in more than a user-defined number of the initial collection. 

We found preliminary evidence for differential preferences in neighbourhood size across the amino acids, and observe some non-trivial correlations between the frequent presence of some types of edges. This work allowed us to identify some mechanisms that could be important for stability in varied contexts. It enables us also to identify chemical groups that occur frequently around multiple centres, indicating that there are some chemical groups that are almost universally important for imparting local stability.

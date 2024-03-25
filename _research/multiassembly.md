---
title: "DNA/RNA Sequence Multiassembly"
layout: single-portfolio
excerpt: "<img src='/images/research/splicing-graph.png' alt='splice graph'>"
collection: research
order_number: 10
header: 
 og_image: "research/splicing-graph.png"
---


The assembly of full RNA and DNA sequences from short sequence data is a fundamental computational problem in biology.  A highly successful approach to addressing assembly problems has been to express them abstractly in terms of computational problems on graphs, such as 
decomposing flow in a network.  This project builds on this approach to develop 
state-of-the-art algorithmic approaches to better assemble sequences with guarantees on
computational efficiency and the quality of the assemblies produced.


We consider both new computational problems and variations that arise in genomic assembly
applications, in which the goal is to use information from short
DNA read sequences to assemble (and potentially also quantify) one or more longer sequences that
represents some biological object (e.g. a DNA or RNA sequence).
While there are existing tools in this space, they are often built around heuristic methods that
do not guarantee an optimal solution is found.  The tools we propose are built around 
explicit formulations of the problems and on exact computational methods, that can
advance the state-of-the art from both theoretical and practical perspectives.
The research is organized around computational challenges in computing flow decompositions,
coping with uncertainty in data, and handling multiple samples. 

<img src="/images/research/splicing-graph.png" style="display: block; margin: auto;" />



## Funding

- [NSF-2309902](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2309902) Scaling Flow Decomposition to Multi-Sample Multiassembly and Comparison (joint with [Lucia Williams](https://lgw2.github.io), University of Montana)

## Select Publications

- L. Williams, A. I. Tomescu, B. Mumey. Flow Decomposition With Subpath Constraints. IEEE/ACM Transactions on Computational Biology and Bioinformatics, 20(1), 360–370. 2023.
[doi.org/10.1109/TCBB.2022.3147697](http://doi.org/10.1109/TCBB.2022.3147697)

- Fernando H.C. Dias, Lucia Williams, Brendan Mumey, and Alexandru I. Tomescu.
Efficient Minimum Flow Decomposition via Integer Linear Programming.
Journal of Computational Biology. 1252-1267. 2022. 
[doi.org/10.1089/cmb.2022.0257](http://doi.org/10.1089/cmb.2022.0257)

- M. Cáceres, B. Mumey, E. Husić, R. Rizzi, M. Cairo, K. Sahlin, A. I. Tomescu. Safety in Multi-Assembly via Paths Appearing in All Path Covers of a DAG. IEEE/ACM Transactions on Computational Biology and Bioinformatics, vol. 19, no. 6. 3673-3684. Dec 2022.
[doi.org/10.1109/TCBB.2021.3131203](http://doi.org/10.1109/TCBB.2021.3131203)





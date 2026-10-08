---
title: "Filtering Wasteful Vertex Visits in Breadth-First Search"
collection: publications
permalink: /publication/SCW23-filter
excerpt: 'In this work, we analyze distributed Breadth First Search for potential filtering opportunities for the messages transmitted. We identify techniques to reduce the storage requirement for such a filtering logic and discuss implementation considerations for filtering.'
date: 2023-11-12
venue: '13th Workshop on Irregular Applications: Architectures and Algorithms - SCW ’23 Workshops of The International Conference on High  
Performance Computing, Network, Storage, and Analysis'
paperurl: 'https://prachatos.github.io/files/filter.pdf'
codeurl: ''
citation: ''
authorlist: '<b>Prachatos Mitra</b>, Alexandros Daglis'
shortname: 'SCW 2023'
---
In this work, we analyze distributed Breadth First Search for potential filtering opportunities for the messages transmitted. We identify techniques to reduce the storage requirement for such a filtering logic and discuss implementation considerations for filtering.

<p align="center"><img src="/images/bfs-filtering-efficiency.png" alt="Filtering efficiency against logical partition count"></p>

Filtered vertex visits as a function of logical partition count, for graphs of 2^20, 2^24 and 2^27 vertices.

<p align="center"><img src="/images/bfs-architecture.png" width="500" alt="Hierarchical filtering architecture"></p>

The hierarchical architecture the analysis targets, with filtering at the PE, group and switch levels.

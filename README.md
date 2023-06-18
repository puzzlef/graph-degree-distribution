Obtain the degree distribution of a static graph (in MTX format).

In this experiment, we measure the **degree distribution** of a number of
**static graph datasets**. As logging all the degrees of a graph is *not*
*feasible*, we *compress the degree distribution* into **blocks** (or *bins*)
such that there are a total of **256 blocks**. The degree distribution is then
measured by counting the number of nodes in each block.

The results show that in general graphs have a **dual power-law degree**
**distribution**, i.e., the degree distribution follows a power-law distribution
in the **low-degree region** and another power-law distribution in the
**high-degree region**. The transition point between the two power-law regions
can be called the **knee** of the degree distribution, and can be determiner of
the performance of graph algorithms.

All outputs are saved in a [gist] and a small part of the output is listed here.
Some [charts] are also included below, generated from [sheets].

<br>

[![](https://i.imgur.com/CUHZlks.png)][sheetp]
[![](https://i.imgur.com/6OwxpwX.png)][sheetp]
[![](https://i.imgur.com/o8sDC6b.png)][sheetp]
[![](https://i.imgur.com/1PrIgIv.png)][sheetp]
[![](https://i.imgur.com/wNyBzSQ.png)][sheetp]
[![](https://i.imgur.com/1m8DbR9.png)][sheetp]
[![](https://i.imgur.com/wUswT1e.png)][sheetp]
[![](https://i.imgur.com/aLNnFvX.png)][sheetp]
[![](https://i.imgur.com/4XgBEKU.png)][sheetp]
[![](https://i.imgur.com/xdVPQrj.png)][sheetp]
[![](https://i.imgur.com/XTwp8hq.png)][sheetp]
[![](https://i.imgur.com/cXcX0Za.png)][sheetp]
[![](https://i.imgur.com/tAr885V.png)][sheetp]

<br>
<br>


[![](https://img.youtube.com/vi/E8WaFvwtphY/maxresdefault.jpg)](https://www.youtube.com/watch?v=E8WaFvwtphY)<br>
[![ORG](https://img.shields.io/badge/org-puzzlef-green?logo=Org)](https://puzzlef.github.io)
[![DOI](https://zenodo.org/badge/654985498.svg)](https://zenodo.org/badge/latestdoi/654985498)


[gist]: https://gist.github.com/wolfram77/804cc67b8eab2b357396286309e18917
[charts]: https://imgur.com/a/ApNmBGV
[sheets]: https://docs.google.com/spreadsheets/d/1mit1TuOxN15d0oUb7uWALWaQqGTJSCJknEVr8-3m5x0/edit?usp=sharing
[sheetp]: https://docs.google.com/spreadsheets/d/e/2PACX-1vRhOO3Cy6Dsv3SyVSqoJm1wG4uJ6J9O3u_AIIBtXBWDL4WgVbphyzWkxWF3eoDQcb_jre83KOfSBCub/pubhtml

---
title: Useful code

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Order that this section appears on the page.
weight: 5

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---
<section>
  <h2>HyperCells</h2>
  <p>GAP package that aids in constructing primitive cells and supercells of hyperbolic lattices based on triangle groups and quotients with normal subgroups. For finite systems, this includes the construction of appropriate periodic boundary conditions, while for infinite systems, the corresponding primitive cell and successive supercells are constructed in order to apply the supercell method for hyperbolic band theory. Additionally, the package determines maximally-symmetric Wyckoff positions and simplifies dealing with translation and point group symmetries on the hyperbolic lattice. The package also allows the definition of the graph underlying a specific model, i.e., selecting specific Wyckoff positions, nearest or next-nearest neighbors etc. Check out the file format <a href="https://hypercells.github.io/HyperCells/doc/chap7_mj.html#X8091CEE880E799B4">definitions</a> and the entire <a href="https://hypercells.github.io/HyperCells/doc/chap0_mj.html">documentation</a>.</p>
  <p> We have developed a dedicated <a href="https://www.hypercells.net/">website</a> that includes installation information as well as several detailed tutorials.</p>
  <img src="project_HyperbolicLattices.JPG" width="600" max-width: 100%>
</section>
<br>
<br>


<section>
  <h2>HyperBloch</h2>
  <p>HyperBloch is a Mathematica package that provides functions for importing and easily visualizing the clusters, supercells, and model graphs output by the HyperCells package. Additionally, it allows the user to easily define tight-binding models ontop of the model graph, by placing orbitals at vertices and defining hopping matrices on the graph edges. Finally, functions for constructing the Abelian Bloch Hamiltonian for the defined model are provided which allows studying eigenstates and eigenvalues. </p>
  <p>Check out further information on the dedicated <a href="https://www.hypercells.net/index.html">website</a> that also includes installation instructions as well as several detailed tutorials.</p>
  <img src="hypHex.PNG" width="600" max-width: 100%>
</section>
<br>
<br>

<section>
  <h2>Second Chern number</h2>
  <p>Mathematica code to compute the second Chern number of a four-dimensional (topological) band insulator, downloadable from <a   href="http://dx.doi.org/10.13140/RG.2.2.35088.12801/1" target=”_blank”>ResearchGate</a>. The code is an implementation of the algorithm discussed in M. Mochol-Grzelak, A. Dauphin, A. Celi, and M. Lewenstein, Quantum Sci. Technol. <b>4</b> 014009 (2019), DOI:<a href="https://doi.org/10.1088/2058-9565/aae93b" target=”_blank”>10.1088/2058-9565/aae93b</a> (where the algorithm's convergence is discussed too). </p>
  <p>The data plotted below correspond to $30^4$-partitioning of Hamiltonian: </p>
  <p>$$\mathcal{H}(k^\textrm{4D}) = \sum_{i=1}^4 \Gamma_i\sin k_i + \Gamma_5\left[m + \sum_{i=1}^4\cos k_i\right].$$</p>
  <img src="C2-compare.JPG" width="600" max-width: 100%>
</section>
<br>
<br>

<section>
  <h2>Patch Euler class </h2>
  <p>Mathematica code that computes the <i>patch Euler class</i> of a pair of bands on a region (the patch) with a boundary, downloadable from <a href="http://dx.doi.org/10.13140/RG.2.2.29803.69928" target=”_blank”>ResearchGate</a>. The patch Euler class is an invariant for systems with $C_2\mathcal{T}$-symmetry (and also for spinless systems with $\mathcal{PT}$-symmetry), which determines whether a pair of Dirac points are able to annihilate along a prescribed trajectory. The algorithm, as described in the supplementary material to A. Bouhon, Q.S. Wu, R.-J. Slager, H. Weng, O. V. Yazyev, and T. Bzdušek, Nat. Phys. <b>16</b>, 1137–1143 (2020), DOI:<a href="https://doi.org/10.1038/s41567-020-0967-9" target=”_blank”>10.1038/s41567-020-0967-9</a> [<a href="https://www.tomasbzdusek.com/publication/non-abelian-reciprocal-braiding-of-weyl-nodes-and-its-manifestations-in-zrte/">info</a>], corresponds to a computationally efficient way to extract the most relevant bit of information from the non-Abelian topological invariant introduced previously in Q.S. Qu, A. A. Soluyanov, and T. Bzdušek, Science <b>365</b>, 1273–1277 (2019), DOI:<a href="https://doi.org/10.1126/science.aau8740" target=”_blank”>10.1126/science.aau8740</a> [<a href="https://www.tomasbzdusek.com/publication/non-abelian-band-topology-in-noninteracting-metals/">info</a>].
  </p>
  <p>The data below plot the Euler curvature computed from first principles near two pairs of band nodes of strained $\textrm{ZrTe}$. Upon pair collision the band nodes are stable in the top scenario, and annihilate in the second scanario – even though no difference is present in the Berry phases and Chern numbers of the scenarios.
  </p>
  <img src="patch-Euler.JPG" width="400" max-width: 100%>
</section>
<br>
<br>

<section>
  <h2>Nodal link compositions</h2>
  <p> Our publications on non-Abelian band topology, first introduced in Q.S. Qu, A. A. Soluyanov, and T. Bzdušek, Science <b>365</b>, 1273–1277 (2019), DOI:<a href="https://doi.org/10.1126/science.aau8740" target=”_blank”>10.1126/science.aau8740</a> [<a href="https://www.tomasbzdusek.com/publication/non-abelian-band-topology-in-noninteracting-metals/">info</a>], were demanding on visualization of three-dimensional nodal-line compositions. This became especially true in our long overview paper of band topology in $\mathcal{PT}$-symmetric Hermitian band structures through the optics of the non-Abelian band topology, see A. Tiwari and T. Bzdušek, Phys. Rev. B <b>101</b>, 195130 (2020), DOI:<a href="https://doi.org/10.1103/PhysRevB.101.195130" target=”_blank”>10.1103/PhysRevB.101.195130</a> [<a href="https://www.tomasbzdusek.com/publication/non-abelian-topology-of-nodal-line-rings-in-pt-symmetric-systems/">info</a>]. 
  </p>
  <p> The Mathematica code that generates the plentiful illustrations in the latter paper is downloadable from <a href="http://dx.doi.org/10.13140/RG.2.2.13943.75680" target=”_blank”>ResearchGate</a>. The two images below a representative snippet.
  </p>
  <img src="NL-compositions.jpg" width="600" max-width: 100%>
</section>

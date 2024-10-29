# Logan Search

[`Logan Search`](https://logan-search.org) is a k-mer search engine for all Sequence Read Archive public accessions. Given a DNA sequence, the service replies in a few minutes in which SRA accession(s) it is likely to occur. The service also enables to recover metadata associated to target accessions, and to perform some visualizations.

In more technical depth, the search engine uses [kmindex](https://tlemane.github.io/kmindex), a k-mer based sequence search tool that uses Bloom filters. It was applied to construct an index over all genome assemblies of all of SRA, more specifically over the unitigs of [Logan](https://github.com/IndexThePlanet/Logan). This website is running the [kmviz](https://tlemane.github.io/kmviz) visualization tool.

**This repository is used as a discussion place for questions/issues from `Logan Search` users**.



 

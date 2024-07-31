---
layout: about
title: About
permalink: /
---

# MOFid
{: .no_toc }

A system for rapid identification and analysis of metal-organic frameworks.

Please cite [DOI: 10.1021/acs.cgd.9b01050](https://pubs.acs.org/doi/abs/10.1021/acs.cgd.9b01050) if you use MOFid in your work.


## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Objective

Supplement the current MOF naming conventions with a canonical, machine-readable identifier to facilitate data mining and searches. Accomplish this goal by representing MOFs according to their nodes and linkers and topology.

## Usage and Installation Instructions

There are three main ways in which you can use MOFid.
1. From your browser.
2. By compiling the MOFid source code and running it locally.
3. By using Singularity or Docker to run a pre-built image of the MOFid code locally.

### Browser-based MOFid

Visit [Web MOFid](https://snurr-group.github.io/web-mofid/) to quickly and easily run MOFid in your browser! No programming skills are required.

### Compiling from Source

See [Compiling]({{site.baseurl}}/compiling) for how to compile and run MOFid from source.

### Containerized MOFid

See [Singularity]({{site.baseurl}}/singularity) for how to run MOFid via a Singularity container.

## Background and Troubleshooting

Please read [this page](https://github.com/snurr-group/web-mofid/blob/master/README.md) for a detailed background and for important tips and tricks in troubleshooting problematic scenarios.
## Credits

This work is supported by the U.S. Department of Energy, Office of Basic Energy Sciences, Division of Chemical Sciences, Geosciences and Biosciences through the Nanoporous Materials Genome Center under award DE-FG02-17ER16362.

The MOFid command line and web tools are built on top of other open-source software projects.

* [Open Babel](https://github.com/openbabel/openbabel) cheminformatics toolkit
* [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) as a dependency for Open Babel
* [GoogleTest](https://github.com/google/googletest) C++ testing framework
* [Make](https://www.gnu.org/software/make/), [CMake](https://cmake.org/), [Node.js](https://nodejs.org/en), and [Emscripten](https://emscripten.org/) for build infrastructure
* [Systre](http://www.gavrog.org/) and [webGavrog](https://github.com/odf/webGavrog) to analyze crystal graph data and assign [RCSR topology symbols](https://rcsr.anu.edu.au/) for MOFs
* [NGL Viewer](https://github.com/nglviewer/ngl) to visualize MOF structures and components on the website
* [Kekule.js](https://partridgejiang.github.io/Kekule.js/) to draw molecule substructure queries in the SearchDB web tool

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)

[jekyll-organization]: https://github.com/jekyll

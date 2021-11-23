# Public Transit Optimization with Social Access Objectives

This repository is meant to act as a home page linking to the various programs related to the research project:

> A. Rumpf and H. Kaul. A public transit network optimization model for equitable access to social services. In _Equity and Access in Algorithms, Mechanisms, and Optimization (EAAMO’21)_, October 5–9, 2021. Association for Computing Machinery, New York, NY, doi: [10.1145/3465416.3483288](https://doi.org/10.1145/3465416.3483288).

I would not expect these programs to be of much use to anyone outside of our research group, but they are provided here for anyone interested. The sections below include links to the repositories related to this project as well as brief explanations of how they fit into the study. The READMEs of the individual repositories explain their functions in greater detail.

## Chicago Data Preprocessing

[social-transit-preprocessor](https://github.com/adam-rumpf/social-transit-preprocessor) is a Python script written to perform preprocessing on various City of Chicago and CTA data sets in order to construct the underlying network for our main case study.

## Procedural Artificial Network Generation

[social-transit-example](https://github.com/adam-rumpf/social-transit-example) is a Mathematica script written for procedurally generating artificial networks for use in testing our main solution algorithm.

## Main Solver Preprocessing

[social-transit-solver-single](https://github.com/adam-rumpf/social-transit-solver-single) is a C++ program used for conducting the preprocessing necessary to generate the input files for the main solver [social-transit-solver](https://github.com/adam-rumpf/social-transit-solver).

## Main Solver

[social-transit-solver](https://github.com/adam-rumpf/social-transit-solver) is a C++ implementation of our main hybrid tabu search/simulated annealing solution algorithm.

## Computational Trial Driver

[social-transit-trial-driver](https://github.com/adam-rumpf/social-transit-trial-driver) is a C++ program that calls the main solver [social-transit-solver](https://github.com/adam-rumpf/social-transit-solver) repeatedly to solve a set of problem instances.

## Miscellaneous

[social-transit-network-analysis](https://github.com/adam-rumpf/social-transit-network-analysis) is a collection of miscellaneous C++, Python, and Mathematica utilities used to perform various result analysis and file editing tasks throughout the computational trial process.

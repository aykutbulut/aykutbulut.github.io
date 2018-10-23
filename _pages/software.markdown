---
layout: page
title: Software
permalink: /software/
---

On this page you will find scripts/codes/software I have written.

COLA (Conic Optimization with Linear Approximations) is a solver written in C++
that solves second order conic optimization (SOCO) problems. It uses outer
approximation to solve SOCO problems. It depends on COIN-OR’s solver interface
OSI and lp solver CLP.

DietCOLA (Discrete COLA) is a solver for discrete SOCO problems. For now it
uses a naive branch and bound method. It depends on COIN-OR’s ingenious search
library ALPS (Abstract Library for Parallel Search). By default it uses COLA to
solve continuous relaxation problems, Mosek can also be used for this through
interface provided. Nowadays I spent most of my time to improve DietCOLA, more
improvements will be coming, stay tuned.

Check GiMPy (Graph Methods in Python) and GrUMPy (Graphics for Understanding
Mathematical Programming) packages for Python. GiMPy contains a graph class and
associated methods for visualizing various graph-based algorithms. GrUMPy is
build on top of GiMPy and used for visualizing branch and bound tree of integer
linear programs. The purpose is to build and visualize the tree on the fly when
the solver is working, for observing/analyzing the process. These packages are
available through Python Package Index (PyPI) and Coin-OR website. You can
install them using easy install.

Check BLiMPy (Basic List Implementation in Python) package. It is a linked list
implementation. We developed this to use in GiMPy.

Turing machine simulator is a C++ class that simulates a Turing Machine. Turing
machine class has a very simple API that provides writing Turing machine
programmes. It is based on the Turing machine simulator written in Python. The
python version can be found in
http://code.activestate.com/recipes/252486-turing-machine-simulator.

Unlimited Register Machine (URM) is a model of computation, like Turing
Machine. Computability theorists like to work with URMs, at least Nigel Cutland
does. I took a reading class based on Cutland’s “Computability: An Introduction
to Recursive Function Theory” book. I wrote a Python class that simulates URMs,
for fun. I implemented some of the example programs/exercises from the
book. You can get URM simulator and examples from here. Have fun with URM
programming!

Salbp is a python class that solves Simple Assembly Line Balancing Problems
(SALBP) of type 2. It depends on some other open-source softwares. For further
information about the problem or how to use Salbp you can check my qualifier
report which is about SALBP type 2. Slbp-1.0 misses solution retrivial
methods. You can use Pulp methods for this.

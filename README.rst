Placement
=========
This python package intends to be a collection of VNF
placement algorithms running on top of networkx package. Each placement
algorithm is contained within the mapper module as a class inheriting from the
AbstractMapper. Every AbstractMapper has an associated AbstractChecker to
ensure that received graphs contain the required information.


Related paper
=============

.. image:: img/volatite-problem-figure.png
    :width: 200px
        :align: center
            :height: 100px
                :alt: fog robotics

This fork of the placement module contains the heuristic
solution presented in the paper

"Delay and Reliability-Constrained
VNF Placement on Mobile and Volatile
5G Infrastructure"

Article DOI: 10.1109/TMC.2021.3055426

The file
`constructive_mapper_from_fractional.py`
contains the class `ConstructiveMapperFromFractional`,
which solves the Virtual Network Embedding (VNE)
problem in Fog scenarios accounting for:
 * battery constraints;
 * mobility;
 * radio coverage;
 * delay constraints; and
 * resources contraints (network & computational).

The proposed heuristic is based on a bin packing
variant that, and it finds a fractional optimal solution.
The experiments derived are located in **TODO**.


Citation
========
Consider referencing our work as follows if you
are using it for personal/comercial purposes:


```tex
TODO
```

MLA: **TODO**





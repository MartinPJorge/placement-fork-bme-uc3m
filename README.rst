Placement
=========
This python package intends to be a collection of VNF
placement algorithms running on top of networkx package. Each placement
algorithm is contained within the mapper module as a class inheriting from the
AbstractMapper. Every AbstractMapper has an associated AbstractChecker to
ensure that received graphs contain the required information.


Related paper
=============

"Delay and Reliability-Constrained VNF Placement on Mobile and Volatile 5G Infrastructure"
###############

.. image:: https://github.com/MartinPJorge/placement-fork-bme-uc3m/blob/bme-uc3m/img/volatile-problem-figure.png

This fork of the placement module contains the heuristic
solution presented in the paper

"Delay and Reliability-Constrained
VNF Placement on Mobile and Volatile
5G Infrastructure" DOI: 10.1109/TMC.2021.3055426

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


**BibTeX**

.. code-block:: latex

   @article{nemeth2021delay,
      title={Delay and reliability-constrained VNF placement on mobile and volatile 5G infrastructure}, 
      author={Balázs {Németh} and Nuria {Molner} and Jorge {Martín-Pérez} and Carlos J. {Bernardos} and Antonio {de la Oliva}, Balázs {Sonkoly}},
      year={2021},
      journal={IEEE Transactions on Mobile Computing}
      archivePrefix={TODO},
      primaryClass={TODO},
      doi={10.1109/TMC.2021.3055426}
      % Unkwnown details prior to publication - TODO
      % volume={65},
      % number={2}, 
      % pages={464-474},
   }



**Plain text**

.. code-block:: txt
    
    Balázs Németh, Nuria Molner, Jorge Martín-Pérez, Carlos J. Bernardos, Antonio de la Oliva, Balázs Sonkoly,
    "Delay and reliability-constrained VNF placement on mobile and volatile 5G infrastructure,"
    in IEEE Transactions on Mobile Computing, vol. ??, no. ?, pp. ???-???, ?? 2021, doi: 10.1109/TMC.2021.3055426.



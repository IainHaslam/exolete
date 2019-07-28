# Exolete lattice Boltzmann scripts

A tiny repository to share lattice Boltzmann code from exolete.com

This code has been shared via web pages since just before Linus started writing
git. As people continue to find it useful, I'm updating the method of
sharing so that it is slightly easier to find, pickup and play with.

This code is concise - they are simple numerical simulations, completely
omitting even functional decomposition let alone unit tests.

Explanations of the code are available at:

 * [exolete.com/lbm](https://exolete.com/lbm) for the matlab scripts `lbm.m`,
   `lbmval.m` and `lbm3d.m`
 * [exolete.com/parallel_lbm](https://exolete.com/parallel_lbm) for
   `lbm_mpi.cpp`, a vintage C++ with MPI approach to distributed-memory
   parallelisation of lattice Boltzmann. Although the style of the code is
   slightly outdated, the *method* is still clearly presented. Read it on this
   [single-sheet of paper](http://exolete.com/images/lbm_mpi.pdf)

This specific implementation of the numerical method is described in a
fairly leisurely, but necessarily numerical, fashion at 
[iainhaslam.com](https://iainhaslam.com/monplace/lbm-theory)

![Reactive flow modelled with lattice Boltzmann](lbmflow.gif)

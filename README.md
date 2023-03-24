# PyNN implementation of Brette-et-al 2007
The main goal is to provide a series of benchmark simulations of networks of spiking neurons, and demonstrate how these are implemented in the different simulators overviewed in the paper.



PyNN model of networks of spiking neurons: a review of tools and strategies [Brette et al. 2007](https://senselab.med.yale.edu/ModelDB/ShowModel?model=83319&file=/destexhe_benchmarks/PyNN/0.4/VAbenchmark_graphs.py#tabs-1)

The results should look like this


![alt text](https://github.com/doorkn-b/PyNN-Brette-et-al.-2007/blob/main/PyNN/VAbenchmark_COBA.png)


![alt text](https://github.com/doorkn-b/PyNN-Brette-et-al.-2007/blob/main/PyNN/VAbenchmark_CUBA.png)


We review different aspects of the simulation of spiking neural
networks.  We start by reviewing the different types of simulation
strategies and algorithms that are currently implemented.  We next
review the precision of those simulation strategies, in particular
in cases where plasticity depends on the exact timing of the
spikes.  We overview different simulators and simulation
environments presently available (restricted to those freely
available, open source and documented).  For each simulation tool,
its advantages and pitfalls are reviewed, with an aim to allow the
reader to identify which simulator is appropriate for a given task.
Finally, we provide a series of benchmark simulations of different
types of networks of spiking neurons, including Hodgkin-Huxley
type, integrate-and-fire models, interacting with current-based or
conductance-based synapses, using clock-driven or event-driven
integration strategies.  The same set of models are implemented on
the different simulators, and the codes are made available.  The
ultimate goal of this review is to provide a resource to facilitate
identifying the appropriate integration strategy and simulation
tool to use for a given modeling problem related to spiking neural
networks.

The codes included in this package refer to the benchmark
simulations described above.  The main goal is to provide a series
of benchmark simulations of networks of spiking neurons, and how
these are implemented in the different simulators overviewed in the
paper.  See details in the enclosed file Appendix2.pdf, which
describes these different benchmarks.  Some of these benchmarks
were based on the Vogels-Abbott model (Vogels TP and Abbott LF. 
Signal propagation and logic gating in networks of
integrate-and-fire neurons. J. Neurosci. 25: 10786-10795, 2005).  


The submitted version of the paper is available at this URL:

http://arxiv.org/abs/q-bio.NC/0611089 

These files updated October 15th, 2008 to include Brian and PyNN.

20110805 Ted Carnevale corrected the synaptic time constants for the 
NEURON implemetation of the coba model (see NEURON/coba/cobacell.hoc).

This repository holds the code for PyNN.

# PyNN-Brette-et-al.-2007
PyNN model of networks of spiking neurons: a review of tools and strategies [Brette et al. 2007](https://senselab.med.yale.edu/ModelDB/ShowModel?model=83319&file=/destexhe_benchmarks/PyNN/0.4/VAbenchmark_graphs.py#tabs-1)

The main goal is to provide a series of benchmark simulations of networks of spiking neurons, and demonstrate how these are implemented in the different simulators overviewed in the paper.

The results should look like this


![alt text](https://github.com/doorkn-b/PyNN-Brette-et-al.-2007/blob/main/PyNN/VAbenchmark_COBA.png)


![alt text](https://github.com/doorkn-b/PyNN-Brette-et-al.-2007/blob/main/PyNN/VAbenchmark_CUBA.png)


This package provides a series of codes that simulate networks of spiking neurons (excitatory and inhibitory, integrate-and-fire or Hodgkin-Huxley type, current-based or conductance-based synapses; some of them are event-based). The same networks are implemented in different simulators (NEURON, GENESIS, NEST, NCS, CSIM, XPP, SPLIT, MVAspike; there is also a couple of implementations in SciLab and C++). The codes included in this package are benchmark simulations; see the associated review paper (Brette et al. 2007). The main goal is to provide a series of benchmark simulations of networks of spiking neurons, and demonstrate how these are implemented in the different simulators overviewed in the paper. See also details in the enclosed file Appendix2.pdf, which describes these different benchmarks. Some of these benchmarks were based on the Vogels-Abbott model (Vogels TP and Abbott LF 2005).

This repository holds the code for PyNN.

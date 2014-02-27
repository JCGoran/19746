Synaptic Integration in a CA1 Pyramidal Cell
--------------------------------------------

This model investigates signal integration in the dendritic tree
of a hippocampal CA1 pyramidal cell when different combinations
of active channels are present in the tree.  The model is the
basis of the results presented in the paper:

Bruce P. Graham, Pattern recognition in a compartmental model of
a CA1 pyramidal neuron, Network: Computation in Neural Systems
12: 473-492, 2001.

The model allows the user to specify the number of synapses that
are randomly distributed across the portion of the apical dendritic
tree that is in stratum radiatum (default 200 synapses).  The total
synaptic conductance and the relative proportions of AMPA and NMDA
response at a single synapse can also be specified. 

Running the model gives the voltage response at the soma as the
result of synaptic events at all of the synapses.  These events
are either synchronous, or randomly spread in time according to
the "temporal jitter" interval.

Various combinations of active channels can be added to the
dendritic tree via menu options.  The default configuration adds
all the available channels to the tree in the proportions used
in the paper.  Details of other combinations and exactly how the
channels are distributed across the tree (non-uniform) are given
in the paper.

Main HOC file: run_CA1.hoc

CA1 neuron: CA1_Major.nrn (kindly supplied by Guy Major)

Note: In the "Excitatory Synapses" window, any changes to
the excitatory synapse parameters (such as their number) are only
registered after clicking on "Update synapses".

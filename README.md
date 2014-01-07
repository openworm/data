data
====

Data repository

AVBCircuit.hd5 = a hdf5 data base with all the neurons on the AVB Locomotion circuit.
Format:

Presynaptic Neuron = string(5), e.g. AVBL, MDL08
Postsynaptic Neuron or Muscle = string(5), e.g. VB01, MVL24
Connections = Int32, e.g. 1, 2, 3 ... -1, -2, -3 whereas the number represents the number of synaptic or gap junction connections and the sign (+/-) is whether the connection is excitatory (+) or inhibitory


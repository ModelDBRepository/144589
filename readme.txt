This is the readme for the model associated with the paper:

Berzhanskaya J, Chernyy N, Gluckman BJ, Schiff SJ, Ascoli GA (2013)
Modulation of hippocampal rhythms by subthreshold electric fields and
network topology. J Comput Neurosci 34(3):369-389

This is the code that the paper authors used.

This NEURON model simulates OPb network made of 20 Pyramidal, Oriens
and Basket cells (60 total).  Biophysically realistic Pyramidal cells
have full 3D morphological structure, while Oriens and Basket cells
have simplfied compartmental structure.  Synaptic weight distribution
on Pyramidal cells is modeled after Li and Ascoli (2006, 2008).
Experimental data on the external electric field effects at the single
cell level are collected using control circuits described in Gluckman
et al. (1996, 2001). External electric field application is simulated
after C. McIntyre and M. Robertson.

Usage instructions:
-------------------

Either auto-launch from ModelDB or download, extract the archive and
compile the mod files with nrnivmodl (unix/linux) or mknrndll (pc or
mac). (The file auto-launch will start is HipNetStart.hoc).  If
running by hand use "nrngui mosinit.hoc" (unix/linux) or double
clicking mosinit.hoc (mswin) or dragging and dropping the mosinit.hoc
file onto the nrngui icon (mac os x).

Once the simulation has started three actions are required to run the
network:

1. Select the network (Click the netwOPb button)
2. Set up electric field (Click the Uniform Field button)
3. Choose initial current injection (recommended 0.23-0.26 nA) (type
0.23 into the "Int Stim Amp (nA)" field in the "Internal Current
Clamp" window)

Current version runs in Neuron 7

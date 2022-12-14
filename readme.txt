This is the readme for the model associated with the paper:

Rudolph M, Destexhe A (2005) An extended analytic expression for the
membrane potential distribution of conductance-based synaptic
noise. Neural Comput 17:2301-15

Abstract:

Synaptically generated subthreshold membrane potential (Vm)
fluctuations can be characterized within the framework of stochastic
calculus. It is possible to obtain analytic expressions for the
steady-state Vm distribution, even in the case of conductance-based
synaptic currents. However, as we show here, the analytic expressions
obtained may substantially deviate from numerical solutions if the
stochastic membrane equations are solved exclusively based on
expectation values of differentials of the stochastic variables, hence
neglecting the spectral properties of the underlying stochastic
processes. We suggest a simple solution that corrects these
deviations, leading to extended analytic expressions of the Vm
distribution valid for a parameter regime that covers several orders
of magnitude around physiologically realistic values. These extended
expressions should enable finer characterization of the stochasticity
of synaptic currents by analyzing experimentally recorded Vm
distributions and may be applicable to other classes of stochastic
processes as well.

To run the demo, simply auto-launch from ModelDB, or unzip this file,
compile the mod file mechanism and execute the file "demo.hoc".

Changelog
---------
2022-12: Fix 9.0.0 Upcoming error: new_seed used as both variable and function in file Gfluct.mod 
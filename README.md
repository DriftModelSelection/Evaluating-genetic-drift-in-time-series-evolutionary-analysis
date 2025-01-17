Evaluating-genetic-drift-in-time-series-evolutionary-analysis
=============================================================

Code used in Nene, N.R., Mustonen,V., Illingworth, C.J.R. Evaluating genetic drift in time-series evolutionary analysis.(http://www.sciencedirect.com/science/article/pii/S0022519317304332).


InferenceCode folder
-------------------
Forward-backward/predict-update HMM algorithm for drift model parameter estimation (N or sigma) through likelihood maximization and posterior calculation. Executable: DMS .Required external C libraries: gsl (see makefile) 

RunMatPower folder
------------------
Routines for generating matrix powers either using Open_BLAS or MKL (see respective makefiles). Pre-computed matrices for Wright-Fisher propagation are available in InferenceCode/MatPow.

WFprop folder
-----------------------------------------------------------------------
Routines for generating allele frequency time-series with a Wright-Fisher propagation model, from an initial set of genomes with linkage disequilibrium generated by the FastSimCoal coalescence model.

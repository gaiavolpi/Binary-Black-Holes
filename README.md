# Merging Binary Black Holes from Wolf-Rayet - Black Hole progenitors

> Laboratory of Computational Physics (MOD.B) group project

> Authors: Puggioni Dario, Salvador Alberto, Saran Gattorno Giancarlo, Volpi Gaia

## Project descriptions

X-ray binaries containing a black hole and a massive star are among the most promising observational candidates for binary black holes (BBHs) progenitors.
The primary objective of this project is to identify the key parameters that determine whether a black hole - Wolf-Rayet star system will evolve into a BBH system that eventually merges via emission of gravitational waves within a Hubble time.

To achieve this, we work with the outputs of the population synthesis code SEVN (Stellar EVolution for N-body). We preprocess the initial dataset using Dask, an optimal solution to enable Python code to scale across multiple multi-core machines. The parallelization of the computing process is performed on a cluster of virtual machines provided by the cloud service CloudVeneto.

We implemented a Random Forest algorithm for the binary classification task, after implementing different techniques to solve the problem of working with an unbalanced dataset. 

Detailed procedures and results are reported in *Final_Proj.ipynb*.

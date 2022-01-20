# photoacid-fitting

The model and fitting code are available in the iPynb notebook in this repository.


The code was developed using a Windows Subsystem For Linux environment. The performance of the parallel processing part of the differential evolution algorithm may depend on the operating system; for example, it does not work on Windows. For Windows users it might be necessary to remove the "workers" arguments from the sp.optimize.differential_evolution calls.

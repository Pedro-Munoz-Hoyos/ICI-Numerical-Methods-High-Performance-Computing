# ICI-Numerical-Methods-High-Performance-Computing
Related code from the course in Numerical Methods and High-Performance Computing attended during the M.Sc. in Computational Fluid Dynamics at Cranfield University. The numerical engines solve the one-dimensional linear advection equation using two different initial conditions, namely *F0* and *F1*, to address the numerical dissipation and dispersion of five numerical schemes, namely the *FTCS*, *First-order Upwind*, *Lax-Friedrichs*, *Lax-Wendroff*, and *Fifth-order WENO*. The parallelization of the sequential code was performed using OpenMPI, and the simulation parameters, ranging from the domain extension to the Courant number, are introduced via an "Input.dat" file.

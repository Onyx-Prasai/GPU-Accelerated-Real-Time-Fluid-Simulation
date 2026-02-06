# GPU-Accelerated-Real-Time-Fluid-Simulation-
GPU Accelerated Real Time Fluid Simulation using Smoothed Particle Hydrodynamics (SPH)
- - - -
This project focuses on the development of a high performance, real time fluid simulation system utilizing Smoothed Particle Hydrodynamics (SPH) accelerated via GPGPU programming. Traditional CPU based fluid solvers often face bottlenecks when handling the massive computational load required for realistic interaction, particularly the O(n^2) complexity of neighbor searching. To overcome these limitations, this study leverages OpenGL Compute Shaders to parallelize the Navier Stokes equations, offloading physics calculations including density, pressure, and viscosity directly to the GPU. Central to the system’s efficiency is a Spatial Hash Grid optimization, which reduces the search complexity to O(n) by partitioning 3D space into localized cells. Developed in C++ and OpenGL 4.6, the resulting application provides a robust framework for interactive virtual environments, enabling users to manipulate fluid properties and observe dynamic collisions in real time.



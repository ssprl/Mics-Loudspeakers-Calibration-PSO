# Joint Calibration and Synchronization of Two Arrays of Microphones and Loudspeakers using Particle Swarm Optimization

## Overview
MATLAB code for the published manuscript titled "Joint Calibration and Synchronization of Two Arrays of Microphones and Loudspeakers using Particle Swarm Optimization". Link: https://ieeexplore.ieee.org/abstract/document/9566708.

> **Abstract:** This work presents a methodology for the joint calibration and synchronization of two arrays of microphones and loudspeakers. The problem is modeled as estimation of the rigid motion of one array with respect to the other, as well as estimation of the synchronization mismatch between the two. The proposed method uses dedicated signals emitted by the loudspeakers of the two arrays to compute a set of time of arrival (TOA) estimates. Through a simple transformation, estimated TOAs are converted into a set of linearly independent time difference of arrival (TDOA) measurements, which are modeled by a system of nonlinear equations in the unknown parameters of interest. A maximum likelihood estimate is then given as the solution to a nonlinear weighted least squares (NWLS) problem, which is optimized applying a parallelizable variant of Particle Swarm Optimization (PSO). In this paper, we also derive the Cramer-Rao lower bound (CRLB), and benchmark it against the proposed method in a series of Monte Carlo (MC) simulations. Results show that the proposed method attains high-performance comparable to the CRLB.

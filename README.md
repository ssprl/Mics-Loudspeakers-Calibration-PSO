# Joint Calibration and Synchronization of Two Arrays of Microphones and Loudspeakers using Particle Swarm Optimization

## Overview
MATLAB code for the published manuscript titled "Joint Calibration and Synchronization of Two Arrays of Microphones and Loudspeakers using Particle Swarm Optimization". Link: https://ieeexplore.ieee.org/abstract/document/9566708.

> **Abstract:** This work presents a methodology for the joint calibration and synchronization of two arrays of microphones and loudspeakers. The problem is modeled as estimation of the rigid motion of one array with respect to the other, as well as estimation of the synchronization mismatch between the two. The proposed method uses dedicated signals emitted by the loudspeakers of the two arrays to compute a set of time of arrival (TOA) estimates. Through a simple transformation, estimated TOAs are converted into a set of linearly independent time difference of arrival (TDOA) measurements, which are modeled by a system of nonlinear equations in the unknown parameters of interest. A maximum likelihood estimate is then given as the solution to a nonlinear weighted least squares (NWLS) problem, which is optimized applying a parallelizable variant of Particle Swarm Optimization (PSO). In this paper, we also derive the Cramer-Rao lower bound (CRLB), and benchmark it against the proposed method in a series of Monte Carlo (MC) simulations. Results show that the proposed method attains high-performance comparable to the CRLB.

## License and Citation
The codes are licensed under open-source MIT license.

For any utilization of the code content of this repository, the following needs to be cited by the user:

A. Kovalyov, K. Patel and I. Panahi, "Joint Calibration and Synchronization of Two Arrays of Microphones and Loudspeakers Using Particle Swarm Optimization," in IEEE Open Journal of Signal Processing, vol. 2, pp. 535-544, 2021, doi: 10.1109/OJSP.2021.3118574.

## Disclaimer
- This work was supported by the National Institute on Deafness and Other Communication Disorders (NIDCD) of the National Institutes of Health (NIH) under Award 5R01DC015430-05. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.
- The information and materials contained in this website is a presentation of the documented research work carried out by the faculty, students and personnel at the University of Texas at Dallas (UTD). This website including its content is available for public access with the understanding that UTD and the authorized faculty and students contributing to this website make no warranties, either expressed or implied, concerning the completeness, reliability, or suitability of the presented materials for any kind of applications. Neither UTD nor any contributor to this website and its content shall be held liable to any party for any use or misuse of the information and materials contained in this website in any form or shape. Nor does the UTD warrant that the use of this website information is free of any claims of copyright infringement. This website does not endorse any commercial providers or their products. UTD and faculty managing this website reserve the right to remove, update, alter, or take down any and all posted materials on this website at any time without notice.

# UniMoVib
A unified interface for molecular harmonic vibrational frequency calculations. It was initially written in Fortran 77 during 2014 and 2015, but its ancient predecessor has been started since 2009. After being rewritten in Fortran 90 in the spring of 2017, UniMoVib has been released as a stand-alone program.

## Latest Version
Version 1.1.0 (Dec/31/2017).

1. Raman intensities (Gaussian-fchk and UniMoVib data files only).
2. Interface to [LocalModes](https://github.com/zorkzou/OpenLocalModes) for the local mode analysis.
3. The conversion factor from Bohr to Angstrom has been updated.

## Features

1. Calculate harmonic vibrational frequencies and (optional) I.R. & Raman intensities from Hessian, coordinates, and other related data generated by quantum chemistry programs or by the user manually. Nearly 30 quantum chemistry programs have been supported.
2. Analyze point group of geometry and irreducible representations of normal modes in full symmetry.
3. Thermochemistry calculation uses the point group in full symmetry, and the results are printed in Gaussian-style.
4. Save a Molden file for animation of normal modes.
5. Set up isotopic masses, temperature, pressure, scale factor and/or experimental frequencies, and so on.
6. Can be used as a third party module for frequency and thermochemistry calculations in a quantum chemistry program.
7. Interface to [LocalModes](https://github.com/zorkzou/OpenLocalModes) for the local mode analysis (e.g. force constants of chemical bonds, bond angles, and so on).

### To be done:

1. Construct Hessian matrix from force constants of redundant or 3N-L non-redundant internal coordinates.
2. An interface between UniMoVib and the quantum chemistry program [BDF](http://182.92.69.169:7226/).

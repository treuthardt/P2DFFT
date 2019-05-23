***
# Overview
_P2DFFT_ has simplified the user input and depending on the number of cores available, runs significantly faster than the older serial version, _2DFFT_. Further enhancements include:
* Allowing direct input of FITS images
* Optionally outputting inverse Fourier transform FITS images
* Ability to generate idealized logarithmic spiral test images of a specified size that have 1 to 6 arms with pitch angles of -75 degrees to 75 degrees
* Ability to output Fourier amplitude versus inner radius and pitch angle versus inner radius for each Fourier component (m = 0 to m = 6)
* Ability to calculate the Fourier amplitude weighted mean pitch angle across m = 1 to m = 6 versus inner radius
* Ability to calcualte overall Fourier spectrum over all annuli

* * *
# Citation
If you publish results using _P2DFFT_, please cite the following paper:

[Mutlu-Pakdil, B., Seigar, M. S., Hewitt, I. B., Treuthardt, P., Berrier, J. C., & Koval, L. E., _The Illustris Simulation: Supermassive Black Hole - Galaxy Connection Beyond the Bulge_, MNRAS, 474, 2594 (2018)](https://doi.org/10.1093/mnras/stx2935).

_2DFFT_ can be found [here](http://www.d.umn.edu/~msseigar/2DFFT/2DFFT.tar.gz).  If you publish results using this code, please cite the following paper:

[Davis, B. L., Berrier, J. C., Shields, D. W, et al., _Measurement of Galactic Logarithmic Spiral Arm Pitch Angle Using Two-Dimensional Fast Fourier Transform Decomposition_, ApJS, 199: 33 (2012)](http://iopscience.iop.org/0067-0049/199/2/33/).

* * *
# Available Versions

[p2dfft-5.2.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-5.2.tgz) [![DOI](https://zenodo.org/badge/86847725.svg)](https://zenodo.org/badge/latestdoi/86847725)
(Version 5.2 - Major updates and bug fixes and add Zooniverse support and new pitch angle determination algorithm)

[p2dfft-4.4.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-4.4.tgz) (Rebase the code to Ubuntu 16.04 LTS and add options to spiral.c to set arm sweep and luminosity change)

[p2dfft-4.2.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-4.2.tgz) (Fix missing makefile and CHANGES files in V4.1 and add -a option to avg.py)

[p2dfft-4.1.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-4.1.tgz) (Minor bug fixes when using the -n [nautical mile] option on the avg.py tool)

[p2dfft-4.0.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-4.0.tgz) (Major update to switch to using the Harvard FFTW3 libraries for performance and better licensing terms.  Also further updates to avg.py output plotting program, bug fixes, additional documentation, and more usuability enhancements)

[p2dfft-3.5.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-3.5.tgz) (Major updates to avg.py output plotting program, bug fixes, and usuability enhancements)

[p2dfft-3.3.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-3.2.tgz) (Updated instructions, add support for reentrant flag in CFITSIO libraries, and correct error in handling ASCII FITS files)

[p2dfft-3.2.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-3.2.tgz) (Eliminated compatibility issue between C++11 and GCC versions older than 4.9)

[p2dfft-3.1.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-3.1.tgz)

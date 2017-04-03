# Overview
_P2DFFT_ has simplified the user input and depending on the number of cores available, runs significantly faster than the older serial version, _2DFFT_. Further enhancements include:
 * Allowing direct input of FITS images
 * Optionally outputting inverse Fourier transform FITS images
 * Ability to generate idealized logarithmic spiral test images of a specified size that have 1 to 6 arms with pitch angles of -75 degrees to 75 degrees
 * Ability to output Fourier amplitude versus inner radius and pitch angle versus inner radius for each Fourier component (m = 0 to m = 6)
 * Ability to calculate the Fourier amplitude weighted mean pitch angle across m = 1 to m = 6 versus inner radius

_P2DFFT_ is in the process of being published and is therefore considered proprietary at the moment. We are willing to share the code in exchange for co-authorship. If you are interested in using this new code, please contact Patrick Treuthardt or Marc Seigar.

_2DFFT_ can be found here.  If you publish results using this code, please cite the following paper:

Davis et al. 2012, Measurement of Galactic Logarithmic Spiral Arm Pitch Angle Using Two-Dimensional Fast Fourier Transform Decomposition, ApJS 199: 33 (2012, ApJS).

# Available Versions
[p2dfft-3.1.tgz](https://github.com/treuthardt/P2DFFT/blob/master/p2dfft-3.1.tgz)

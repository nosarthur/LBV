# LBV

Background removal for MRI phase data by solving the Laplacian boundary value problem. 

More details about the algorithm can be found in the publication: 

[Zhou et al. NMR in Biomed 27 (3), 312-319, 2014](http://onlinelibrary.wiley.com/doi/10.1002/nbm.3064/abstract)


## Files

* LBV.m - Matlab wrapper
* MGv6.cpp - source code
* mexMGv6.cpp - source code for mex file 
* mexMGv6.mexa64 - mex file for Mac
* mexMGv6.mexw64 - mex file for Windows

## Notes

* Linux users need to compile mexMGv6.cpp to get the corresponding mex file.
* MGv6.cpp gives rise to a command-line tool



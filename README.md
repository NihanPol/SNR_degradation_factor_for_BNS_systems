# On the detectability of eccentric binary pulsars, Bagchi, Lorimer, Wolfe, 2013, MNRAS

This repository holds the Fortran code written and developed by Bagchi, et al. in their analysis on the degradation factor for pulsars in binary orbits ([link to paper](http://adsabs.harvard.edu/abs/2013MNRAS.432.1303B)). The original host for the code on the WVU webpage is not available, and hence the code has been moved here with permission from the authors. This code is publicly available for use contingent on appropriate credit and citation to the paper above.

The instructions on using the Fortran code are provided in the file "instructions.txt". 

In addition to the code, we also provide a few example parameter files. These parameter files are used to define the survey parameters for the survey being used to detect a binary neutron star system of given orbital characteristics. The given parameter files were used in the merger rate analysis **Future prospects for ground-based gravitational wave detectors --- The Galactic double neutron star merger rate revisited** by **Pol, McLaughlin, and Lorimer** and can be used to calculate the degradation factors used in their dosurvey.py PsrPopPy source code (see the github repo for that paper [here](https://github.com/NihanPol/2018-DNS-merger-rate)). Note that $T_{\rm obs}$, the integration time, will change based on the survey being used.

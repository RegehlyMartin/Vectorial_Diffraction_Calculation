# Python Jupyter Scripts for Numerical Calculation of Vectorial Diffraction
See the submitted paper "Split-Aperture Xolography - Linear volumetric photoactivation with short axial dimension and low out of focus excitation." for details of the implementation.

We outcoupled three different scripts for simplified computation of 1D axial PSF lineouts, 2D lateral (XY) focal plane and 2D axial (YZ) PSF images. In the implementation, the focus is on comprehensibility and compactness and not on the fastest possible runtime.  Since the calculation of images takes more time compared to 1D lineouts, we have also provided the results of the examples in the form of *.npy files, which can be loaded into the scripts without having to perform the computation.

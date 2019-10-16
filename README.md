#### CODE for MEASURING SEISMIC TRAVEL-TIME CHANGES with the WAVELET METHOD
#### Contact: Shujuan Mao (maos@mit.edu) and Aurélien Mordret (aurelien.mordret@univ-grenoble-alpes.fr)

This package contains codes and test data for measuring seismic travel-time shifts in the time-frequency domain using the wavelet cross-spectrum analysis. 

MATLAB R2018a (or higher version) and the MATLAB WAVELET TOOLBOX are needed to run the codes.

Contents in this package:

—— My_Wxspectrum_TO.m: 
    The core function to calculate dt in the time-frequency domain by wavelet cross-spectrum analysis.

—— main_TO.m: 
    An example of using My_Wxspectrum_TO.m on synthetic data. Plots come with one click.

—— synthetic_dvov_0.05percent.mat: 
    Two synthetic waveforms for testing the codes.
    The synthetic seismograms are generated using velocity models by a homogeneous background superimposed with random heterogeneities. The perturbation between the current and reference velocity models is a 0.05% homogeneous dv/v throughout the medium. (If interested, see Section 3.1 in the following reference for more details.)

Reference: S.Mao, A.Mordret, M.Campillo, H.Fang, R.D.van der Hilst, (2019), On the Measurement of Seismic Travel-Time Changes in the Time-Frequency Domain with Wavelet Cross-Spectrum Analysis, GJI, In Review.


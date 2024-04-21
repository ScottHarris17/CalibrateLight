# CalibrateLight
Matlab App for computing photoisomerizations from measurements of light intensity and spectra.

Requirements:
<ul>
<li>MATLAB 2020+</li>
<li>Power Meter</li>
<li>Photospectrometer</li>
</ul>

The power meter and photospectrometer should be used before running this app to record data about the light power (a single number in watts) and spectrum (usually this is one vector of wavelengths and one vector of the relative power reading at each wavelength), respectively. Then, use this app to calculate the photoisomerization rate of M-cones, S-cones, and rods. Note, these calculations are based on absorption spectra for rodent opsins, but the code can be easily modified to calculate photoisomerization rates for human photoreceptors, or any other species.

To run, enter <code>>>CalibrateLight</code> in the MATLAB command line and follow the instructions presented in the app.


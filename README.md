# ETNP19_ADCP
ADCP Data from the Eastern Tropical North Pacific Cruise on the Kilo Moana in October 2019

Requires packages "oce" "ncdf4" and "tidyverse", "Viridis", "lubridate" packages.
Also requires rstudio.
I have successfully run this in a linux environment but it should work anywhere.

ExamineADCPAmp.Rmd is an rstudio notebook file that parses and plots adcp signal return data, which can be useful for tracking movement of zooplankton and nekton in the water.

We do not know precisely what these are though we found that the ADCP signal did not appear to associate with more zooplankton caught in a plankton net.
300 
I found that I had the highest resolution with the os38nb.nc data file. This is a narow band adcp. os38bb and wh3300 are the broadband and workhorse adcps which you may explore by changing out the value saved to ncdfName in the r markdown script.

CheckADCPAmp.Rmd was a file that I used to look at ADCP on the cruise itself and has been left here for legacy reasons.

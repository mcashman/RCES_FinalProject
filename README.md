## RCES 2018 Final Project

## A sea level curve for Barbados over MIS 5
### Miranda Cashman

### Introduction/Intellectual Merit:
Future sea level predictions depend on accurate and high resolution reconstructions of sea level during past warm periods.  To reconstruct sea level in the past, we identify, sample, and measure 'sea level indicators' - geologic evidence of where past sea levels were compared to modern.  Fossil corals are widely used sea level indicators becacuse they are easily dateable with isotopic methods.  Compiling many sea level indicator data can yield a sea level curve, which aims to reconstruct sea level in the past thorugh time, which can ultimately constrain future sea level model outputs.  

### Proposed Project:
I propose to construct a sea level curve for Barbados from existing coral data compiled in the Hibbert et al., 2016 repository of global coral sea level indicators.  I choose to only focus on Barbados during MIS 5 for the scope of this project.  MIS 5 is a period show to have a lot of suborbital frequency, and by resolving sea level over this interval, we may better understand ice sheet stability and response to warming climate through an interglacial-glacial transition.  While my analysis is not replicating one specific paper's analysis, I will be performing an analysis similar to many that have been previously published at different sites worldwide.  Thompson and Goldstein, for example, created a Barbados sea level curve in 2005, but my analysis will add more coral data than their study used, and will seek to understand how changing different assumptions about past sea level influences the sea level curve reconstruction.  I chose Barbados as my location of focus because when I have processed my own samples from Barbados I can perform the same analysis on my own data.

I will follow methods similar to those described in Thompson and Goldstein 2005, O'Leary et al., 2013, and Cutler et al., 2003:
- Load the data via pandas from csv format
- Clean the data set to be more easily manipulated in python
- Filter the data to relavent data points (i.e. Barbados, and corals dating to MIS 5)
- Apply an open system correction to data points that indicated diagenetic alteration (this yields a more accurate age date)
- Calculate uplift rate (this parameter can change under different assumptions, a few of which I plan to test - i.e. create different sea level curves under different tectonic uplift rates)
- Fit a curve to the data points preferentially fitting the highest elevation points and considering data 'holes' to be representative of sea level lowstands or stillstands 
- Propogate error through the calculations and combinations
- Vary parameters and assumptions and (maybe) vary the filtering restrictions to see how the sea level curves change with different inputs

### Deliverable:
- Maps of Barbados showing sample location
- Figure showing the variability in different parameters based on how constrained/unconstrained our assumptions about the past are.
- Multiple sea level curves that display how changing our assumptions on uplift and how we filter data can influence the output of sea level reconstructions and thereby predictions.  

### Data:
Hibbert et al., 2016
https://www.sciencedirect.com/science/article/pii/S0277379116301305?via%3Dihub

Database:
https://ars.els-cdn.com/content/image/1-s2.0-S0277379116301305-mmc2.xlsx

### Binder link
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mcashman/RCES_FinalProject/master)


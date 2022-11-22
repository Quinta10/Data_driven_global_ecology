# Data_driven_global_ecology

Using outputs of two PSD resolving marine carbon algorithms 
we are trying to uncover latent drivers to phytoplankton ecology.
The data Consists of a rahge of sources: WOA18, PSD_carbon_backscattering (Kostadinov et al., 2016), PSD_carbon_absorption (Roy at al., 2013)
Iron is Hu

total carbon in the particles ranging from 0.5 to 50 um. pico = 0.5-2 um, nano = 2-20 um, micro = 20-50 um TK, ROY, Satellite data are downloaded for 2003-2007, resampled from 0.083(12 km) to 1 degree, using NN Nitrate, Phosphate and silicate are from WOA
Winds and MLD are from EraInterim
Fe: Iron from https://zenodo.org/record/6385044#.Y2hc-3bMKUk Huang Y, Tagliabue A and Cassar N (2022)Data-driven modeling of dissolved iron in the global ocean.
TK_T: Is calculated as in Kostadinov et al., 2016 All TK data is based on TK 2016, the LUTs were obtaing from Tiho in Feb 2020 before OS meeting in San Diego
ROY_T: Total carbon calculated from size distributions (xi, k, particle numbers) provided by Shovonlal Sept 2019
Both products use unified allometric coefficients described in Roy et al, 2013.
** suffix _P, _N, _M:** denotes size group as noted above satellite gridded data:
PAR: oceancolor SeaWiFS v 2020.
PIC: oceancolor SeaWiFS v 2020 (Balch 2005).
Stram: oceancolor SeaWiFS v 2020. Stramski 2000
Beh: Oregon state univ website, Behrenfeld model output
CHL: oceancolor SeaWiFS v 2020. Standard SeaWIFs
SST: oceancolor SeaWiFS v 2020. MODIS
MLD: EN 4.2 Hadley reanalysis
Wind, U10, V10, tccurl, lpcurl, vecurl:, EN 4.2 Hadley reanalysis
PO4, Si, NO3:  WOA18
Coordinates:
Month_v: column shows the # of the month
Lon: Shows pixel number in a 1 degree coordinates, corresponds to Longitudes
Lat: Shows pixel number in a 1 degree coordinates, corresponds to Latitudes

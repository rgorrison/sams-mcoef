[![DOI](https://zenodo.org/badge/450638718.svg)](https://zenodo.org/badge/latestdoi/450638718)
# South American Summer Monsoon variability in the last millennium 

This code was used in research as part of an international collaboration that builds on the proxy- and modeling-specific expertise of the co-authors to present a unique synthesis of past climate variability in tropical South America. We define the leading modes of variability of the South American Monsoon Summer System (SASM) during the last millennium from a network of oxygen-isotope proxy records and two isotope-enabled climate models. These modes are interpreted based on present-day SASM climatology and found to be emergent features of the regional boundary conditions rather than a response to external forcings or internal variability. Finally, multi-centennial shifts in the mean state during the Medieval Climate Anomaly and Little Ice Age show regionally coherent patterns of hydroclimatic change associated with upstream rainout.

The contents of this directory are part of a recently accepted publication in Climate of the Past. Please see the citation guide below.

-------------
### Files
**figscode/*:** This directory contains python code used to generate figures for the manuscipt

**SASM_MCEOF_mceofcalculation.ipynb**: This python notebook contains the code used to generate the Monte Carlo Empirical Orthogonal Function Decomposition of a multi-proxy network capturing variability of the South American Summer Monsoon. 

**SASM_ind_850_1850.csv**: First principal component time series (PC1) of the MCEOF analysis, interpeted as an index of SASM variability over the last millennium (850 -- 1850 CE).

**SACZ_ind_850_1850.csv**: Second principal component time series (PC2) of the MCEOF analysis, interpeted as an index of South Atlantic Convergence Zone variability over the last millennium (850 -- 1850 CE).

-------------
### Data availability
Oxygen isotope samples used in this analysis are available from the National Centers for Environmental Information (NCEI) Paleo Data server (https://www.ncdc.noaa.gov/paleo/) and the University of São Paolo Geosciences speleothem database. GPCP Precipitation data were obtained from NOAA NCEI at https://www.ncdc.noaa.gov/ghcn-daily-description. NOAA OLR and ERSST_V3b data are available from the NOAA/OAR/ESRL PSL, Boulder, Colorado, USA, from their website at https://psl.noaa.gov/.

--------------
### Citation

If you use the code for the MCEOF function in your work, please cite:

Orrison, Rebecca. (2022). SASM-MCEOF-v1.1.0. Zenodo. [code, data set]. https://doi.org/10.5281/zenodo.6949234

*and* 

Orrison, R., Vuille, M., Smerdon, J. E., Apaéstegui, J., Campos, J. L. P. S., Cruz, F. W., and Della Libera, M. E.: South American Monsoon variability over the last millennium in paleoclimate records and isotope-enabled climate models, Clim. Past, 18, 2045–2062, doi: 10.5194/cp-18-2045-2022



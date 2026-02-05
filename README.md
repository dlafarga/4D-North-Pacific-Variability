# Four-dimensional North Pacific variability and regional impacts from a high-resolution ocean reanalysis
This code will produce all the figures for the paper 'Four-dimensional North Pacific variability and regional impacts from a high-resolution ocean reanalysis.' Figures produced in the paper are included as PNG files. The period used for the GLORYS data is a December, January, and February average from 1994 - 2021 and can be downloaded through [the Copernicus Marine Environment Monitoring Service website](https://data.marine.copernicus.eu/product/GLOBAL_MULTIYEAR_PHY_001_030/description).

The files needed to produce the figures are:
- EOF_1.nc and EOF_2.nc: Files with the first two EOFs calculated from GLORYS.
- Winter Avg_eigenvalues_eigenvectors.csv: File with the eigenvalues and eigenvectors.
- Winter.mon.clim.nc: File with the climatology computed from GLORYS as a DJF average.

The code you will use to do all the plotting is **Plot_Figures.ipynb**, and all dependencies are outlined in the requirements.txt file. If you open this file with Google Colab please make sure to mount to drive first. 

[![DOI](https://zenodo.org/badge/1127008682.svg)](https://doi.org/10.5281/zenodo.18490047)


# Project Description

CTA_BrighteningAnalysis is an analysis of the sources filtered by Paolo Goldoni from the 4LAC Fermi-LAT Catalog. This can be useful for the AGN Population Task Force and also the AGN Flares Task Forces of the Cherenkov Telescope Array Collaboration.


## Installation
 
This package can be installed by downloading it:

```
git clone git@github.com:luanapassosreis/CTS_BrighteningAnalysis.git

```

You must change the path in __init__ and set it to this folder on your computer (CTA_BrighteningAnalysis/ folder)

>> \_\_init\_\_.ipynb << Initial imports, functions and dataframes for the 4LAC Analysis

From that point on, you can reproduce all plots/analysis, by opening the following files:

>> Fvar_sources.ipynb << F_var analysis for the sources on 4LAC Catalog

>> Plot_lightcurves_and_spectrum.ipynb << Light Curve and Spectrum Plots of a chosen range of sources from the 4LAC Catalog

>> Histogram_analys.ipynb << Histogram Analysis of the 4LAC Catalog


## Files that may help:

- Fermi LAT Light Curve Repository: https://fermi.gsfc.nasa.gov/ssc/data/access/lat/LightCurveRepository/
- LAT 10-year Source Catalog (4FGL-DR2): https://fermi.gsfc.nasa.gov/ssc/data/access/lat/10yr_catalog/
- Fermi Light Curve Repository Data Description: https://fermi.gsfc.nasa.gov/ssc/data/access/lat/LightCurveRepository/table_description.html
- Fermi Large Area Telescope Fourth Source Catalog Collaboration paper: https://arxiv.org/pdf/1902.10045.pdf
- Fvar is calculated with equation 2 from this paper: https://arxiv.org/pdf/2001.08678.pdf
- To calculate the uncertainty of Fvar, the prescription is in: https://articles.adsabs.harvard.edu/pdf/2003MNRAS.345.1271V

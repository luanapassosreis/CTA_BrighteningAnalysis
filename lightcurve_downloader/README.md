# lightcurve_downloader

Contact:
	Tarek Hassan (tarek.hassan@ciemat.es)
        
## Aim

Download all lightcurves available within the LAT lightcurve repository:

https://fermi.gsfc.nasa.gov/ssc/data/access/lat/LightCurveRepository/

---
### Dependencies

I think it only uses these dependencies:

1. astropy
2. numpy
3. json
4. urllib.request


### Download available lightcurves

You only need to execute sequentially the notebook in this folder. 

Please note I first build the "AGN Pop" catalog, combining the 4LAC catalog with Paolo Goldoni's revised list of redshifts.

You may change the cadence, min TS and index type of the lightcurves, always using the labels specified in the notebook.

I don't think it is worth investing more time for this... It takes roughly 40 min to download all lightcurves (deleting those that are empty).

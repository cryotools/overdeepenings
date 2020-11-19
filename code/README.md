![GLAMoR](https://cryo-tools.org/wp-content/uploads/2020/07/GLAMoR-LOGO-400px.png)
# Scripts

### Required data
In order to run properly, the scripts in this repository require different datasets as input.
For the glacier ice thickness estimates, we recommend using the dataset of 
[Farinotti et al. (2019)](https://doi.org/10.1038/s41561-019-0300-3)
The glacier outlines can be downloaded from the 
[Randolph Glacier Inventory, v6](https://www.glims.org/RGI/).
While theoretically, a number of DEMs are available for HMA, we recommend using the 
[ALOS World 3D - 30m (AW3D30)](https://www.eorc.jaxa.jp/ALOS/en/aw3d30/index.htm).

### Required software
Valid licences for several extensions of the ArcGIS software are needed, 
i.e. the *ArcGIS 3D Analyst*, the *ArcGIS Spatial Analyst*, and the *ArcGIS Geostatistical Analyst*.
While most of the code is written in Python, we use R for some steps as well.

### Preprocessing
Some preprocessing steps are not included in the scripts as they heavily depend on the employed
platform, folder structure, and data. However, they are very straightforward:




### Citation
You are free to use this code and the dataset in your research. 
If you do, please refer to the release you used, e.g., for v0.1:

Furian, Wilhelm (2020): An inventory of future glacial lakes 
in High Mountain Asia in shapefile format, v0.1, Zenodo, DOI: 10.5181/zenodo.3958786

[![DOI](https://zenodo.org/badge/281966062.svg)](https://zenodo.org/badge/latestdoi/281966062)

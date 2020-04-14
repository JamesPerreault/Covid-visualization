This epository contains python code for visualizing covid data.   Known issues are that the Maryland rest call for  covid data by zip code is broken.  It will be fixed once a new link is available.

Two python packages are needed.  They are:
* [PyShp](https://pypi.org/project/pyshp/)
* [Plotly](https://plot.ly/python/)

In addition the following files need to be downloaded from the US Census and exploded into the shapefiles directory:
* https://www2.census.gov/geo/tiger/GENZ2018/shp/cb_2018_us_state_5m.zip
* https://www2.census.gov/geo/tiger/GENZ2018/shp/cb_2018_us_zcta510_500k.zip

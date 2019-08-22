# pangeo-xarray-sprint
Experiment with working with overlapping swath data in xarray


# Install components
## GDAL from source

Steps to install GDAL 3 from source:
- Ensure you have the latest version of [PROJ](https://proj.org/install.html) installed (> 6.0)
- Get the latest source for [GDAL](https://gdal.org/download.html) (> 3.0)
- Go inside the extracted directory and execute the following:
```shell script
./configure
make
make install
```

Resource for bulding GDAL: https://trac.osgeo.org/gdal/wiki/BuildHints

## Rasterio from source

### Requirements
- Have the follwoing packags installed: Numpy, Cython
- Get latest from GitHub: https://github.com/mapbox/rasterio
- Install
```
python setup.py install
```

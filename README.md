# Randerson group plotting tutorial

by Baird  
4 September 2018

If you plan to run these scripts on your own machine, use the `conda-environment-file.yml` file to install all the necessary packages.  More info on this from the conda documentation:  [Creating en environment from an environment yml file](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

### Contents
#### 1. ```matplotlib``` basics
  * Summary of plotting methods
  * Creating ```Figure``` and ```Axes``` objects

#### 2. Panel plots
  * Creating equally-sized panel plots
  * Creating nonuniformly-sized panel plots (gridspec)
  * Axes embedded within other axes

#### 3. ```cartopy``` and maps
  * Quick intro using NetCDF file

#### 4. Polishing up plots for publication

#### 5. Plotting remote sensing (raster) data
  * MODIS (HDF) files
  * LandSat (GeoTIFF) files

### Directory structure

```
.
|—— .git
|—— .gitignore
|—— README.md
|—— conda-environment-file.yml

|—— data-files
    |—— LC08_L1GT_226057_20180815_20180815_01_RT_B2.TIF
    |—— LC08_L1GT_226057_20180815_20180815_01_RT_B3.TIF
    |—— LC08_L1GT_226057_20180815_20180815_01_RT_B4.TIF
    |—— LC08_L1GT_226057_20180815_20180815_01_RT_thumb_small.jpg
    |—— MOD13A2.A2018113.h12v08.006.2018129234917.hdf
    |—— precip.mon.mean.nc
    |—— sst.mnmean.nc
    |—— sstoi.indices

|—— figures
    |—— 3-maps-using-cartopy.pdf
    |—— 4-publication-quality-example.pdf
    |—— 5-landsat-true-color.pdf
    |—— 5-modis-with-coastlines.pdf

|—— notebook-files
    |—— 1-matplotlib-basics.ipynb
    |—— 2-panel-plots-and-embedded-axes.ipynb
    |—— 3-maps-in-cartopy.ipynb
    |—— 4-publication-quality-figures.ipynb
    |—— 5a-plotting-MODIS-data.ipynb
    |—— 5b-plotting-LandSat-data.ipynb
    |—— png-files
        |—— anatomy1.png
        |—— ax_pos_example.png
        |—— creating_figures_for_examples.ipynb
        |—— fig_map.png
        |—— grid_example_equal_size.png
        |—— gridspec_example.png
```

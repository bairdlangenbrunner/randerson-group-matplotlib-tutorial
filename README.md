# Randerson group plotting tutorial

by Baird  
21 August 2018

### Contents
#### 1. ```matplotlib``` basics
  * Creating ```Figure``` and ```Axes``` objects
  * Figure size
  * Transform keyword
  * Interactive vs. static figures

#### 2. Panel plots
  * Creating equally-sized panel plots
  * Creating nonuniformly-sized panel plots (gridspec)
  * Axes embedded within other axes

#### 3. Prettying up your plots
  * Accessible colormaps (```cmocean```, ```seaborn```)
  * Controlling font sizes

#### 4. ```cartopy``` and maps
  * quick intro using NetCDF file
  * Raster data
    * Plotting a LandSat image
    * Plotting a MODIS image

### Directory structure

```
.
|—— .git
|—— .gitignore
|—— README.md

|—— data-files
    |—— precip.mon.mean.nc
    |—— sst.mnmean.nc
    |—— LANDSAT files
    |—— MODIS files

|—— figures
    |—— panel_plot_a.png
    |—— panel_plot_b.png

|—— notebook-files
    |—— 1-matplotlib-basics.ipynb
    |—— 2-panel-plots.ipynb
    |—— 3-prettying-up-plots.ipynb
    |—— 4a-cartopy.ipynb
    |—— 4b-plotting-LandSat-data.ipynb
    |—— 4c-plotting-MODIS-data.ipynb
    |—— 5-best-practices.ipynb
```

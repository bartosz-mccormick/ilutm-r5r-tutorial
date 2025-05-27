# ILUT-M R5R Tutorial 

Tutorial for Interactions of Landuse and Transport at the Technical University of Munich

In this tutorial you will be introduced to [r5r](https://ipeagit.github.io/r5r/): an interface to the [R5](https://github.com/conveyal/r5) routing engine developed by Conveyal.
R5 allows you to do "rapid, realistic" routing on multimodal networks. It's very flexible, enabling
intermodal analyses and has the key strength of retaining the full detail of the public transport timetable.
If you're more familiar with python, you can consider using [r5py](https://github.com/r5py/r5py) instead - although it may not have all of the same functionality.

The tutorial consists of the following main steps:

1. Installing `r5r`
2. GTFS preparation
3. Building a `r5r` model
3. Preparing origin-destination data
4. Calculating and exporting a TTM


In addition to r5r, you will be exposed to several other useful R packages: [dplyr](https://dplyr.tidyverse.org/) (for working with data tables), [sf](https://r-spatial.github.io/sf/) (for working with geodata), and [tidytransit](https://github.com/r-transit/tidytransit) (for working with GTFS data). These are all very
powerful packages that can make your life a lot easier if you learn how to use them! You're encouraged 
to look into the documentation of these packages for more information.

## To Get Started

- Install R & R Studio:
  -  https://ftp.fau.de/cran/index.html
  - https://posit.co/download/rstudio-desktop/
- Download or clone this repository and open the `.Rmd` file. You can then complete the tutorial by following the steps. 
- You can also open the `.nb.html` file in a browser, it shows the output that you should get in each step

![image](https://github.com/user-attachments/assets/ffc4704c-e009-48ea-b1ee-0ea2810c73c7)

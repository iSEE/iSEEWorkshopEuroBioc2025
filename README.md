# iSEEWorkshopEuroBioc2025 <img src="man/figures/iSEE.png" align="right" width="120" />

Learn how to use the iSEE package, in a compact 2-hours workshop!

This is intended as a companion to its big sis workshop package, [iUSEiSEE](https://github.com/iSEE/iUSEiSEE).

This workshop is going to be presented at the EuroBioC2025 conference, taking place in September 2025 in Barcelona, Spain.

# Huch, what's iSEE again?

The `iSEE` package is a flexible, powerful and extensible application to explore any dataset stored in a `SummarizedExperiment` object.
In turn, any dataset that can be shaped into one or more numerical matrices ("rectangular" datasets) can easily be put into a `SummarizedExperiment` object.
This includes many types of bulk, single-cell, and spatially resolved biological data, as well as many non-biological data types. 

`iSEE` enables a multitude of panels to gain in-depth insight in your data; it does so combining interactivity and reproducibility, and provides an ideal tool for deeper dives into your data.


## How to install

To follow this workshop, first install R and RStudio, e.g. following the instructions [here](https://carpentries-incubator.github.io/bioc-intro/). 
Next, within an R session, the workshop package and all required dependencies can be installed from GitHub as follows:

```
install.packages("BiocManager")
BiocManager::install("iSEE/iSEEWorkshopEuroBioc2025", 
                     dependencies = TRUE, 
                     build_vignettes = TRUE)
```

## How to run this workshop

- Clone the [GitHub repository](https://github.com/iSEE/iSEEWorkshopEuroBioc2025) to a local folder on your computer. 
- Open the `iSEEWorkshopEuroBioc2025.Rproj` project file in RStudio.
- Navigate to the `vignettes` folder.
- Open the individual R Markdown files and execute their content live!


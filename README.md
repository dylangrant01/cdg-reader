# ncar_data_guide
A package for climate researchers to check for information on the NCAR Climate Data Guide to compare to a user netCDF file.


## Installation 
The easiest way to install the latest version of `ncar_data_guide` is using `pip':  

```
pip install ncar_data_guide
```

## Documentation 

Check out the NCAR Climate Data Guide for a wealth of information: https://climatedataguide.ucar.edu/

## Intro 

The field of climate data is diverse and expanding.

The Climate Data Guide provides concise and reliable information on the strengths and limitations of the key observational data sets, tools and methods used to evaluate Earth system models and to understand the climate system. The Guide publishes data summaries with access links, intercomparisons, and expert commentaries on the utility of climate data for addressing a wide variety of questions in climate science. The Guide has helped over a million readers from around the world gain an insider's perspective on data ranging from simple climate indices to state-of-the-art data assimilation products (e.g. reanalysis) to paleoclimate records from tree rings and corals.

This package utilizes the xarray environment to help access key information and insights from Climate Data Guide that may be valuable to understanding the key strengths and limitations of your dataset.


'ncar_data_guide' will return up to (3) results from the database relevant to your dataset.

```
   import ncar_data_guide as ndg
    
   # Use your netCDF file to search the guide for relevant information.
   ndg.check_NCAR('file.nc')

```


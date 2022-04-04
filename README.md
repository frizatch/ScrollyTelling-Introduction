# ScrollyTelling-Introduction

Geoscience workshop for exploring Landsat data via GEE with python

*Kudos to Qiusheng Wu (Twitter @giswqs) who is responsible for nearly all of this work!*

## Workshop Resources
 - Google Earth Engine (GEE) - create an account for non-commercial purposes here: [GoogleEarthEngine](https://earthengine.google.com/)
 - [Minconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda/Anaconda Navigator](https://docs.anaconda.com/anaconda/navigator/install/)
 - Landsat Data - Supplied to you on the GEE site!
 - [Jupyter Notebook](https://www.dropbox.com/s/c8ag0mbbyy2ttrd/geeandlandsat.ipynb?dl=0) - download to follow some exercises!

## Workshop Goals
By the end of this workshop, you will be able to:
- understand data from the Landsat 8 & 9 satellites
- create a python environment for geoanalysis
- use geemap to connect to Google Earth Engine for geospatial visualization and analysis

## Outline
- [Remoting Sensing](#remotesensing)
- [Landsat 8 & 9 overview](#landsat)
- [Exploring Landsat data](#streamlit)
- [What is GEE?](#gee)
- [geemap - a python package for GEE](#geemap)
- [Anaconda python](#anaconda)
- [Jupyter notebook for GEE and Landsat](#notebook)
- [Resources](#resource)

## <a name="remotesensing"></a> Remote Sensing: Geoscience with Satellites!

Remote sensing is the process of detecting and monitoring the physical characteristics of an area by measuring its reflected and emitted radiation at a distance (typically from satellite or aircraft, so it isn't just satellites). Special cameras collect remotely sensed images, which help researchers "sense" things about the Earth. You can have passive sensors which record the earth's own emittance or reflectance from the sun's radiation. Sensors can also be active, like LiDAR for example, meaning they send out their own signal and look for the reflectance.

To understand how the sensors carried on satellites and aircraft work, we need some understanding of the electromagnetic spectrum:

<p align="center">
<img src="images/Spektrum_eng_h600.png" width="800"/>
</p>

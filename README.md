# Data-Science-Portfolio 
A portfolio summarizing the data science and ML projects conducted for academic research and learning.

All the projects are listed in two categories: academic projects for scientific research and fun projects for self learning.


##  Academic Projects
### 1.  Developing image Processing pipeline to detect energetic explosions / anomalies from the Long Wavelength Array (LWA) radio telescope image datasets using Python.
	
Developed a Python based image processing pipeline to process large amounts (160 terabytes) of images from the 2 LWA stations in New Mexico to detect energetic events occuring in our universe. The pipeline utilized ***data collection, data cleaning, image processing (background subtraction, threshold based detection, tracking of objects), classification of candidates, anomaly detection using images and time series analysis, and visualization of interesting new source candidates.***
	
**The [Imager-tools](https://github.com/savinshynu/Imager-tools) repository contains the python scripts used in the statistical analysis and visualization of the data. The [Jupyter notebook](https://github.com/savinshynu/Imager-tools/blob/master/Orville_image_processing_pipeline.ipynb) shows how the tools in the Imager-tools repository is used to process images and identify interesting new sources in the datasets.** 
The analysis of data from this pipeline has resulted in 3 scientific journal publications.
 
 1. Detection of a Low-frequency Cosmic Radio Transient Using Two LWA Stations [link](https://iopscience.iop.org/article/10.3847/1538-4357/ab07c6)
 2. Testing the Radiation Pattern of Meteor Radio Afterglow [link](https://doi.org/10.1029/2019JA026922)
 3. Broadband Imaging to Study the Spectral Distribution of Meteor Radio Afterglows [link](https://doi.org/10.1029/2021JA029296)

### 2.  Comissioning the data processing pipeline of COSMIC, a new innovative compute cluster developed at the Very Large Array telescope hunting intelligent alien civilizations.

  Developed various *tools to test and commission the digital signal processing software of COSMIC, which can process 3 TB/s of continuously streaming time series data* from 27 radio telescopes. This included testing and validating the ***raw voltage time series data and the image data from the observing system. Developed software to calibrate the data and verify different signal processing components such as beamformer (coherent addition of time series data from multiple antennas), imager and technosignature (alien signals) detection through spectrogram analysis.***
  
 **The [VLA_COSMIC](https://github.com/savinshynu/VLA_COSMIC) repository contains the Python tools developed to commission the COSMIC system.**
 [] (The [Jupyter notebook] shows how to detect alien candidates using time series and spectrogram analysis of the data from COSMIC system.)

[] (### 3.  Principal component analysis to study correlations in the meteor data)

### 3. Studying Fast Radio Bursts (FRBs: millisecond time scale explosions) using the time series data from the LWA radio telescope.

Developed a python pipeline which can process the time series data from LWA telsecope to study FRBs. This pipeline includes ***convertion of time series data to spectrograms (using Fourier transforms), data cleaning for bad radio interference, signal reconstruction in spectrogram space and visualization of interesting candidates.***

***The [LWA_FRB](https://github.com/savinshynu/LWA_FRB) repository contains tools developed to detect FRBs with the LWA data.***

### 4. Searching for intended signal transmission from One Web satellite constellation.
The One Web satellite constellation (similar to Space X constellation) consists of nearly 630 satellites oribitting in the low earth orbit (LEO). These satellites are designated to communicate with Earth basec receivers between 10.7-12.7 GHz. In this project, I utilized the observations of One Webb satellties with the 13 m Onsala Space telescope in Sweden to gain an understanding of how often these satellties communications affect ground based radio telescope observations of astrophysical sources. 

The [SERES](https://github.com/savinshynu/SERES) repository contains the statistical and visualization tools used understand the effect of satellite transmissions on radio telescope observations. 


### 5. Studying radio emission from meteors using the data from OVRO-LWA telescope in California
Implemented tools and methodologies to detect radio emission from meteors using the raw telescope data product (cross correlated time series data) from the OVRO-LWA telescope. The [MRA-OVRO](https://github.com/savinshynu/MRA-OVRO) repository contains the tools developed to process the data and identify meteors producing radio emissions. ***This included data cleaning, Fourier transforms to convert raw data to images, image processing, anomaly detection, time series analysis, Fourier domain enhancements and deconvolution techniques.***

[] (### 7. Searching for alien technosignatures using the time series data from LWA telescope.)

## Learning Projects - (in progress)
[](### 1.  Explorative data analysis of insurance data with pandas and linear regression with Scikit Learn.)
[](### 2. Explorative data analysis with R and SQL)
# Data-Science-Portfolio 
A portfolio summarizing the data science and ML projects conducted for academic research and learning.

All the projects are listed in two categories: academic projects for scientific research and personal projects for self learning.


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
 
### 3. Studying Fast Radio Bursts (FRBs: millisecond time scale explosions) using the time series data from the LWA radio telescope.

Developed a python pipeline which can process the time series data from LWA telsecope to study FRBs. This pipeline includes ***convertion of time series data to spectrograms (using Fourier transforms), data cleaning for bad radio interference, signal reconstruction in spectrogram space and visualization of interesting candidates.***

***The [LWA_FRB](https://github.com/savinshynu/LWA_FRB) repository contains tools developed to detect FRBs with the LWA data.***

### 4. Searching for intended signal transmission from One Web satellite constellation.
The One Web satellite constellation (similar to Space X constellation) consists of nearly 630 satellites oribitting in the low earth orbit (LEO). These satellites are designated to communicate with Earth basec receivers between 10.7-12.7 GHz. In this project, I utilized the observations of One Webb satellties with the 13 m Onsala Space telescope in Sweden to gain an understanding of how often these satellties communications affect ground based radio telescope observations of astrophysical sources. 

The ***[SERES](https://github.com/savinshynu/SERES)*** repository contains the statistical and visualization tools used understand the effect of satellite transmissions on radio telescope observations. 

### 5. Studying radio emission from meteors using the data from OVRO-LWA telescope in California
Implemented tools and methodologies to detect radio emission from meteors using the raw telescope data product (cross correlated time series data) from the OVRO-LWA telescope. The ***[MRA-OVRO](https://github.com/savinshynu/MRA-OVRO)*** repository contains the tools developed to process the data and identify meteors producing radio emissions. ***This included data cleaning, Fourier transforms to convert raw data to images, image processing, anomaly detection, time series analysis, Fourier domain enhancements and deconvolution techniques.***

### 6. Using SQL (Structured Query Language) to interact with the VLA COSMIC database.
The [SQL-COSMICDB-Git](https://github.com/savinshynu/SQL-COSMICDB-Git) repository contains sripts and jupyter notebooks to interact with the VLA COSMIC database using Python. This ***[Jupyter notebook](https://github.com/savinshynu/SQL-COSMICDB-Git/blob/master/cosmic_sql_query-git.ipynb)*** shows how SQL commands can be used to submit simple and complicated queries, collect and analyze data from the database.
## Personal Projects
### 1. Exploratory data analysis and predictive modelling of insurance claim data using multivariate linear/polynomial regression.
This ***[Jupyter notebook](https://github.com/savinshynu/DS-Projects/blob/master/EDA_visualization_multivariate_regression.ipynb)*** basically try to develop a model which can predict the insurance cost of clients in the United states. The dataset for this project has been taken from Kaggle. This notebook utilizes ***pandas to conduct exploratory data analysis, matplotlib for plotting the data and scikit-learn for mutilvariate linear/polynomial regression modelling.***

### 2. Deep learning to classify medical images of patients with tensorflow.
This ***[Jupyter notebook](https://github.com/savinshynu/DS-Projects/blob/master/Medical-Image-Classification-Deeplearning.ipynb)*** demonstrates the development of a deep learning model, multi layer perceptron (MLP) model which can classify the medical images of different body parts taken using MRI, CT and Xray scans (collected from Kaggle). ***The pandas, numpy and matplotlib is used for exploratory data analysis and visualization. Tensorflow and scikit-learn is utilized for building the deep learning model which can classify the images with 99 % accuracy.***

### 3. Exploratory data analysis, visualization and predictive modeling of Walmart Sales in R.
This ***[R Markdown notebook](https://github.com/savinshynu/DS-Projects/blob/master/DataAnalysis-with-R/EDA-linear-regression.pdf)*** shows how multivariate linear regression can be used to predict the Walmart Sales as a function of regional, time and economic factors in the R language. The R libraries *rio* is used for importing data, *dplyr and tidyr* is used for data manipulation, *ggplot and plotly* are used for data visualization. Principal component analysis and correlation calculations are also calculated to understand the correlation between features in the datasets.
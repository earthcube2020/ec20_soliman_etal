
# Processing digital elevation data for deep learning models using Keras Spatial<br/>
**Aiman Soliman and Jeffrey Terstriep**

Most state-of-the-art deep learning systems have their roots in computer vision, which force the remote sensing community to develop ad-hoc procedures for applying deep learning methods in the analysis of remote sensing data. In this Juypuiter notebook, we present Keras Spatial (https://pypi.org/project/keras-spatial), a new python package for pre-processing and augmenting geospatial data for deep learning models. Keras Spatial is composed of loosely-coupled components, which allow users to pre-process geospatial raster data on-the-fly before ingesting them into neural networks. The advantage of using Keras Spatial over more traditional Ad-hoc pipelines are (1) allowing scientists and developers to work in projected coordinates rather than pixels and (2) controlling the sample space and hence avoiding issues such as bias and class imbalance during training. We will demonstrate Keras Spatial using the case study of processing digital elevation data for a segmentation model. We will also demonstrate advanced data pre-processing features of this package, such as accessing remote data sources directly, easy integration of multiple datasets using automatic reprojection and resampling, and decoupling training samples dimensions from the geographic extent to open the door for prediction across different scales.

----

This Jupyter notebook demonstrates the use of Keras Spatial package to prepare geospatial data for Tensorflow models. We illustrate the different functionality of Keras Spatial using the case study of pre-processing Digital Elevation data.

To lunch an interactive notebook on binder please click here 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/a2soliman/ec20/master?filepath=ks-preprocess-dem.ipynb)

A static version is also available [here](https://github.com/earthcube2020/ec20_soliman_etal/blob/master/ks-preprocess-dem.ipynb)       

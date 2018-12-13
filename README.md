Author:
Lu Bai, bai.lu2@husky.neu.edu
Shuwan Zhang, zhang.shuwa@husky.neu.edu

Salt Identification and Segmentation

Abstract

The identification of salt bodies plays an important role in geological research and exploration of oil and gas, but now professionals still need to manually distinguish seismic images. This project aims to build an effective model through deep learning to quickly identify areas of the salt bodies in seismic images. Our dataset is a set of images chosen at various locations chosen at random by using reflection seismology in the subsurface. After data exploratory, we implemented U-Net and CNN models using Keras to process and capture features of our train data. After comparing the prediction results of the two models, we select one of the excellent ones to process the test dataset and obtain the salt bodies with higher accuracy. In this paper, we will elaborate how seismic images can be used in recognizing salt bodies step by step. The results obtained in this research is showing the best accuracy of our U-Net model is about 0.9221 and the best accuracy of our CNN model is about 0.8507. So, we choose the U-Net model to predict our dataset data.

Operating Environment

Running Python in Jupyter Notebook Python is an interpreted high-level programming language for general-purpose programming. To install Python and get tutorials, pelase visit their OFFICIAL SITE Or you can also browse the tutorial site _Lynda.com, they have many fabulous crouses on the site.

Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. It is the most popular tool to run Python on. To have jupyter notebook up and run, please install the IDE Anaconda first. Or refer to https://github.com/nikbearbrown/INFO_7390/blob/master/Week_1/NBB_Intro_Python.ipynb

Before running the code, please install "tensorflow_base", "keras","tqdm","tensorflow" module through pip. You can simple do it by typping "pip install "tensorflow_base","pip install keras","pip install tqdm", "pip install tensorflow" in the Anaconda Prompt, or maybe using the Environments in the Anaconda navigator.

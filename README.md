# Udacity_Capstone_Dog_Breed
Udacity Capstone utilizing Convolutional Neural Networks predicting dog, their breed, and humans


## Project Overview

Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!

## Table of Content

dogImages.zip -download from:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip

Ifw.zip -download from:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip

DogVGG16Data.npz -download from:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz

DogResnet50Data.npz -download from:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz

dog_app.ipynb

report.html

osloopera2x2.jpg

mercar2x2.jpg

## Installations

1. (Optional) __If you plan to install TensorFlow with GPU support on your local machine__, follow [the guide](https://www.tensorflow.org/install/) to install the necessary NVIDIA software on your system.  If you are using an EC2 GPU instance, you can skip this step.

2. (Optional) **If you are running the project on your local machine (and not using AWS)**, create (and activate) a new environment.

	- __Linux__ (to install with __GPU support__, change `requirements/dog-linux.yml` to `requirements/dog-linux-gpu.yml`): 
	```
	conda env create -f requirements/dog-linux.yml
	source activate dog-project
	```  
	- __Mac__ (to install with __GPU support__, change `requirements/dog-mac.yml` to `requirements/dog-mac-gpu.yml`): 
	```
	conda env create -f requirements/dog-mac.yml
	source activate dog-project
	```  
	**NOTE:** Some Mac users may need to install a different version of OpenCV
	```
	conda install --channel https://conda.anaconda.org/menpo opencv3
	```
	- __Windows__ (to install with __GPU support__, change `requirements/dog-windows.yml` to `requirements/dog-windows-gpu.yml`):  
	```
	conda env create -f requirements/dog-windows.yml
	activate dog-project
	```
3. (Optional) **If you are running the project on your local machine (and not using AWS)** and Step 6 throws errors, try this __alternative__ step to create your environment.

	- __Linux__ or __Mac__ (to install with __GPU support__, change `requirements/requirements.txt` to `requirements/requirements-gpu.txt`): 
	```
	conda create --name dog-project python=3.5
	source activate dog-project
	pip install -r requirements/requirements.txt
	```
	**NOTE:** Some Mac users may need to install a different version of OpenCV
	```
	conda install --channel https://conda.anaconda.org/menpo opencv3
	```
	- __Windows__ (to install with __GPU support__, change `requirements/requirements.txt` to `requirements/requirements-gpu.txt`):  
	```
	conda create --name dog-project python=3.5
	activate dog-project
	pip install -r requirements/requirements.txt
	```
4. (Optional) **If you are using AWS**, install Tensorflow.
```
sudo python3 -m pip install -r requirements/requirements-gpu.txt
```
5. Switch [Keras backend](https://keras.io/backend/) to TensorFlow.
	- __Linux__ or __Mac__: 
		```
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
		```
	- __Windows__: 
		```
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
		```
6. (Optional) **If you are running the project on your local machine (and not using AWS)**, create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `dog-project` environment. 
```
python -m ipykernel install --user --name dog-project --display-name "dog-project"
```

## Project Motivation


Capstone was build to show case my abilities as far as real world data science goes.


## File Descriptions


**dogImages.zip** -contains .jpg files of dog images only

**Ifw.zip** -contains .jpg files of human facial image only

**DogVGG16Data.npz** -contains VGG16 dog train, validation, test to make a bottleneck for cnn models

**DogResnet50Data.npz** -contains ResNet50 dog train, validation, test to make a bottleneck for cnn models

**dog_app.ipynb** -contains code of cnn classifications

**report.html** -is an html of dog_app.ipynb

**osloopera2x2.jpg** -.jpg image of Oslo's Operahouse

**mercar2x2.jpg** -.jpg image of sprorts car


## Results

are show cased in my blog:


## Conclusion


## Acknowledgements

Udacity Team for all I have been taught 


## Licence
I authorize any none malicious use of this code.


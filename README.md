# Udacity Deep Learning Nanodegree program projects

### Projects

* [Predicting Bike-Sharing Patterns](https://github.com/Pavelko007/udacity-deep-learning-ND-projects/tree/master/project-bikesharing): Implement a neural network in NumPy to predict bike rentals.
* [Dog Breed Classifier](https://github.com/Pavelko007/udacity-deep-learning-ND-projects/tree/master/project-dog-classification): Build a convolutional neural network with PyTorch to classify any image (even an image of a face) as a specific dog breed.
* [TV Script Generation](https://github.com/Pavelko007/udacity-deep-learning-ND-projects/tree/master/project-tv-script-generation): Train a recurrent neural network to generate scripts in the style of dialogue from Seinfeld.
* [Face Generation](https://github.com/Pavelko007/udacity-deep-learning-ND-projects/tree/master/project-face-generation): Use a DCGAN on the CelebA dataset to generate images of new and realistic human faces.
* [Sagemaker](https://github.com/Pavelko007/udacity-deep-learning-ND-projects/tree/master/project-sagemaker): Build and deploy a neural network which predicts the sentiment of a user-provided moview review and use your deployed model through a simple web app.

---

# Dependencies


## 1. Create and Activate the Environment

For Windows users, these following commands need to be executed from the **Anaconda prompt** as opposed to a Windows terminal window. For Mac, a normal terminal window will work. 

1. Create (and activate) a new environment, named `deep-learning` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n deep-learning python=3.6
	source activate deep-learning
	```
	- __Windows__: 
	```
	conda create --name deep-learning python=3.6
	activate deep-learning
	```
	
2. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```

3. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

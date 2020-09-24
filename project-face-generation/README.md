# Face Generation

I built a pair of multi-layer neural networks and make them compete against each other in order to generate new, realistic faces.
After training them on a set of celebrity faces I tried to generate new ones with my generator model.

## Dataset
Project is using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train adversarial networks. 
You can download this data [by clicking here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip).
This is a zip file that you'll need to extract in the home directory of this notebook for further loading and processing. After extracting the data, you should be left with a directory of data `processed_celeba_small/`

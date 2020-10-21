# DCGAN implementation in PyTorch

I would like to sincerely thank the author of DCGAN tutorial for using their open-sourced source code in PyTorch. The code has been *fully* borrowed from the author's code. The commands to mount the Google Drive and change the directory path have been added. Example dataset has also been added- 70 MNIST training images. 

The DCGAN code was written by Nathan Inkawhich (https://github.com/inkawhich)


### Procedure: 
 Clone the repository and save it in your Google Drive. You can shift the python notebook to Colab Notebooks folder.   
 
### Data Preprocessing: 
Download preferred dataset MNIST from http://yann.lecun.com/exdb/mnist/ , celebrity dataset or any dataset from kaggle and store it in data--> celeba--> img_align_celeba folder
  
 You can also use the example dataset provided in the repository. Example dataset has been added with 70 MNIST training images. 

### Training 
Run all the cells present in the notebook for the DCGAN to train.

### Experiment analysis 

Once you have trained the model, you can see the loss curve in the notebook. Based on the loss curve different hyperparameters can be experimented with. The fake images are displayed in the notebook itself for qualitative analysis.
  
  
  ## Reference citation: 
```
DCGAN tutorial: https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html
```
```
DCGAN paper: Radford, Alec, Luke Metz, and Soumith Chintala. "Unsupervised representation learning with deep convolutional generative adversarial networks." arXiv preprint arXiv:1511.06434 (2015).
```

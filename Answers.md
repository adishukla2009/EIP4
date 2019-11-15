**1. Convolution**    
Convolution is way to traverse the image and output is generated on the basis of element multiplication of the kernel and the dataset. An anology which can be used is a duster traversing the blackboard.
  
**2. Filters/Kernels**  
Every image is basically made up of basic features (i.e. an image is made up of freatures like edges, gradients) and it's the responsibility of kernel to extract these features. A kernel is therefore also called feature extractor.  
  
**3. Epochs**  
An Epoch is termed as the traversal of whole dataset once. In our code we have used 10 Epochs meaning the dataset of 60000 images was used 10 times for the purpose of training our neural network.  
  
**4. 1X1 Convolution**  
This is a method of traversal of an image where in the X and Y dimension of the output remain same as the input. It is more like a same version of the image just every element multiplied with the same number. It is basically used for Z-depth reduction.
  
**5. 3X3 Convolution**  
This is a method of traversal of an image where in the X and Y dimension of the output are decreased by 2. Also being the most popular with the GPUs it is considered as the best practice for X/Y dimensionality reduction.
  
**6. Feature Maps**  
A kernel or feature extractor extracts all the similar features and creates a collection of these features. This collection is called a feature map or a channel.
  
**7. Activation Function**  
Consider a function Y=F(X) X being the input and Y output. Now the job of the function F() is to give an output of 1 or 0 ( ON or OFF). This function F() which decides whether the output is ON or OFF is called as an activation function.

**8 Receptive Field**  
Receptive field is the field of vision of a layer in the network, it can also be understood as what portion of the original image or previous layer could be seen by a respective layer. 


# Image-Identifier
Built a logistic regression classifier to recognize cats.
Incorporated Neural Network mindset, deep learning.



#### Built the general architecture of a learning algorithm, including:

Initializing parameters

Calculating the cost function and its gradient

Using an optimization algorithm (gradient descent)

Gathered all three functions above into a main model function, in the right order.

#### About the dataset:

- a training set of m_train images labeled as cat (y=1) or non-cat (y=0)

- a test set of m_test images labeled as cat or non-cat

- each image is of shape (num_px, num_px, 3) where 3 is for the 3 channels (RGB). Thus, each image is square (height = num_px) and (width = num_px).

To represent color images, the red, green and blue channels (RGB) must be specified for each pixel, and so the pixel value is actually a vector of three numbers ranging from 0 to 255.

<img src="https://github.com/Khushi-Mineeyar/Image-Identifier/blob/main/Screenshot%202022-07-09%20142928.png">

- Initialize the parameters of the model
- Learn the parameters for the model by minimizing the cost  
- Use the learned parameters to make predictions (on the test set)
- Analyse the results and conclude

The main steps for building a Neural Network are:

Define the model structure (such as number of input features)

Initialize the model's parameters
Loop:
- Calculate current loss (forward propagation)
- Calculate current gradient (backward propagation)
- Update parameters (gradient descent)

<img src="https://github.com/Khushi-Mineeyar/Image-Identifier/blob/main/Test_images/LogReg_kiank.png">

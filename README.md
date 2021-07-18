# Indian Currency Classification

### Image Classification of new Indian Currency Notes using Keras and TensorFlow

<br/>

A model has a life-cycle, and this very simple knowledge provides the backbone for both modeling a dataset and understanding the tf.keras API.

* The five steps in the life-cycle are as follows:

  1. Define the model
  2. Compile the model
  3. Fit the model
  4. Evaluate the model
  5. Make predictions

### Classes

* No. of Classes - 7
* Name of Classes - 10, 20, 50, 100, 200, 500, 2000 

### Dataset

* Custom Dataset
* Resizing Images to (300,300,3) in the local machine using Icecream Image Resizer
* No. of (training + validation) images - 1239
* No. of test images - 55

### Preprocessing of Data

* Resizing images to (128, 128, 3)
* Splitting data
    1. Training - 992 images
    2. Validation - 247 images
* Normalizing the images
* Shuffling the training dataset
* Interpolation - Bicubic

### Important Packages

* TensorFlow
* Keras
* Numpy
* Matplotlib

### Model Specifications

* Sequential model built from scratch
* No. of layers used - 18
* Activation Function - ReLU, Softmax
* Optimization Algorithm - Adam
* Learning Rate - 0.0001
* Loss Function - SparseCategoricalCrossentropy

### Model Architecture

<img width="318px"  height = "1032px" src="https://github.com/ParulParima/Indian-Currency-Classification/blob/main/model_architecture.png?raw=true" />

### Evaluation of Model on the Validation Dataset

* Validation:

    1. loss: 0.030041895806789398
    2. accuracy: 0.9959514141082764

### Inference Results on the Test Set

<br/>

<img width="700px"  height = "450px" src="https://github.com/ParulParima/Indian-Currency-Classification/blob/main/Outputs/Output1.png?raw=true" />
<img width="700px"  height = "96px" src="https://github.com/ParulParima/Indian-Currency-Classification/blob/main/Outputs/Output2.png?raw=true" />
<img width="700px"  height = "450px" src="https://github.com/ParulParima/Indian-Currency-Classification/blob/main/Outputs/Output3.png?raw=true" />
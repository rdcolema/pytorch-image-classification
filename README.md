# PyTorch Image Classification

Classifies an image as containing either a dog or a cat (using Kaggle's <a href="https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data">public dataset</a>), but could easily be extended to other image classification problems.

### Dependencies:
- PyTorch / Torchvision
- Numpy
- PIL
- CUDA

## Data

The data directory structure I used was:

* project
  * data
    * train
      * dogs
      * cats
    * validation
      * dogs
      * cats
    * test
      * test

## Performance
The result of the notebook in this repo produced a log loss score on Kaggle's hidden dataset of 0.04988 -- further gains can probably be achieved by creating an ensemble of classifiers using this approach. 

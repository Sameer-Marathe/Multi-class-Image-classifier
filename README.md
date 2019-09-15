# Multi-class-Image-classifier
Image classifier to predict class for image among four options

## Dataset
Please download the dataset from [here](https://tinyurl.com/y62jfglm)

As dataset is pretty large, it is recommended to use [Google Colab](https://colab.research.google.com/) for training purpose

## Dependencies

This code is implemented in [Keras](http://keras.io/) using  [Tensorflow API r1.0](https://www.tensorflow.org/api_docs/) as backend. 
You can follow the [online instructions](https://www.tensorflow.org/install/) to install Tensorflow 1.0.
Other dependencies [h5py](http://www.h5py.org/), [numpy](http://www.numpy.org/),  can be installed by
[pip](https://pypi.python.org/pypi/pip). This code has been tested with Python 3.6.

## Training 
Please train the model using ``` Train.ipynb ``` script.The model weights and the model itself are saved in drive after training. Saved model was trained using ``` 150 * 150 ```
dimension images.

## Testing 

Please run ``` predict_the_labels.ipynb ``` script to predict labels on test image folder.

Model achieved 95% train accuracy and around 90% test accuracy.


# Food Classification
Convolutional Neural Networks (CNN), a technique within the broader Deep Learning field, have been a revolutionary force in Computer Vision applications, especially in the past half-decade or so. One main use-case is that of image classification, e.g. determining whether a picture is that of a dog or cat.
<br><br><br><image src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40537-021-00444-8/MediaObjects/40537_2021_444_Fig7_HTML.png" style="width:100%"><br>
You don't have to limit yourself to a binary classifier of course; CNNs can easily scale to thousands of different classes, as seen in the well-known ImageNet dataset of 1000 classes, used to benchmark computer vision algorithm performance.
<br><br><br><image src="https://camo.githubusercontent.com/e70a0a0f78671c104dec3246b7faae906cec6728e4c6ed9056b8c3e0c1823467/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f612f61342f54656e736f72466c6f774c6f676f2e706e67">  <image src="https://camo.githubusercontent.com/d4542550828038568a6cb1c20934771c9c7504aaed4918685c0602ae0159bab2/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f632f63392f4b657261735f4c6f676f2e6a7067"><br>
In the past couple of years, these cutting edge techniques have started to become available to the broader software development community. Industrial strength packages such as [Tensorflow](https://www.tensorflow.org/) have given us the same building blocks that Google uses to write deep learning applications for embedded/mobile devices to scalable clusters in the cloud -- *Without having to handcode the GPU matrix operations, partial derivative gradients, and stochastic optimizers that make efficient applications possible.*

On top of all of this, are user-friendly APIs such as [Keras](https://keras.io/) that abstract away some of the lower level details and allow us to focus on rapidly prototyping a deep learning computation graph.

### **Project Description**

As an introductory project for myself, I have tried my hand on Binary-Image-Classification of Cats vs Dogs dataset, But for a higher understanding of Keras and image classification I chose to use a pre-trained image classifier that comes with Keras, and retrain it on a Food-101 dataset . In the dataset there are 101 types of Dishes from different cuisine. Each Dish has 1000 image of it self. `Refer the meta folder to get to know the types of Dishes`.<br>
**To get enough computational power the input classes have been reduced to 8 classes with each 1000 images** 

### Objective

The main objective of this project is to get deeper understanding of Keras and  Pre-trained Convolutional Neural Network provided by Keras and TensorFlow.

### **Approach**

- The Goal is to optimise `MobileNetv2` to its maximum potential and get as close to `Inceptionv3` as we can.
- Approach of this project is to verify the accuracy of `MobileNetv2` vs `Inceptionv3` by changing different trainable parameters of the model

### **Results**

After tuning a pre-trained Google **MobileNetv2** model, I was able to achieve about **80.18% Top-1 Accuracy** on the test set with 8 different Food Items

After tuning a pre-trained Google [**InceptionV3**](https://keras.io/applications/#inceptionv3) model, I was able to achieve about **78.23% Top-1 Accuracy** on the test set with 101 different Food Items

```
Note: The Model and Project both are not yet fully optimised and the work is in Progress. Surely open to help & Ideas !
```

## **Aknoledgement**
This is a direct implementation from keras examples.

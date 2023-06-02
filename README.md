[//]: # (# Hand Written Digit Recognition)

[//]: # ( Hand Written Digit Recognition using javascript library tensorflowjs)
 
[//]: # (## Live Demo)

[//]: # (**[https://bensonruan.com/handwritten-digit-recognition-with-tensorflow-js/]&#40;https://bensonruan.com/handwritten-digit-recognition-with-tensorflow-js/&#41;**)

[//]: # ()
[//]: # (![handwritten-recognition]&#40;https://bensonruan.com/wp-content/uploads/2019/09/handwritten-recognition-5.gif&#41;)

[//]: # ( )
[//]: # (## Installing)

[//]: # (Clone this repository to your local computer)

[//]: # (``` bash)

[//]: # (git https://github.com/bensonruan/Hand-Written-Digit-Recognition.git)

[//]: # (```)

[//]: # (Point your localhost to the cloned root directory)

[//]: # ()
[//]: # (Browse to http://localhost/index.html  )

[//]: # (## Start Predicting Hand Written Digit)

[//]: # (* Draw on the canvas with your mouse on desktop or your finger on your mobile)

[//]: # (* Click "Predict" to get result of the hand written digit prediction)

[//]: # (* Click "Clean" to start drawing again)

[//]: # (## Pre-trained model )

[//]: # (Use MNIST dataset from Keras with CNN &#40;Convolutional Neural Network&#41;)

[//]: # (```python)

[//]: # (model = keras.Sequential&#40;[)

[//]: # (    keras.layers.Conv2D&#40;32, &#40;5, 5&#41;, padding="same", input_shape=[28, 28, 1]&#41;,)

[//]: # (    keras.layers.MaxPool2D&#40;&#40;2,2&#41;&#41;,)

[//]: # (    keras.layers.Conv2D&#40;64, &#40;5, 5&#41;, padding="same"&#41;,    )

[//]: # (    keras.layers.MaxPool2D&#40;&#40;2,2&#41;&#41;,    )

[//]: # (    keras.layers.Flatten&#40;&#41;,   )

[//]: # (    keras.layers.Dense&#40;1024, activation='relu'&#41;,    )

[//]: # (    keras.layers.Dropout&#40;0.2&#41;,   )

[//]: # (    keras.layers.Dense&#40;10, activation='softmax'&#41;)

[//]: # (]&#41;)

[//]: # ()
[//]: # (model.compile&#40;optimizer='adam', loss='categorical_crossentropy', metrics=['accuracy']&#41;)

[//]: # (```)

## Library
* [jquery](https://code.jquery.com/jquery-3.3.1.min.js) - JQuery
* [tensorflowjs](https://github.com/tensorflow/tfjs) - JavaScript library for training and deploying machine learning models
* [Chart.js](https://github.com/chartjs/Chart.js) - JavaScript library for display charts

## To Start Type

```shell

python -m http.server 8080

```
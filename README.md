# Android-app-with-complex-MNIST

This mainly talks about an android app made using android Studio, that basically predicts the handwritten-digits, taken from 
the very popular MNIST Dataset.The Model has been made and trained using Tensorflow in Python and mainly comprises of a 
2D- Convolutional Network that works on these images of handwritten digits of 28x28 pixels.

The Python codes were executed, trained and the results generated with an accuracy of 98%, were stored in pb plots and ckt plot, that are later interfaced with Google android studio.
1. Execute the complex_MNIST.py code in order to train the model for 20000 iterations, and get the needed accuracy. You can play around with the learning rate and weights in order to vary or enhance the accuracy. 
2. Then, execute the freeze_path.py, and you will notice that plots with the name 'Optimized_advanced_mnist.pb' get created.
3. Set up the application project in Android studio, with the desired SDK tools and API levels. This app was made on API level 25-Android7.1.1-Nougat.
4. Create a new directory with the name 'Assets' and include the 'Optimized_advanced_mnist.pb', and add libandroid_tensorflow_inference_java.jar file in the libs directory.
5. Include the MNIST_imageset for the app, and provide the necessary dependancies for building the apk, i.e. String literals, buildToolsVersion and make changes in the UI by editing the android_main.xml file. I kept is really plain and clean. 
bult the apk, and deploy it into your emulator or transfer the apk in your phone, install the APk file, and see the results.



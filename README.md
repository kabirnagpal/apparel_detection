# Apparel Detection
The project deals with detection of apparel that the person in the image is wearing.  
Sliding window along with image pyramid were used to detect the apparel. 
The code is a modification to code available in [this](https://www.pyimagesearch.com/2020/06/22/turning-any-cnn-image-classifier-into-an-object-detector-with-keras-tensorflow-and-opencv/) blog.  
The classifier was trained using transfer learning on [Xception net](https://keras.io/api/applications/xception/).  
Apparel Dataset was used from the one given in [this](https://www.kaggle.com/trolukovich/apparel-images-dataset) link.  
The overal F1-score achieved on test data after training the Network on Google Colab was 90%.  
<img src="https://github.com/kabirnagpal/apparel_detection/blob/master/images/kabir.jpeg" width="400" height="750" />
<img src="https://github.com/kabirnagpal/apparel_detection/blob/master/images/label.jpeg" width="400" height="750" />

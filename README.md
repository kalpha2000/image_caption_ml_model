This is a machine learning project.

The goal for the model is to take an image as an input and give a sentence as output which should describe the inout image.

The following concepts have been utilised to create the project:
  1) Neural Networks
  2) Transfer Learning (using resnet50 and glove vector)
  3) RNN/LSTM's
  4) Language Modeling
 
The pipeline itslef has been mentioned in the code file attached

Prequisites:
  1) Have the following named folders in your directory :
    a) Flicker_Data - this should have the flickr8k dataset unzipped
    b) model_weights - this is the location where the model_weights will be saved after training
    c) saved - this will store the img feature vectors for the training and test data so as to not compute the same from the resnet50 model again and again, this should also have                the glove.6B.50d.txt file, you can download that from kaggle

After making all the necessory directories, you can run the code and will have an Image Captioning AI bot by the end

# P.S : run on google colab or with a gpu

There is also a web app built on the same model, which is in the image captioning folder, the model there is already trained and saved, which is used directly in the web app.
  

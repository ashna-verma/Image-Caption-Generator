# Image-Caption-Generator
- In this project, we systematically analyse a deep neural networks-based image caption generation method. With an image as the input, the method can output an English sentence describing the content in the image.
- We analyse three components of the method:
convolutional neural network (CNN), recurrent neural network (RNN) and sentence
generation. 
- Then we will be implementing the caption generator using CNN
(Convolutional Neural Network) with the help of Tensor flow module and LSTM (Long
short term memory). The image features will be extracted from Exception which is a CNN
model trained on the Fliker_8k dataset and then we feed the features into the LSTM
model which will be responsible for generating the image captions.
- For the image caption generator, we will be using the Flickr_8K dataset. The Flickr_8k_text folder
contains the file Flickr8k.token which is the main file of our dataset that contains image
names and their respective captions separated by newline.
- For the image caption generator, we will be using the Flickr_8K dataset. There are also
other big datasets like Flickr_30K and MSCOCO dataset but it can take weeks just to train
the network so we will be using a small dataset, Flickr8k. The Flickr_8k_text folder
contains the file Flickr8k.token which is the main file of our dataset that contains image
names and their respective captions separated by newline.

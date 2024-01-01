# Transfer-Learning-by-VGG16

1) We all of us know about vgg16 contains 16 layers and 138 millions parameters.
2) In this repo. I try to make model by using the trasfer Learning using the weight of imagNET datasets which contains the 15 millions of photos distributed in 1000 classes.
3) I has tried the trasfer learning in two way , The first way is feature extraction and second way is fine tunning the model.
4) In Feature extraction , Freez the all layers of VGG16 pre-tarined model except top  fullt connected layers.
5) In Fine-tunning method , train the some leyers of convolutional layers of VGG16 along with our own fully connected layers.
6) I used the adam optimizer and RMSprop during the time of compilation the model
7) Used loss is binary_crossentropy

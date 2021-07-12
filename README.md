"# facial_expression" 

1)FER dataset used which contains images of faces with 7 facial expressions namely happy,sad,angry,disgust,surprise,neutral,fear.

2)CNN used for feature extraction from the images. I created a CNN layer from scratch to train my model. I have thought of replacing the CNN layer with a VGG layer to grt better efficiencies.

3)Extracted features used to train the model and then predicted on the images from validation set.

4)Entered data can be in the form of a single image or a video where we can extract frame wise data and predict on it.

5)Finally I created a flask based app for deployement. User can upload a video or a picture in the given box for that purpose and our web app will give as an output the expression of the face.

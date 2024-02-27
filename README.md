This project was the capstone final project for MIT's Applied Data Science Program. 
The objectve was to take a data set containing 20,014 images sized (48,48,1) of peoples faces expressing emotions. The categroies of the expressed emotions are 
Happy, Sad, Surprise, Neutral. 

I performed an initial EDA on the data set, then inspected the distribution of images across the class's.
Created a specialized weight to be applied at training time to attempt to make up for some of the skew in the data set. 
Performed data augmenttation, on the data to add more robustness to the traiing phase. 

BUILT 6 Convolutional Neural Networks, 3 CNN's from scratch that had 4-5 cnn layers and then ranging dense layers. 
Then 3 Transferlearning CNN models using RESnet50, VGG16, and Efficient Net to see if highter performance could be accomplished using pretrained models as the base. 


Then As an additional network i buit and trained a siamese network that was a specialixed feature vector extractor that was designed to look at just two of the class categories of 
sad and neutral and learn the difference between the two cleasses as they werer the two hardest classes for the models to learn. 



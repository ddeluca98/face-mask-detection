# face-mask-detection
This repository contains all of the codes and the datasets (included oroginal,cropped, and augmented). 

Data_Preproecess.ipynb assigns extracts samples from the images, applies the annotations, and crops the images

AugmentationV2.ipynb applies the oversampling technique (data augmentation) and puts the augmented files into Augmented_WOM and Augmented_MIW. these images, along with the

df_train is the data frame that has the image names/label for all training images inclusing the augmented images 
df_test is the data frame that has the image name for all test images and the corssponding label. 
TrainTestData folder has all the image data train and test, (The images in Augmented_WOM and Augmented_MIW are added to this folder as well)

model.ipynb is the design and creation of the model

Model_train.ipynb trains and tests the model. 
Model_train(Optimization).ipynb trains and tests the model with optimization.

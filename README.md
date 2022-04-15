# face-mask-detection
This repository contains all of the code and datasets (included cropped and augmented). 

Data_Preproecess.ipynb assigns extracts samples from the images, applies the annotations, and crops the images

Augmentation.ipynb applies the oversampling technique (data augmentation) and puts the augmented files into Augmented_WOM and Augmented_MIW. these images, along with the
unaugmented images are put in th TrainTestData folder

model.ipynb is the design and creation of the model

Model_train.ipynb trains and tests the model. Optimization is also done in this file.

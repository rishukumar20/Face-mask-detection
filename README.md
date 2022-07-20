face mask detection
===================================

• Imported dataset from kaggle having 4000 images(224X224X3) of masked and unmasked faces with data augmentation

• Ran the test data on basic CNN model using keras layers(Conv2d,MaxPooling2D,Dense,Flatten) with an accuracy of 89%

• Implemented VGG16 models on the test data to achieve accuracy of 96% on validation dataset

• Extracted feature vector using numpy array while running the model on VGG16 and used it to run the test data

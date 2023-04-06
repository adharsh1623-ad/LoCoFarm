# LoCoFarm

### This code is used to create a convolutional neural network (CNN) model for image classification. The code begins by defining the input shape of the images, the batch size, and loading the annotations from a CSV file. The dataset is then split into train and validation sets. An instance of the ImageDataGenerator class is created to perform data augmentation on the training dataset.

### The training and validation datasets are then loaded using the flow_from_dataframe method. The CNN model architecture is then defined using the Keras Sequential API. The model is then compiled and trained using the fit method. Finally, the model is evaluated and saved.

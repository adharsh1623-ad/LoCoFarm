# LoCoFarm

## overall Python Code 

### This code is used to create a convolutional neural network (CNN) model for image classification. The code begins by defining the input shape of the images, the batch size, and loading the annotations from a CSV file. The dataset is then split into train and validation sets. An instance of the ImageDataGenerator class is created to perform data augmentation on the training dataset.

### The training and validation datasets are then loaded using the flow_from_dataframe method. The CNN model architecture is then defined using the Keras Sequential API. The model is then compiled and trained using the fit method. Finally, the model is evaluated and saved.


## App's Signin Activity

### This is the signin activity page for the user to login into the application.
In this page we have used the firebase authentication for the user to login into the application.
We have used the EditText for the user to enter the email and password for the authentication.
We have used the TextView for the user to redirect to the signup page.
We have used the Button for the user to login into the application.
We have used the ImageView for the user to view the logo of the application.
We have used the ProgressBar for the user to view the progress of the authentication.
We have used the FirebaseAuth for the user to authenticate


## App's Main Activity

This code is used to create the main activity of the application.
It contains the viewpager, tablayout and the adapter.
The viewpager is used to display the fragments in the application. 
The tablayout is used to display the titles of the fragments.
The adapter is used to add the fragments to the viewpager. 
The onCreateOptionsMenu() method is used to inflate the menu and the onOptionsItemSelected() method is used to logout the user.

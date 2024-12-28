# **Project Image Classification**


# Table Of Contents



## **Libraries used :**

* os : to interact with the operating system
* zipfile : to extract the contents of the dataset zip file
* tensorflow : Core library includes modules for model creation (keras), image data augmentation, and training.
* numpy : for numerical operations 
* matplotlib : For visualizing images using plots.


## **Packages in Detail**

tensorflow.keras.preprocessing.image
* ImageDataGenerator : Used for image augmentation 
* image.load_img and image.img_to_array : Used to preprocess and convert new images for prediction.

## **Project Work flow**

1. Download and Extrcat Dataset
2. Image Augmentation and Data Splitting
3. Load Data into Generators
4. Build CNN Model
5. Train the Model ( accuracy > 85% )
6. Predict New Images ( from upload an image)

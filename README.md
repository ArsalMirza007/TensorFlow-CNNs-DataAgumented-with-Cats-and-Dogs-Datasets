# First Model Code result
# Instructions:
Tasks performed in the provided code:

1. **Downloading and Preparing the Dataset**:
   - This section includes code to download the Cats vs Dogs dataset from a given URL and unzip it under the `/tmp` directory. It also removes non-image files from the dataset.

2. **Creating Directories for Training and Validation Sets**:
   - This section contains code to create directories for the training and validation sets, as well as subdirectories for cats and dogs within each set.

3. **Splitting Data into Training and Validation Sets**:
   - Here, the code splits the dataset into training and validation sets, ensuring that the split is random and that images with zero file length are omitted.

4. **Defining and Creating Data Generators**:
   - This section defines and creates generators for training and validation data using Keras' `ImageDataGenerator`. It specifies the target size of images as (150, 150).

5. **Defining the Convolutional Neural Network (CNN) Model**:
   - Here, the code defines a convolutional neural network (CNN) model using Keras' `Sequential` API with at least 3 convolutional layers. It also compiles the model with the appropriate loss function and optimizer.

6. **Training the CNN Model**:
   - This section trains the CNN model on the training data using the `fit` method, specifying the number of epochs.

7. **Evaluating Model Performance**:
   - After training, the code plots the training and validation accuracy and loss over each epoch to evaluate the model's performance.

8. **Downloading Training History**:
   - Finally, there's a function provided to download the training history (`history.pkl`) for further analysis.
     
# Screenshots:
![accuracy](https://github.com/ArsalMirza007/CNN-s-with-Cats-and-Dogs-Datasets/assets/121928372/dcf26805-3c7a-49ea-abb3-87a96597566e)
![loss](https://github.com/ArsalMirza007/CNN-s-with-Cats-and-Dogs-Datasets/assets/121928372/6d98c7ca-451a-4568-b358-457220109b06)

# 2nd Model Code result

# Instructions:
Tasks performed in the provided code:

**Tackle Overfitting with Data Augmentation**  
Welcome to As in the previous task, you will be using the famous cats vs dogs dataset to train a model that can classify images of dogs from images of cats. For this, you will create your own Convolutional Neural Network in Tensorflow and leverage Keras' image preprocessing utilities, more so this time around since Keras provides excellent support for augmenting image data.

**Download the dataset**  
Download the Cats vs Dogs dataset from a given URL and prepare it for training.

**Create directories for training and validation sets**  
Define and create directories for the training and validation sets, along with subdirectories for 'cats' and 'dogs' within each set.

**Splitting data into training and validation sets**  
Split the dataset into training and validation sets, ensuring randomness and excluding images with zero file length.

**Defining and creating data generators**  
Define and create generators for training and validation data using Keras' `ImageDataGenerator`, specifying augmentation parameters and normalization.

**Defining the Convolutional Neural Network (CNN) model**  
Define a CNN model using Keras' `Sequential` API with at least 3 convolutional layers, and compile the model with appropriate loss function and optimizer.

**Training the CNN model**  
Train the CNN model on the training data using the `fit` method, specifying the number of epochs for training.

**Evaluating model performance**  
Plot training and validation accuracy and loss over each epoch to evaluate model performance.

**Downloading training history**  
Provide a function to download the training history (`history.pkl`) for further analysis.

# Screenshots:
![loss](https://github.com/ArsalMirza007/CNN-s-with-Cats-and-Dogs-Datasets/assets/121928372/a64e1a05-7797-4804-8235-2d6bf465b5e2)
![accu](https://github.com/ArsalMirza007/CNN-s-with-Cats-and-Dogs-Datasets/assets/121928372/795ea11d-2960-47c9-bc56-7b7e945c7b93)

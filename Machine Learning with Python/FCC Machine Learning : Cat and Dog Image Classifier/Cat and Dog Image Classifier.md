# Cat and Dog Image Classifier

Welcome to the **Cat and Dog Image Classifier** challenge! In this project, you will build a convolutional neural network (CNN) using TensorFlow 2.0 and Keras to classify images of cats and dogs. Your goal is to achieve an accuracy of at least 63%, with extra credit for reaching 70% accuracy.

### Project Overview
In this project, you will:
- Work with a dataset of images of cats and dogs.
- Build and train a convolutional neural network (CNN) to classify these images.
- Use image data generators to preprocess and augment the data.
- Train the model and visualize its accuracy.
- Make predictions on test data.

### Requirements:
- **TensorFlow 2.0** and **Keras** to create and train the neural network.
- The dataset is divided into training, validation, and test sets:
  - **Training set**: Contains images of both cats and dogs.
  - **Validation set**: A set for evaluating the model during training.
  - **Test set**: A set for testing the final model performance.

### Instructions:

1. **Setting up the Google Colaboratory Notebook**:
   - Open the provided [Google Colaboratory link](#) and create a copy in your Google Drive or download it for local use.
   - Complete the tasks in the notebook by filling in the required code cells.
   - The notebook includes detailed instructions on each code cell, guiding you on what needs to be done.
   
2. **Dataset Structure**:
   The dataset consists of the following folder structure:
   ```
   cats_and_dogs
   ├── train:
   │   ├── cats: [cat.0.jpg, cat.1.jpg, ...]
   │   └── dogs: [dog.0.jpg, dog.1.jpg, ...]
   ├── validation:
   │   ├── cats: [cat.2000.jpg, cat.2001.jpg, ...]
   │   └── dogs: [dog.2000.jpg, dog.2001.jpg, ...]
   └── test: [1.jpg, 2.jpg, ...]
   ```

3. **Cell Instructions**:
   - **Cell 3**: Set the necessary variables and create image generators for training, validation, and test datasets. Use `ImageDataGenerator` for image decoding and rescaling.
   - **Cell 4**: Visualize five random images from the training set.
   - **Cell 5**: Use `ImageDataGenerator` with data augmentation to create more training data by applying random transformations.
   - **Cell 6**: Visualize the augmented images.
   - **Cell 7**: Build the CNN model using `Conv2D`, `MaxPooling2D`, and fully connected layers with a ReLU activation function.
   - **Cell 8**: Compile and train the model. Use `fit()` with appropriate arguments like epochs and validation data.
   - **Cell 9**: Visualize the training and validation accuracy and loss.
   - **Cell 10**: Use the trained model to make predictions on test images and visualize the results.
   - **Cell 11**: Check if your model passed the challenge or needs improvements.

4. **Additional Information**:
   - You can experiment with epochs and batch size to see how they affect the model performance, but these changes are optional.
   - Be sure to observe the test set results after running the model to evaluate its effectiveness.

### Submission:
- Once you've completed the notebook and passed the test, submit your project by sharing the link to your Google Colaboratory notebook (make sure link sharing is enabled).
- If you’re submitting a local copy, ensure to include your project in a GitHub repository and provide the link.

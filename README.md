# CIFAR-10 Image Classification using a CNN

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images across 10 classes. The goal is to train a CNN model to accurately classify images into one of the predefined classes.


# Features
1.  Dataset:
   - The CIFAR-10 dataset is used for training and testing.
   - It contains 10 classes: `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, and `truck`.

2.  Preprocessing:
   - Pixel values are normalized to the range [0, 1].
   - Training and test images are normalized separately.

3.  model Architecture:
   - Convolutional Layers:
     - Extract features using 3 convolutional layers with ReLU activation.
   - Pooling Layers:
     - Use MaxPooling to reduce spatial dimensions.
   - Fully Connected Layers:
     - Two dense layers for final classification.
   - The model outputs logits, which are converted to probabilities during evaluation.

4.  Training and Evaluation:
   - The model is trained for 10 epochs.
   - Validation is performed using the test dataset.
   - Accuracy and loss metrics are tracked and visualized.

5. **Visualization**:
   - Training and validation accuracy/loss are plotted for analysis.
   - Sample images and predictions are displayed.


   




# Visualizing Training Metrics
The script will display plots for:
- Training and validation accuracy.
- Training and validation loss.

# Predicting and Visualizing Results
- The script will randomly select test images and display predictions along with their ground truth labels.



# Example Output

Training Metrics
![Training Metrics](https://via.placeholder.com/600x300?text=Training+and+Validation+Metrics)

Sample Predictions
![Sample Predictions](https://via.placeholder.com/600x300?text=Sample+Predictions)



# References
- CIFAR-10 Dataset: https://www.cs.toronto.edu/~kriz/cifar.html
- TensorFlow Documentation: https://www.tensorflow.org/


Contributing:
Feel free to fork this repository and submit pull requests to contribute.

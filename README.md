# CIFAR-10 Image Classifier with CNN (TensorFlow/Keras)

This project builds a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset. It includes a baseline model and an improved version with Dropout layers to reduce overfitting.

## 📦 Dataset
- **CIFAR-10**: 60,000 32x32 color images in 10 classes
- 50,000 training images, 10,000 test images

## 🧠 Model Architectures

### Baseline CNN
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten → Dense(64) → Dense(10)

### CNN with Dropout
- Dropout after each Conv + Dense layer to reduce overfitting

## 📊 Results
- Achieved good test accuracy (~70–75%) with dropout model
- Performance improves with proper regularization

## 🚀 How to Run

1. Install requirements:
    ```bash
    pip install tensorflow matplotlib
    ```

2. Run the notebook
    ```

3. (Optional) Modify number of epochs, dropout rates, or architecture to experiment.

## 📈 Future Enhancements
- Add data augmentation
- Use BatchNormalization
- Try different optimizers (SGD, RMSProp)
- Add early stopping or learning rate schedules

## 🛠️ Built With
- Python
- TensorFlow / Keras
- Matplotlib

## 📄 License
This project is open-source and free to use under the MIT License.

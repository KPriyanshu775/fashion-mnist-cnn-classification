# Fashion-MNIST Image Classification Using CNN

## Project Overview

This project uses a Convolutional Neural Network (CNN) to classify fashion images into 10 different categories using the Fashion-MNIST dataset.

The model is built in Python using TensorFlow/Keras. It learns image features through convolutional and pooling layers and predicts the category of unseen fashion images.

## Dataset

- Dataset: Fashion-MNIST
- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28 pixels
- Number of classes: 10
- Image type: Grayscale

The dataset is downloaded automatically using TensorFlow/Keras.

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## CNN Architecture

The model contains:

1. Input layer (28 × 28 × 1)
2. First convolutional layer (32 filters)
3. First max-pooling layer
4. Second convolutional layer (64 filters)
5. Second max-pooling layer
6. Flatten layer
7. Dense layer (128 neurons)
8. Dropout layer (0.5)
9. Output layer (10 classes with Softmax)

## Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 90.93% |
| Test Loss | 0.2466 |
| Correct Predictions | 9,093 |
| Incorrect Predictions | 907 |

The model was evaluated on 10,000 test images.

## Project Files

- `Week5_Deep_Learning_CNN.ipynb` – Complete implementation and analysis.
- `Fashion_MNIST_CNN.keras` – Trained CNN model.
- `Fashion_MNIST_Prediction_Results.csv` – Predictions for all test images.
- `Training_Validation_Accuracy.png` – Accuracy graph.
- `Training_Validation_Loss.png` – Loss graph.
- `Confusion_Matrix.png` – Model classification performance.
- `Week5_Fashion_MNIST_CNN_Project_Report.docx` – Project report.

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook using Jupyter Notebook.
4. Run the cells sequentially.

Install dependencies:

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn jupyter
```

## Conclusion

This project demonstrates how deep learning and CNNs can be applied to image classification. The trained model achieved 90.93% test accuracy on the Fashion-MNIST dataset and was saved for future use.

This project was completed as part of the Virtual Data Science with Python Internship at Yuva Intern.

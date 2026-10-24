# lane_detection

# Road Line Detection Using CNN

## About the Project
This project uses a Convolutional Neural Network (CNN) to classify road image patches into two categories: Road Line and Background. It is developed using Python and PyTorch.

## Technologies Used
- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle Notebook

## Dataset
The project uses a road-line detection dataset containing road images and XML annotation files.

Dataset: [Kaggle Road Line Detection Dataset](https://www.kaggle.com/datasets/dataclusterlabs/lane-detection-road-line-detection-image-dataset)

## Methodology
1. Load road images and XML annotations.
2. Extract road-line bounding boxes.
3. Generate positive and negative image patches.
4. Resize images to 64 × 64 pixels.
5. Train a CNN using PyTorch.
6. Evaluate the model using classification metrics.

## Model Architecture
The CNN consists of three convolutional layers, ReLU activation, max pooling, a fully connected layer, and dropout.

The model classifies each image patch as:
- Background (0)
- Road Line (1)

## Results
- **Validation Accuracy:** 82%
- **Road Line Precision:** 0.78
- **Road Line Recall:** 0.66
- **Road Line F1-Score:** 0.71

These results are based on validation patch classification.

## How to Run
1. Open the project notebook in Kaggle.
2. Add the dataset to the notebook.
3. Run the preprocessing and data preparation cells.
4. Train the CNN model.
5. Evaluate predictions and view the results.

## Limitations
This project classifies image patches. It does not yet provide complete lane tracking or a real-time Lane Keeping Assist system.

## Future Improvements
- Increase the dataset size.
- Improve annotation quality.
- Apply data augmentation.
- Experiment with advanced CNN architectures.
- Explore lane segmentation and video-based detection.

## Author
**Labhansh Satpute**

B.Tech — Computer Science / Data Science

Interests: Machine Learning, Deep Learning, Computer Vision, and Autonomous Driving.

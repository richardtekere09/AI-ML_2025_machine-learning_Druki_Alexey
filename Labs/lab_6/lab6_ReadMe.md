# Image Segmentation using Convolutional Neural Networks (CNN)

This project implements a convolutional neural network (CNN) to perform semantic segmentation on grayscale medical images. The model is trained and evaluated using the Keras deep learning library in Google Colab.

## Objective

- Learn how to build and train convolutional neural networks for image segmentation tasks.
- Apply deep learning techniques to distinguish and segment structures in grayscale images.
- Visualize and evaluate the model’s segmentation performance.

## Dataset

- **Medical Membrane Images (ISBI 2012-like)**: Grayscale images of size 512x512 pixels.
- Dataset split:
  - **Training set**: 30 images and masks.
  - **Testing set**: 30 images and masks.
- Images represent cell membranes and require binary segmentation.

## Project Structure

The project follows these key steps:

1. **Data Loading and Preprocessing**
    - Load images and masks from Google Drive.
    - Normalize pixel values to [0,1].
    - Reshape data to fit the model input requirements.
2. **Model Construction**
    - Build a simple sequential CNN model:
        - Multiple Conv2D layers with ReLU activations.
        - Final Conv2D layer with sigmoid activation for pixel-wise prediction.
3. **Model Training**
    - Compile the model with Adam optimizer and mean squared error (MSE) loss.
    - Train the model using the training dataset.
4. **Evaluation**
    - Evaluate the model performance on the test dataset using MSE.
5. **Visualization**
    - Predict segmentation masks for test images.
    - Display the predicted masks to assess model quality visually.

## Key Libraries

- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL
- Google Colab (Drive Integration)

## How to Run

1. Install required libraries:
    ```bash
    pip install tensorflow numpy matplotlib pillow
    ```

2. Upload the dataset to Google Drive:
    - Structure:
      ```
      /My Drive/membrane/
         ├── train/
         │    ├── image/
         │    └── label/
         └── test/
              ├── image/
              └── label/
      ```

3. Run the Python script or Colab notebook:
    ```bash
    python segmentation_lab6.py
    ```

4. Outputs:
    - Training history (loss reduction per epoch).
    - Model evaluation on the test set.
    - Visualization of segmented images.

## Results

- The CNN model successfully segmented cell membranes from grayscale images.
- Mean Squared Error (MSE) evaluation metric indicated good performance.
- Visual inspection showed clear separation of structures after segmentation.

## Screenshots

📸 Example of a training image and corresponding ground truth mask  
📸 Training loss curve over epochs  
📸 Predicted segmentation mask from the test dataset

## Conclusion

Through this lab, practical skills were gained in constructing and training convolutional neural networks for semantic image segmentation using Keras. The model demonstrated the ability to highlight important structures in medical images effectively.

---



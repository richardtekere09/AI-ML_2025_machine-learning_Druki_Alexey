# Noise Reduction on Images using Autoencoders

This project implements a convolutional autoencoder to perform noise reduction (denoising) on handwritten digit images from the MNIST dataset using Keras.

## Objective

- Learn how to construct and train convolutional autoencoders.
- Apply deep learning techniques to reduce noise from images.
- Visualize and evaluate the model performance on noisy and reconstructed images.

## Dataset

- **MNIST Dataset**: A standard dataset of 28x28 grayscale images of handwritten digits (0-9).
- Noise is artificially added using Gaussian noise to simulate corrupted images.

## Project Structure

The project follows these key steps:

1. **Data Loading and Preprocessing**
    - Load MNIST dataset.
    - Normalize pixel values to [0,1].
    - Add Gaussian noise to the images.
2. **Model Construction**
    - Build a convolutional autoencoder:
        - **Encoder**: Compress input images into a lower-dimensional representation.
        - **Decoder**: Reconstruct images from the encoded representation.
3. **Model Training**
    - Compile with Adam optimizer and binary crossentropy loss.
    - Train using noisy images as input and original images as targets.
4. **Evaluation**
    - Plot training and validation accuracy and loss.
    - Evaluate the model performance on the test dataset.
5. **Visualization**
    - Display original, noisy, and reconstructed images for qualitative analysis.

## Key Libraries

- TensorFlow / Keras
- NumPy
- Matplotlib

## How to Run

1. Install required libraries:
    ```bash
    pip install tensorflow numpy matplotlib
    ```

2. Run the Jupyter Notebook or Python script:
    ```bash
    python Noise_reduction_images.py
    ```

3. Outputs:
    - Training and validation accuracy/loss graphs.
    - Side-by-side visualization of original, noisy, and reconstructed images.

## Results

- The autoencoder effectively removes noise and restores clean digits.
- The final model achieves a binary crossentropy loss of approximately **0.096** on the test dataset.
- Visual inspection confirms successful noise reduction.

## Screenshots

📸 Training graphs of accuracy and loss  
📸 Sample original, noisy, and reconstructed images

## Conclusion

Through this lab, practical skills were gained in building convolutional autoencoders for denoising tasks using Keras. The model demonstrated strong performance in reconstructing clean images from noisy inputs.

---

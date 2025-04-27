# Lab Work No. 3

## Topic
Recognition of clothing elements using Artificial Neural Networks (ANNs) in Keras.

## Objective
To develop skills in designing, training, and testing neural networks for image classification tasks using the Fashion MNIST dataset.

## Tasks
- Import and explore the dataset.
- Preprocess the data for input into a neural network.
- Build the neural network architecture.
- Train the neural network model.
- Evaluate model performance on the test set.
- Visualize training progress and model predictions.

## Libraries Used
- TensorFlow (Keras API)
- Matplotlib

## Dataset Description
Fashion MNIST is a dataset containing 70,000 grayscale images of clothing items, categorized into 10 classes. Each image has a size of 28x28 pixels.

Classes:
- 0 — T-shirt/top
- 1 — Trouser
- 2 — Pullover
- 3 — Dress
- 4 — Coat
- 5 — Sandal
- 6 — Shirt
- 7 — Sneaker
- 8 — Bag
- 9 — Ankle boot

## Project Structure
- `lab3_fashion_mnist.ipynb` — Main notebook containing the complete code.
- Screenshots:
  - Sample images
  - Model summary
  - Training and validation accuracy/loss graphs
  - Model predictions
- `Lab3_report.docx` — Full professional report describing the workflow, analysis, and conclusions.

## Key Steps
1. Import necessary libraries and load the Fashion MNIST dataset.
2. Normalize image pixel values to the [0, 1] range.
3. Build a basic neural network:
   - Flatten input layer (28x28 → 784).
   - Fully connected Dense layer with 128 neurons and ReLU activation.
   - Output Dense layer with 10 neurons and softmax activation.
4. Compile the model using the Adam optimizer and sparse categorical crossentropy loss.
5. Train the model using 80% of the training data with 20% reserved for validation.
6. Plot the training and validation accuracy and loss.
7. Evaluate the model's final accuracy on the unseen test set.
8. Visualize predictions versus true labels.

## Results
- Test set accuracy: **approximately 88–90%**.
- The model accurately distinguishes most clothing categories.
- Some confusion occurs between visually similar classes.

## Conclusion
Through this lab work, a neural network was successfully built, trained, and evaluated for clothing image classification. Practical skills in data preprocessing, neural network design, training, and result analysis using the Keras library were developed.


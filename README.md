# Handwritten Digit Recognition using TensorFlow and Keras

This project implements a handwritten digit recognition system using the MNIST dataset with TensorFlow and Keras. It builds and trains a neural network to classify digits (0-9) based on images from the dataset. Additionally, it allows predicting handwritten digits from new images.

## Project Structure

- `main.py`: The main script that loads the MNIST dataset, trains the model, and predicts digits from custom images.
- `digits.png`: A sample image used for prediction (replace with your own image).
- `README.md`: This file.

## Dependencies

Make sure to install the following Python libraries before running the project:

```bash
pip install tensorflow numpy pillow matplotlib
```
## How to Run
- `Download the Dataset`: The MNIST dataset will be automatically downloaded by TensorFlow during execution.

- `Train the Model`: Run the script to train the neural network on the MNIST dataset:

```bash
python main.py
```
- `Make Predictions` : After training, the model can be used to predict digits from custom images. Ensure the image is a grayscale PNG of size 28x28 pixels or adjust the script to preprocess it.

- `Preprocessing Custom Images`: Use the preprocess_image function to convert a handwritten digit image into a format suitable for prediction. The function inverts the image, resizes it to 28x28, normalizes it, and reshapes it for the model.
## Example
Here’s how to make a prediction:

- Place your handwritten digit image in the project directory and ensure it's named digits.png.
- Run the script, and it will output the predicted digit and display the image with the prediction.

## Example Output
```bash
Accuracy: 98.50%
Predicted Digit: 3
```
## Code Overview
## Accuracy
The trained model achieves an accuracy of approximately 98.50% on the MNIST test dataset.

## Future Work
- Explore using convolutional neural networks (CNNs) to improve accuracy.
- Implement better preprocessing for handwritten digits captured in real-world scenarios.
## License
-This project is licensed under the MIT License - see the LICENSE file for details.






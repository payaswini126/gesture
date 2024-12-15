Hand Gesture Recognition using CNN

This project is a simple hand gesture recognition system using a Convolutional Neural Network (CNN). The goal is to classify hand gestures into two categories: Gesture 1 and Gesture 2.

Features

Dummy Dataset: Random images simulate hand gesture data.

CNN Model: A simple CNN is trained to recognize gestures.

Visualization: Displays the prediction on a sample test image.

Requirements

Install the required libraries using pip:

pip install tensorflow numpy opencv-python scikit-learn matplotlib

How to Run

Clone the Repository:

git clone https://github.com/your-repo/hand-gesture-recognition.git

Run the Script:

python hand_gesture_classification.py

Workflow

Data Generation:

Dummy images (64x64 pixels) are generated for two gestures.

Gesture 1 = 0, Gesture 2 = 1.

Model:

A simple CNN with two convolutional layers and one dense output layer.

The model uses the Adam optimizer.

Evaluation:

Test accuracy is calculated on the test data.

A random test image is visualized with its predicted label.

Output Example

Training CNN Model...
Epoch 1/5
... (training progress)
Test Accuracy (CNN): 90.00%

Testing on Random Image...

Future Improvements

Use real hand gesture datasets.

Add more gesture classes.

Improve model accuracy.

Author

Your Name

License

This project is licensed under the MIT License.


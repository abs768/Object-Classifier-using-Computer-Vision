# Object Classifier using Computer Vision and Machine Learning

This Python mini project combines computer vision and machine learning to create a simple yet effective object classifier. The graphical user interface (GUI) is built with Tkinter, offering an intuitive platform for real-time model training and prediction. OpenCV is employed for camera handling, allowing users to capture and label frames for two custom object classes. The model, utilizing a Linear Support Vector Classifier (LinearSVC) from scikit-learn, is trained on the captured frames. The GUI provides buttons for auto-prediction, saving frames, training the model, and resetting.

## How to Use

1. Run `main.py` to launch the interface.
2. Define two object classes through the GUI.
3. Capture and label frames for each class.
4. Train the model using the "Train Model" button.
5. Click "Predict" to identify and display the object in real-time.

## Demo Video


https://github.com/abs768/Object-Classifier-using-Computer-Vision/assets/91774301/7cefb76e-4038-471b-9f69-fc5bc39fe198


Please refer to the demo video for a visual walkthrough of the application in action.

## Requirements

- Python 3.7
- OpenCV
- scikit-learn
- Tkinter

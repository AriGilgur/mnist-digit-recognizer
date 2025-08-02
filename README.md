# mnist-digit-recognizer
What You Built
I built a handwritten digit recognition system using a convolutional neural network (CNN). The system allows users to draw a digit (0-9) on a canvas in a web browser, then the model predicts which digit was drawn. The app was built using PyTorch for the neural network and Streamlit for the interactive web interface.

What Your Model Predicts
The model predicts which digit (from 0 to 9) a given grayscale image represents. It takes the user's drawing, processes it to the same format as the MNIST dataset images (28x28 pixels, grayscale, normalized), and outputs a predicted digit label.

What Results You Got
After training the CNN for 5 epochs on the MNIST dataset, the model achieved around 98.9% accuracy on the MNIST test set. This means the model correctly recognizes handwritten digits almost 99% of the time. The web app successfully predicts digits drawn live by users on the canvas.

What You Learned
I learned how to preprocess image data to fit the model’s input requirements, including resizing, grayscale conversion, and normalization. I learned how to build and train a simple CNN for image classification using PyTorch, as well as how to save and reload trained models. Additionally, I learned how to build a user-friendly web interface for machine learning models using Streamlit. I also understood the importance of user interaction features like buttons and brush size for a better user experience. Finally, I learned how a classic dataset like MNIST can be used to understand fundamental concepts in deep learning and computer vision.


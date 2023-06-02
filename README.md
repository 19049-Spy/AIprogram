# AI program
- Before you try the program for yourself, make sure you have OpenCV installed. You can install it by running 'pip install opencv-python' in your command prompt or terminal.
- Make sure to replace 'path_to_your_image.jpg' with the actual path to the image you want to detect faces in. The program will draw green rectangles around the detected faces and display the image with the detected faces.
- The pre-trained model is particularly designed for face detection is loaded by this application using the cv2.CascadeClassifier class. 
- The classifier is applied to the grayscale picture using the detectMultiScale function, which then returns the bounding boxes of the discovered faces. Finally, we use the cv2.rectangle method to create rectangles around the faces that have been recognized.

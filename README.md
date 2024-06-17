# Custom-Object-Detection-Using-Python-OpenCV--Training-Database-using-TeachableMachine
This is a Machine Learning Project. This Model Can Detect Any custom trained Objects. 

watch my YouTube Tutorial on -- (https://youtu.be/mS6EXW_YkwQ)

First train Your Models from Teachable Machine (https://teachablemachine.withgoogle.com/)

then download The model

And download the necessary Python libraries

Connect Your Webcam

run the main.py file

and you are ready to go..

Steps to Run the Code and Check for Errors:
Clone the Repository:Clone or download the repository from GitHub to your local machine.
Ensure Prerequisites:Check if you have all the necessary libraries installed (cv2, numpy, keras). You can install them using pip if not already installed:
pip install opencv-python numpy kerasCheck Model File:Ensure that the model.h5 file is present in the directory where you run the script. This file should contain the trained Keras model for object detection.Run the Script:Navigate to the directory containing main.py.Execute the script:python main.pyObserve Output:The script should open a window displaying the webcam feed with overlaid text (predictions) based on the object detection model.Check for any errors or warnings displayed in the console where you executed python main.py.Common Issues to Check:Missing Dependencies: Ensure all required libraries (cv2, numpy, keras) are installed and accessible.File Paths: Verify that the paths to model.h5 and any other required files (if mentioned in the script) are correct.Hardware Compatibility: Ensure your webcam is properly connected and accessible by OpenCV (cv2.VideoCapture(0)).Model Compatibility: Confirm that the model architecture and input size ((224, 224) in this case) match the requirements of the loaded model.h5.Error Handling Tips:If the script exits immediately or displays an error message, read the error message carefully to understand the issue.Common errors might include missing files (model.h5, required libraries), incompatible model formats, or incorrect input shapes.Debug by printing intermediate variables, checking image dimensions (img.shape), and verifying each step in the image preprocessing and prediction process.

Follow Me On Instagram -- https://www.instagram.com/angshutechofficial/
Also don't forgetto subscribe my YouTube cannel -- https://www.youtube.com/channel/UCDx8rZMuU8TUr-tcZ3CYP2g

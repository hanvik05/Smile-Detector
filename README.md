# Smile Detector
 The Smile Detector is a project aimed at automatically detecting whether a person is smiling or not. 
 This code uses the xml files from harcascade.
 <br />
 This is a Computer Vision project. 
 <br />
 <br />
This project uses face detection techniques to identify the different parts on the image.
This project on execution opens up a pop up video, which activates the laptop camera. In case you are using a external webcam change the following code 
<br />
video_capture = cv2.VideoCapture(0)
<br />
to 
<br />
video_capture = cv2.VideoCapture(1)
<br />
During the face detection the code breaks the image into several small parts and searches for important features (eyes, nose etc.…) in case of finding a face. The features for eye detection are eye balls, eye lashes. For the smile the code searches for lips, teeth as the features.

##  Code Output

A pop up window opens.

When you are not smiling
<br />
<img src="https://github.com/hanvik05/Smile-Detector/assets/16571807/e7150076-1b7b-4c99-a38c-80157b6de3a6" alt="notsmile" width="400" height="320">
<br />
When you are smiling
<br />
<img src="https://github.com/hanvik05/Smile-Detector/assets/16571807/0c0b9dca-00fe-4324-b727-7349da9392ef" alt="smile" width="400" height="320">
<br />
<br />
For closing the window press **q** in the keyboard.

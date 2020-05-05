#GENERAL STEPS-

1. Here, I have used the OpenCV to detect human face, which is given as an input through the Web-Cam.
2. Haar-cascade of human eye and frontal face image were used for the same.
3. The model marks a rectangular boundary around the input face.The webcam can be accessed by simply running the model on any suitable paltform (like Jupyter Notebook or Spyder for example) and once the detection is observed,it can be closed by simply pressing the 'q' button on the keyboard.

NB: The model will throw output if tried to run in Google Colab,as the code doesn't give colab the access to use the webcam of the computer. Use of javascript APIs that provide the (here)necessary use of colab accessing computer's webcam may be used,if we wish to run the model on Google colab (the model works pretty fine on normal CPU platform,so the use of colab here can be easily avoided.)

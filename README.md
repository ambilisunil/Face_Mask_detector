# Face_Mask_detector
it is a Desktop Application  for Real time Face mask Detection and Identify Unmasked persons

Machine Learning project use  Harr-cascade algorithm to create classifier(xml file).
Pyqty5 used to Deploy project as a Desktop app.

 
This project is based on Computer Vision. Using Object Detection Technology and Haar Cascade Algorithm, we can Implement a Face mask detector model. I n This current Situation its very useful. we can implement this is in cctv camera recordings, so its help police and recovery forces.
In This COVID-19 pandemic Masks and face coverings can prevent the wearer from transmitting the COVID-19 virus to others and may provide some protection to the wearer. Face mask detection is a simple model to detect face mask using OpenCv and Haar-cascade Classifier . By the development of face mask detection we can detect if the person is wearing a face mask and allow their entry would be of great help to the society.
In this project  the Face Mask detection model deploy as a desktop application using Pyqty. 

Additional feature of this project is identify the unmasked person and save their details in file. For this we can use face reorganization library.This  Face mask detector is a desktop app. Harr-cascade algorithm is used to train the model and build the classifier

*Data For Traing*

a. For mask detector

A folder containg 2 files named P and N. P contain postive imges(Masked persons images) and N contain Unmasked persons images.
Cascade_Training_Gui is used to train the model.  
After traing get a classifier in xml format.

b. For identify faces

Directory Structure of Data set ‘training’. This data set used to train the face_recoganization model.  It contain following folders. Each  of folder contains images of the specified persons mentioned in folder names.
Directory of  traing


mask.xml is the classifier for check person wear a mask or not
joblib file isa model tarined by face_recoganization  used to identify details of unmasked persons


*Requred Libaries*

opencv
pyQt5
face_recognition 
Matplotlib
Joblib 
NumPy
Sklearn
subprocess

*Usage*
run command
python MaskDetector.py



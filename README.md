# Iris-controlled-bot

final_code_client : this code which is supposed to be uploaded on the system, make sure  your system has python (software), opencv, dlib and socket libraries installed

final_code_server : this code which is supposed to be uploaded on the raspberry pi, it contains the command and command for making the robot mobile. Make sure raspberry pi has constant internet connection, socket library installed

shape_predictor_68_face_landmarks.dat.bz2 : is the zipped file of the data file which contains the facial landmarks of the human. It is necessary along with client python file for your system to recognise your face and mark them with landmark which is used to extract the RoI.

threshold values are obtained from hit and trial method because of lighting arrangements in different enviornment.

adjust the parameters (IP address, port number, directories) according to your system/requirement.

# FaceRecognition-based-attendance-system
//Aneesh Reddy

This project Involves a raspberry pi that runs a python code involving OpenCV and face-recognition libraries. The raspberry pi captures the face of the user and compares it to the faces stored in local memory and updates the attendance of the person in google spreadsheet and sends an email acknowledging the attendance. 

While enrolling a new person the raspberry pi captures the face and stores it in local memory and then enrolls the details of the person in a Google Spreadsheet. Then it sends an email to the person regarding the app password. 

The user can download the app (MIT app inventor-based) and view his attendance. 

This is a python based project you need the following libraries to run this code:
opencv-python
face_recognition
gspread oauth2client
gspread
secure-smtplib
pickle-mixin



How to use the code:
Create a google spreadsheet

enable drive and sheets api for it
and  get the credential files for it ( follow this video if you don't know how https://www.youtube.com/watch?v=cnPlKLEGR7E&t=391s&ab_channel=TechWithTim)

add the credentials file into the same directory 

change the credentials file name in the code (my file name is "creds")
change the spreadsheet file name in the code (my file name is"attendance") 
change the sender email ID. 
and you are good to go


Run the "enroll" file if you have to enroll a new person
Run the "recognition" file if you have to start taking attendance.

to use the android app go to mit app inventor and import the aia file provided

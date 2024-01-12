# automated_attendance
 Automated Facial Recognition Attendance System for Educational Institutions


Description

This project is a prototype for an attendance system using facial recognition, designed specifically for educational institutions. The system uses Haar Cascade Classifiers for accurate facial detection and the Local Binary Pattern Histogram algorithm for facial recognition. Additionally, the application's graphical user interface is built with Python Tkinter.




Steps to Follow:

Download the repository.
In the project, create a folder named ‘TrainingImage’.
In the file ‘fin.py', replace all paths with your system's paths.
Run ‘fin.py’.




Instructions

Run the program and enter your ID and name in the provided box. Click on 'Take Images' to capture 200 images of your face, which will be saved in the 'TrainingImage' folder.
To train the model, click on 'Train Images'. This process might take 5-10 minutes.
Once training is complete, select 'Automatic Attendance'. This feature uses the trained model (stored in 'TrainingImageLabel') to recognize faces and automatically fills in the attendance. It generates a .csv file for the attendance, and will name it by time and subject.
If you want to store attendance data in a database, install WampServer and update the database name in 'fin.py' as required.
The 'Manually Fill Attendance' button in the user interface allows for manual attendance entry (without face recognition). This also creates a .csv file and stores the data in the database.



Screenshot_1.png


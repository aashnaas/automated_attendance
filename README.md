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



<img width="720" alt="Screenshot_1" src="https://github.com/aashnaas/automated_attendance/assets/156178460/016094a9-49f0-40af-ba86-5c65f03b5141">



<img width="720" alt="Screenshot_2" src="https://github.com/aashnaas/automated_attendance/assets/156178460/ed8ea035-4e03-4389-ba77-4276bdd800d5">




<img width="720" alt="Screenshot_3" src="https://github.com/aashnaas/automated_attendance/assets/156178460/25162a57-8857-4ce3-b9ac-a62806c83ccf">


<img width="720" alt="Screenshot_4" src="https://github.com/aashnaas/automated_attendance/assets/156178460/578409de-a055-48a3-b176-3d5f89367af9">



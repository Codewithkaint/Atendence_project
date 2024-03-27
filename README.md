
# Attendance System with Dynamic QR Code and Face Recognition

This repository contains the source code for an Attendance System that allows teachers to create dynamic QR codes through a web site and enables students to mark their attendance using a mobile application. The system also incorporates face recognition to ensure that the right student is marking their attendance.

# Features


Dynamic QR Code Generation : Teachers can create dynamic QR codes from a website, which are automatically refreshed every 3 seconds. This ensures that each QR code is unique and cannot be reused for attendance marking.


Student Authentication : Students can log in to the mobile application using their student ID and password. Firebase Authentication is used to manage user authentication securely.

QR Code Scanning : Students can scan the dynamic QR code generated by the teacher. If the QR code data matches their credentials, they proceed to the next step.


Face Recognition : To further validate the student's identity, the system utilizes the Face++ API for face matching. Students are required to capture their picture, and the system checks if the captured face matches the database record of the respective student.


Attendance Marking : Only if the face recognition confirms the student's identity, they can mark their attendance.
Teacher Dashboard : Teachers can view a list of students who have marked their attendance through the website. This provides an easy way to track attendance in real-time.

# Technologies Used
Web Site : The web site for generating dynamic QR codes is built using HTML, CSS, and JavaScript, and it includes features for a Teacher Dashboard.


Mobile Application : The student mobile application is developed using JAVA , XML and Android Studio. Firebase used for authentication.


Face Recognition : Face++ API is integrated for face matching.
Database: Firebase is used for managing the database and user authentication.

Simple Qrcode attendance using Opencv

QR code, Attendance system, OpenCV, Real-time processing, Python, Image processing, pyzbar, Automation, Efficiency, Attendance tracking.

This paper presents a simple QR code-based attendance system utilizing OpenCV for real-time image processing and the pyzbar library for QR code decoding. The proposed system aims to streamline the process of attendance tracking, providing a quick, efficient, and error-free alternative to traditional methods. The implementation is divided into three primary components: QR code generation, QR code reading, and attendance logging.

Overview
1.Generate QR Codes:
Use a library to generate unique QR codes for each participant.
The QR code contains information such as the participant's name and ID.

2.Read QR Codes:
Use a camera (e.g., webcam) to scan QR codes.
Use OpenCV along with a barcode decoding library (like pyzbar) to detect and read the QR codes from the camera feed.

3.Log Attendance:
Extract the information from the QR code.
Log this information with a timestamp to keep track of attendance.

Summary
Generate QR Codes: Using the qrcode library.
Read QR Codes: Using OpenCV and pyzbar to decode QR codes.
Log Attendance: Writing attendance data to a file with timestamps.
This script will capture frames from your webcam, detect and decode any QR codes, and log the attendance information to a text file. Press 'q' to exit the video feed.

Feel free to expand this example by adding error handling, a graphical user interface, or integrating with a database for more robust functionality.

contacts:

Linkedin - https://www.linkedin.com/in/pravin-kumar-1b59ab2ab/

Github   - https://github.com/Pravink1005

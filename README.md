# FaceGuard – Smart Face Recognition Access Control System

## Description

FaceGuard is an AI-based Smart Face Recognition Access Control System designed to identify registered users and automatically control access. The system allows users to register their name, ID, department, email, and face image. During verification, the system captures a face using a webcam and compares it with the registered faces stored in the database. If a match is found, access is granted and the user's details are displayed. If the face is not registered, access is denied.

The project is developed using Python, Face Recognition, OpenCV, NumPy, SQLite, and Gradio. The Gradio interface provides a simple web-based platform for user registration, face verification, registered user management, and access-log monitoring.

## Features

- Multiple user registration
- Unique User ID/Register Number
- Webcam-based face capture
- AI-based face recognition
- Automatic access granting
- Automatic access denial
- User details display
- SQLite database
- Access logs with date and time
- Gradio web interface

## Technologies Used

- Python
- OpenCV
- Face Recognition
- NumPy
- SQLite
- Gradio
- Google Colab

## System Workflow

Register User → Capture Face → Generate Face Encoding → Store User Data → Capture Face for Verification → Compare with Registered Faces → Match Found → Access Granted / No Match → Access Denied → Store Access Log

## How It Works

1. The user registers their personal details and face image.
2. The system detects the face and generates a unique face encoding.
3. The face encoding and user details are stored in the SQLite database.
4. During verification, the webcam captures the user's face.
5. The captured face is compared with all registered faces.
6. If a matching face is found, access is granted.
7. If no matching face is found, access is denied.
8. The verification result is stored in the access log.

## Project Structure

```text
FaceGuard/
│
├── FaceGuard_Gradio_Colab.ipynb
├── README.md
├── database/
├── registered_faces/
└── logs/
```

## Future Enhancements

- Real-time continuous face recognition
- Multiple camera support
- Admin authentication
- Liveness/anti-spoofing detection
- Email or SMS notification for denied access
- Mobile application integration
- Hardware-based door lock integration

## Privacy Note

FaceGuard is developed as a college project prototype. Face images and biometric information should be collected with appropriate consent and stored securely. Real-world access control systems require additional security, privacy, and anti-spoofing measures.

## Project Motto

**“Recognize. Verify. Secure.”**

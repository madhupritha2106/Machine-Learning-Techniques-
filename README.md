AI-Based Fake/Tampered License Plate Detection Using Machine Learning

About the Project

This project proposes an AI-based system to detect vehicle license plates and identify potentially fake or tampered plates using Machine Learning and Computer Vision.

The system detects the license plate, extracts the plate number using OCR, analyses visual and textual characteristics, and classifies the plate as Genuine, Suspicious, or Tampered with a risk/confidence score.

Objective

- Detect and localise license plates from vehicle images or videos.
- Extract license plate numbers using OCR.
- Identify possible tampering such as irregular spacing, fonts, or alterations.
- Classify plates as Genuine, Suspicious, or Tampered.
- Generate a risk/confidence score.

Technologies Used

- Python
- OpenCV
- YOLO
- OCR
- CNN
- XGBoost
- Streamlit / Flask

System Workflow

Input Image/Video → Preprocessing → YOLO Plate Detection → OCR → CNN Feature Extraction → XGBoost Classification → Risk Score & Dashboard

 Modules

1. Image Acquisition & Preprocessing
2. License Plate Detection
3. License Plate Recognition
4. Fake/Tampering Detection
5. Risk Analysis & Dashboard

Output

The system provides the detected plate number, classification result, confidence/risk score, and reasons for suspicious detection.

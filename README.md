# SurakshaAI: Suspicious Activity Detection System Using AI and IoT

## Overview

SurakshaAI is an intelligent surveillance system designed to detect suspicious and abnormal activities in real-time using Artificial Intelligence and Internet of Things (IoT) technologies. The system aims to enhance public safety by automatically identifying activities such as fighting, vandalism, harassment, abuse, theft, and other unusual behaviors from surveillance camera feeds.

The solution leverages Deep Learning techniques for video analysis and generates instant alerts to security personnel, enabling faster response and improved situational awareness.

---

## Problem Statement

Traditional surveillance systems require continuous human monitoring, making them inefficient for large-scale deployments. Human operators may miss critical incidents due to fatigue, distractions, or the large volume of video data.

SurakshaAI addresses this challenge by automating suspicious activity detection and providing real-time alerts whenever abnormal behavior is detected.

---

## Objectives

- Detect suspicious activities in real-time from surveillance footage.
- Reduce dependency on manual monitoring.
- Improve public safety and security.
- Generate instant notifications for detected incidents.
- Integrate AI-based analytics with existing CCTV infrastructure.

---

## Key Features

- Real-time suspicious activity detection
- Violence and fight detection
- Theft and vandalism detection
- Harassment and abnormal behavior recognition
- Automated alert generation
- Live video stream processing
- AI-powered event classification
- Scalable surveillance architecture
- Integration with existing CCTV systems
- IoT-enabled notification support

---

## System Architecture

1. Video Feed Acquisition
2. Frame Extraction and Preprocessing
3. Object and Human Detection
4. Activity Recognition
5. Suspicious Event Classification
6. Alert Generation
7. Security Monitoring Dashboard

---

## Technologies Used

### Programming Languages
- Python

### Deep Learning & Machine Learning
- PyTorch
- TensorFlow
- OpenCV
- NumPy
- Pandas
- Scikit-Learn

### Computer Vision
- YOLOv7
- CNN (Convolutional Neural Networks)
- LSTM (Long Short-Term Memory Networks)

### IoT & Communication
- Email Notifications
- SMS Alert Integration
- Mobile Application Notifications

### Development Tools
- Jupyter Notebook
- Google Colab
- VS Code
- Git
- GitHub

---

## Datasets Used

### UCF Crime Dataset
Contains real-world surveillance videos involving criminal and abnormal activities.

Activities include:
- Abuse
- Arrest
- Assault
- Burglary
- Fighting
- Robbery
- Theft
- Vandalism

### Avenue Dataset
Used for anomaly detection and abnormal event recognition.

### Violent-Flows Dataset
Used for crowd violence and aggressive behavior detection.

---

## Methodology

### Data Collection
Video datasets containing normal and abnormal activities are collected from publicly available sources.

### Data Preprocessing
- Frame extraction from videos
- Image resizing
- Data normalization
- Data augmentation
- Train-test split

### Object Detection
YOLOv7 is used to detect humans and relevant objects from surveillance footage.

### Feature Extraction
CNN layers extract spatial features from individual video frames.

### Temporal Analysis
LSTM networks capture temporal dependencies and movement patterns across video sequences.

### Activity Classification
The extracted features are classified into:

- Normal Activity
- Suspicious Activity

### Alert Generation
When suspicious behavior is detected, alerts are generated and sent to authorized personnel.

---

## Project Workflow

```text
Video Input
      │
      ▼
Frame Extraction
      │
      ▼
Preprocessing
      │
      ▼
YOLOv7 Object Detection
      │
      ▼
CNN Feature Extraction
      │
      ▼
LSTM Temporal Analysis
      │
      ▼
Activity Classification
      │
      ▼
Alert Generation
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/SurakshaAI.git
cd SurakshaAI
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

### Training

```bash
python train.py
```

### Testing

```bash
python test.py
```

### Real-Time Detection

```bash
python detect.py
```

---

## Expected Outcomes

- Automated surveillance monitoring
- Faster incident detection
- Reduced human workload
- Improved public safety
- Real-time suspicious activity alerts
- Enhanced security management

---

## Applications

### Smart Cities
Monitoring public areas, roads, and transportation hubs.

### Educational Institutions
Detecting violence, bullying, and unauthorized activities.

### Corporate Offices
Preventing theft and security breaches.

### Shopping Malls
Monitoring suspicious customer behavior.

### Residential Complexes
Enhancing community security.

### Industrial Facilities
Detecting unsafe activities and unauthorized access.

---

## Future Enhancements

- Multi-camera surveillance support
- Edge AI deployment
- Cloud-based monitoring dashboard
- Facial recognition integration
- Crowd density analysis
- Weapon detection module
- Real-time mobile application alerts
- Multi-agent intelligent surveillance systems

---

## Research and Innovation

This project is based on the application of Artificial Intelligence, Deep Learning, Computer Vision, and IoT technologies for automated surveillance and public safety enhancement.

### Patent Publication

**SurakshaAI: Suspicious Activity Detection by Leveraging AI and IoT**

Patent Application Published under the Indian Patent Office.

---

## Contributors

- Rohini Koli
- Project Team Members

---

## Acknowledgements

- UCF Crime Dataset
- Avenue Dataset
- Violent-Flows Dataset
- OpenCV Community
- PyTorch Community
- TensorFlow Community
- YOLO Research Team

---

## License

This project is developed for academic, research, and educational purposes.

---

## Contact

For research collaborations, project discussions, or academic inquiries:

**Rohini Koli**

Artificial Intelligence and Data Science

Email: your-email@example.com

GitHub: https://github.com/yourusername

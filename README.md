Real-Time Fatigue Monitoring & Alert System
**Project Type**
Implementation Project – Computer Vision Based Monitoring System

**Overview**
This project involves the implementation of a real-time fatigue monitoring system using computer vision techniques. The system detects eye-blink patterns through live webcam input and classifies fatigue levels. Based on predefined thresholds, visual and audio alerts are triggered to notify users when rest may be required.
The objective of this project was to implement a practical monitoring solution that operates in real time with stable performance.

**Problem Statement**
Extended screen usage can lead to eye strain and fatigue, affecting concentration and productivity. Users may not recognize early fatigue signs during continuous work sessions.
This project addresses the need for a real-time automated mechanism to monitor fatigue and provide timely alerts without interrupting workflow.

Key Features
* Live webcam-based facial landmark detection
*Eye-blink ratio calculation
*Fatigue level classification (Active / Mild Fatigue / Critical Fatigue)
*On-screen status display
*Audio alert system
Continuous real-time monitoring

**Implementation Approach**
The system uses MediaPipe Face Mesh to detect facial landmarks from live video input. Eye landmarks are extracted and Euclidean distance is calculated to determine blink ratios.Fatigue levels are classified based on predefined blink thresholds. When thresholds are exceeded, the system displays visual alerts and triggers an audio notification.The implementation was tested iteratively to ensure reliable performance during continuous usage.

**Implementation Flow**
Capture live video using webcam
Detect facial landmarks using MediaPipe
Extract eye landmarks
Calculate blink ratio
Classify fatigue level
Display fatigue status
Trigger alert when threshold is exceeded

**Requirements**
Functional Requirements
Real-time webcam input
Facial landmark detection
Blink ratio calculation
Fatigue classification logic
Visual and audio alert system

**Non-Functional Requirements**
Minimal processing delay
Stable execution
Non-intrusive alerts
Consistent detection accuracy

**Tools & Technologies**
Python
OpenCV
MediaPipe
NumPy
Pygame

Installation & Setup
1. Clone the Repository
git clone https://github.com/aryamenoth/blinkfatiguedetection.git
cd blinkfatiguedetection
2. Install Dependencies
pip install -r requirements.txt
3. Run the Application
python main.py
Press ESC to exit the application.

**Observations During Testing**
Blink ratios remained stable during active usage
Reduced blink frequency observed during fatigue conditions
Alerts triggered consistently after threshold breach
Stable performance maintained during continuous runtime

**Challenges**
Maintaining detection accuracy in real-time conditions
Adjusting fatigue thresholds to avoid false alerts
Ensuring alerts are noticeable but not disruptive

**Future Enhancements**
Configurable fatigue thresholds
Fatigue trend dashboard
Desktop/mobile integration
Multi-user support

Project Status
End-to-end implementation completed and tested for real-time execution.

Author
Arya M A
MSc Computer Science (Data Science)

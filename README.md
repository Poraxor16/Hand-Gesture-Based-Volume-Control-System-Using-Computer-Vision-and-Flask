# Hand-Gesture-Based-Volume-Control-System-Using-Computer-Vision-and-Flask
Overview
The Hand Gesture Based Volume Control System is an innovative approach to controlling system volume using hand gestures.
 This project leverages computer vision techniques and machine learning models to detect hand landmarks, and adjust the system's volume accordingly. 
 The system utilizes OpenCV, MediaPipe, Pycaw, and Flask to provide a seamless, touchless user experience.

#Features:
- Real-time Hand Gesture Recognition: Detects hand gestures using MediaPipe.
- Volume Control: Adjusts system volume based on the distance between the thumb and index finger.
- Web Interface: Flask-based user interface to control and visualize the system’s status.
- Touchless Interaction: Provides an alternative, hands-free way to control system volume.
  
#Technologies Used
- OpenCV: For handling video capture and image processing.
- MediaPipe: For hand gesture recognition and tracking.
- Pycaw: For controlling the system's audio settings.
- Flask: To create the web-based interface for starting and monitoring the script.
  
#Requirements
- Python 3.x
- OpenCV
- MediaPipe
- Pycaw
- Flask
  
#Other dependencies can be installed using the provided requirements.txt.

##Installation
- Step 1: Clone the repository
#bash
## git clone https://github.com/yourusername/hand-gesture-volume-control.git
cd hand-gesture-volume-control

- Step 2: Install required packages
# bash
- pip install -r requirements.txt
  
#Step 3: Set up the system
- Ensure that you have a working camera connected to your computer.
- Install the necessary drivers for the camera.
  
- Step 4: Run the Flask Application

# Navigate to the project directory.
- Run the Flask app:
# bash
#python app.py
- The application will run on http://127.0.0.1:5000. Open it in your browser.
  
- Step 5: Start the Hand Gesture Script
- Click the Start button on the web interface to launch the hand gesture recognition script.
- Adjust your hand gestures to control the volume.
  
#How it Works
- Hand Gesture Recognition: The system uses MediaPipe to track the landmarks of the hand (specifically the thumb and index finger). 
- The distance between these two fingers is calculated in real-time.
- Volume Control: Based on the hand gesture, the system adjusts the volume of the computer.
- The closer the fingers are, the lower the volume, and as they move apart, the volume increases.
-Web Interface: The web interface allows the user to start the gesture control system by clicking a button, providing an interactive way to control and monitor the system.

#Project Structure
hand-gesture-volume-control/
│
├── app.py                    # Main Flask application
├── handtrack.py               # Python script for hand gesture tracking and volume control
├── requirements.txt           # Python dependencies
├── templates/                 # Folder containing HTML files
│   └── index.html             # Frontend for the web application
└── static/                    # Folder for static files (e.g., images, CSS, JS)

###This project is copyright for Ashish Parasar### 

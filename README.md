# Object-Detection-Model
A browser-based application that performs real-time object detection using your webcam and TensorFlow.js. This app leverages state-of-the-art AI models to identify and classify objects in your camera feed with bounding box visualization.

![image](https://github.com/user-attachments/assets/5ed45ac0-1ea5-4c5f-8074-ce8c6cfee99f)
![image](https://github.com/user-attachments/assets/f93f753e-eca3-459d-b44b-ce413efcb384)

Features
Multiple AI Models: Choose between COCO-SSD, MobileNet, and EfficientDet detection models
Real-time Detection: Process webcam feed with adjustable FPS and detection metrics

Customizable Settings:
Confidence threshold adjustment
Maximum detections limit
Model selection


Visual Feedback:
Color-coded bounding boxes based on confidence
Detection labels with percentage confidence
Real-time results list

Performance Statistics:
Detection frames per second (FPS)
Processing time in milliseconds
Most commonly detected object


Snapshot Capability: Capture and save detection results as images
Responsive Design: Works across desktop and mobile devices

Technologies Used:
TensorFlow.js
COCO-SSD, MobileNet, and EfficientDet models
HTML5 Canvas API
MediaDevices API (WebRTC)
Modern CSS (Flexbox, Grid, Variables)
Material Design Icons

Getting Started
Prerequisites

Modern web browser (Chrome, Firefox, Edge, Safari)
Webcam or camera device
Internet connection (for initial model loading)

Usage

Click "Start Camera" to initialize your webcam
Adjust detection settings as needed:

Select the AI model (COCO-SSD is recommended for beginners)
Set confidence threshold (higher values = fewer but more confident detections)
Set maximum detections to limit processing


Click "Start Detection" to begin real-time object detection
Use "Take Snapshot" to capture the current frame with detection results
Click "Stop" to end the session and release the camera

Customization
You can easily customize this application:

Add New Models: Extend the model selection with other TensorFlow.js compatible models
Custom Styling: Modify the CSS variables in the :root selector to change the color scheme
Extra Features: Extend functionality with object counting, motion tracking, or specific object alerts

Browser Compatibility
This application uses modern web APIs and is compatible with:

Chrome 76+
Firefox 75+
Edge 79+
Safari 13+

Mobile browsers are supported, but performance may vary based on device capabilities.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

TensorFlow.js team for the excellent machine learning library
The creators of the COCO-SSD, MobileNet, and EfficientDet models
Google's Material Design Icons for the user interface elements


Made with ❤️ by Bikram Sardar

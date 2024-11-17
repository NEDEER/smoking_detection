🚭 Smoking Detection Using Face and Hand Tracking

(Add an actual screenshot from your project instead of this placeholder)

📋 Overview
This project uses Computer Vision to detect whether a person is smoking or not based on their hand proximity to their face. It employs Face Mesh Detection, Hand Tracking, and a custom logic to calculate the distance between specific facial landmarks and hand landmarks.

🛠 Key Features
Real-time hand and face detection using CVZone and OpenCV.
Displays a simple message ("Smoking" or "No Smoking") based on detected behavior.
Clean, simple text overlay for the detection message.
Works with any video file or webcam input.
🖼 Demo Preview
Smoking Detected

The system shows "Smoking" when the right hand is close to the face.

No Smoking Detected

The system shows "No Smoking" otherwise.

⚙️ Technologies Used
Python 3.9+
OpenCV - For video frame processing.
CVZone - For face mesh, face detection, and hand tracking.
FaceMeshModule - Detects facial landmarks.
HandTrackingModule - Tracks hand landmarks.
FaceDetectionModule - Finds face bounding boxes.
🚀 Installation and Setup
Step 1: Clone the Repository
bash
Copy code
git clone https://github.com/your-username/smoking-detection.git
cd smoking-detection
Step 2: Install Dependencies
Install the required Python libraries:

bash
Copy code
pip install opencv-python cvzone mediapipe
Step 3: Run the Project
Run the script using the following command:

bash
Copy code
python smoking_detection.py
📝 Usage
Replace smooo.mp4 in the script with your video file path or use your webcam.
The program displays a message "Smoking" or "No Smoking" based on the calculated distance.
Quit the application by pressing the q key.
📂 Project Structure
bash
Copy code
.
├── README.md           # Project Documentation
├── smoking_detection.py  # Main Script
├── smooo.mp4           # Sample Video (Replace with your own)
└── images/             # Folder for demo images (Optional)
🎨 Customization
Text Position: Adjust the position of the "Smoking"/"No Smoking" message in the code using cv2.putText().
Threshold Distance: Modify the distance threshold (currently 30) in the logic to fine-tune detection sensitivity.
Video Source: Replace the video file path with a webcam feed or a different video.
🛠 Future Improvements
Add audio alerts (e.g., warning sound for smoking).
Extend detection for multiple faces in the frame.
Support for edge cases like occluded hands or partial face visibility.
🤝 Contributions
Contributions are welcome!
If you'd like to improve the project, fork the repository and submit a pull request.

📧 Contact
For any queries or support, feel free to reach out:
📩 your-email@example.com

📜 License
This project is licensed under the MIT License.
See the LICENSE file for details.

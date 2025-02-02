# Face Identification using YOLOv8 and DeepFace

This project implements a face recognition-based attendance system using YOLOv8 for face detection and DeepFace for face recognition. The system captures video from a webcam, detects faces, and identifies individuals by comparing them against a pre-created embedding database. Detected individuals are logged into an attendance file with timestamps.

## Features
- **Face Detection**: Utilizes YOLOv8 for real-time face detection.
- **Face Recognition**: Employs DeepFace with the VGG-Face model to recognize individuals.
- **Attendance Logging**: Logs recognized individuals into a CSV file with date and time.
- **Real-Time Processing**: Displays the video feed with FPS and the last detected individual.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Shedzuu/Face_identification_yolo-deepface.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
1.  Database Creation: Place images of individuals in the dataset folder following the naming convention Surname_Firstname_ID.
2.  Run the model at identification_model.ipynb
3.  Exit: Press q to stop the video feed and close the application.

## Repository Structure
- dataset/: Contains images for creating the embedding database.
- runs/: Stores YOLOv8 model weights.
- attendance_log.csv: Logs attendance entries.
- data.yaml: Configuration file for YOLOv8.
- face_photo_taker.ipynb: Notebook for capturing face images.
- identification_model.ipynb: Notebook for model training and testing.
- requirements.txt: Lists all required Python packages.


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.


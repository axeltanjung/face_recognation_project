# Face Recognition and Attendance Project

## Overview
This project is designed to implement a face recognition system for attendance tracking. The system captures images of individuals, recognizes their faces, and logs their attendance automatically.

## Features
- **Face Detection**: Detects faces in real-time using a webcam.
- **Face Recognition**: Identifies individuals based on pre-trained models.
- **Attendance Logging**: Records attendance data with timestamps.
- **User Management**: Allows adding and removing users from the system.

## Technologies Used
- **Python**: Main programming language.
- **OpenCV**: For image processing and face detection.
- **dlib**: For face recognition.
- **SQLite**: For storing attendance records.
- **Flask**: For creating a web interface (optional).

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/face_recognition_attendance.git
    ```
2. Navigate to the project directory:
    ```bash
    cd face_recognition_attendance
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the face recognition script:
    ```bash
    python recognize_faces.py
    ```
2. Access the web interface (if using Flask):
    ```bash
    python app.py
    ```
    Open your browser and go to `http://localhost:5000`.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact [yourname@example.com](mailto:yourname@example.com).
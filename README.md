# Face Recognition Attendance System

This project is a Flask web application that utilizes face recognition technology to track attendance. It captures images of individuals, trains a model to recognize faces, and records attendance in a CSV file.

## Features

- Real-time face detection and recognition using OpenCV.
- Attendance tracking with timestamps.
- User-friendly web interface for managing attendance.
- Ability to add new users and train the model with their images.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create a virtual environment:
   ```bash
   python -m venv myenv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     myenv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source myenv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Step-by-Step Process to Run the Code
1. Ensure you have the necessary files:
   - `background.png`: Background image for the attendance interface.
   - `haarcascade_frontalface_default.xml`: Pre-trained face detection model.

2. Run the application:
   ```bash
   python app.py
   ```

3. Open your web browser and navigate to `http://127.0.0.1:5000/` to access the application.

4. Use the interface to add new users, capture their images, and track attendance.

## Dependencies

- Flask
- OpenCV
- NumPy
- Pandas
- scikit-learn
- Joblib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenCV for computer vision capabilities.
- Flask for the web framework.
- scikit-learn for machine learning functionalities.

# Attendance-Management
<h1>Attendance Management System</h1>

<h2>Overview</h2>
The Attendance Management System is a Python-based application designed to manage and record attendance using CSV files for data storage. It includes features for manual attendance management, automatic face recognition, and a Streamlit-based interface for ease of use.

<h3>Features</h3>

1.Face Recognition:
Automatically detects and identifies individuals for attendance marking.
Uses Haarcascade models for face detection.
2.Manual Attendance:
Record attendance manually via CSV files.
User-Friendly Interface:
Built using Streamlit for interactive and easy navigation.
3.Attendance Records:
Attendance is stored in structured CSV files, organized by date and subject.
4.Student Management:
Stores student details in a dedicated CSV file.
Technologies Used

Programming Language: Python 3.x

Libraries:
OpenCV for face recognition.
Streamlit for GUI.
Pandas for handling CSV files.

Data Storage: CSV files for attendance and student details.

Project Structure

Attendance Management/  
├── Attendance/  
│   └── Manually Attendance/         # Contains manually marked attendance records  
├── Streamlit/  
│   ├── app.py                       # Streamlit application entry point  
├── StudentDetails/  
│   └── StudentDetails.csv           # File storing student details  
├── TrainingImage/  
│   └── Images for training the face recognition model  
├── TrainingImageLabel/  
│   ├── haarcascade_frontalface_alt.xml  # Haarcascade XML for face detection  
│   ├── haarcascade_frontalface_default.xml  
├── main_Run.py                      # Main file for running the application  
├── mini_app.py                      # Mini version of the app for testing  
├── testing.py                       # Script for testing the system  
├── training.py                      # Script for training the face recognition model  
├── requirements.txt                 # List of Python dependencies  
├── README.md                        # Project documentation  

<h3>Installation</h3>

Prerequisites

Install Python 3.x.
Install the required Python libraries:

pip install -r requirements.txt  

cd attendance-management  
 
Usage

Main Functionalities

Mark Attendance Automatically:
Launch the application and let the system detect and record attendance using facial recognition.
Mark Attendance Manually:
Add entries directly to the CSV files in the Attendance/Manually Attendance folder.
View Attendance Records:
Check CSV files or use the Streamlit interface for viewing attendance reports.
Future Enhancements
Integrate cloud-based storage for better accessibility and scalability.
Add notifications for absenteeism.
Enable report generation directly within the application.

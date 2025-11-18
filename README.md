# Face Recognition Attendance System
* A Python GUI application using OpenCV and Tkinter to capture student faces, train a recognition model, and mark attendance automatically in Excel/CSV format. 
## ⚙️ Setup
* Install Dependencies:
pip install opencv-python opencv-contrib-python numpy pandas pillow
* ⚠️ Critical Fix:
The code contains a hardcoded file path.
Before running:
Locate haarcascade_frontalface_default.xml on your system (or download it).
Open the script and replace the long path in harcascadePath with the correct path to your XML file.

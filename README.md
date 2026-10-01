
# Green Screen Background Replacement using Python

## 📌 Overview
A Python-based project that uses OpenCV and NumPy to replace the green screen background in a video with a custom image while preserving the original colors of the subject.

## 🚀 Features
- Green screen detection using HSV color space.
- Background removal using color masking.
- Custom background replacement.
- Real-time video frame processing.
- Preserves the original colors of the subject.

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy

## 📂 Project Structure
```text
Green-Screen-Replacement/
│
├── green.py
├── green.mp4
├── bg.jpg
├── requirements.txt
└── README.md
```

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Green-Screen-Replacement.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Green-Screen-Replacement
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage

1. Place your green screen video (`green.mp4`) and background image (`bg.jpg`) in the project folder.
2. Run the Python script:
   ```bash
   python green.py
   ```
3. View the output and press **Q** to exit.

## 🔍 How It Works
1. Captures video frames using OpenCV.
2. Converts frames from BGR to HSV color space.
3. Detects green pixels using HSV color thresholds.
4. Creates masks to separate the subject from the green background.
5. Combines the original subject with the custom background.
6. Displays the final output.

## 📦 Requirements
```text
opencv-python
numpy
```

## 🎯 Future Improvements
- Improve edge detection and background removal.
- Support video output saving.
- Add adjustable HSV color thresholds.
- Implement smoother background blending.

## 👩‍💻 Author
**Tanushree Yaltiwar**

## 📄 License
This project is open-source and available for educational purposes.

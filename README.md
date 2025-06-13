# 🔍 Number Plate Recognition using Python

This project performs **automatic number plate detection** using image processing techniques in Python. It scans vehicle images and detects license plates from them.

---

## 📁 Project Structure

Number_Plate-python-main/
├── number_plate.py # Main script for plate detection
├── Requirement.txt # Required Python libraries
└── Plates/ # Folder containing test plate images
├── scaned_img_0.jpg
├── scaned_img_1.jpg
└── ...

## 🚀 Features

- Detects number plates from input vehicle images
- Uses image processing techniques like contour detection and thresholding
- Visual output of detected plates for easy verification

---

## 🧠 Technologies Used

- Python
- OpenCV
- NumPy

---

## 🔧 Setup Instructions

1. Clone this repository or download the ZIP.
2. Install dependencies:
   ```bash
   pip install -r Requirement.txt
Run the script:
python number_plate.py
📌 Folder Plates/
Contains sample vehicle images to test the number plate recognition functionality.

📈 Future Improvements
Integrate OCR (Tesseract) to extract text from plates

Add live webcam support for real-time detection

Improve accuracy for varied plate formats

👤 Author
Developed as a Python-based image processing project for vehicle number plate detection.

# Vehicle Number Plate Detection

## Description
This project is a Python-based system designed to detect vehicle number plates from images using Optical Character Recognition (OCR). It processes images to extract vehicle number plate information, which can be useful in applications such as automated vehicle identification systems for parking lots, toll booths, and security checks.

## Features
- Pre-processes images to enhance number plate detection.
- Uses OCR to extract text from vehicle number plates.
- Outputs extracted text and processed images for further use.

## Installation Steps
To install and run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vehicle-number-plate-detection.git
   cd vehicle-number-plate-detection

2. Install the required packages:
    ```bash
    pip install -r requirement/requirement.txt

3. Run the Project
    ```bash
   python main_code/number_plate.py

## How it works
- Preprocesses the input image to improve the clarity of number plates.
- Uses Tesseract-OCR to extract text from the number plates.
- Outputs the extracted number plate text along with processed images for verification.

# Text Detection with EasyOCR

This repository demonstrates how to use EasyOCR and OpenCV to detect and recognize text in images. The implementation includes drawing bounding boxes around detected text and visualizing the results.

## Project Overview
The objective of this project is to showcase a simple yet effective approach for text detection in images using EasyOCR. The detected text is highlighted with bounding boxes and overlaid on the image for easy interpretation.

## Features
- **Text Detection**: Uses EasyOCR to detect and recognize text in images.
- **Bounding Boxes**: Draws bounding boxes around detected text with confidence scores above a specified threshold.
- **Visualization**: Displays the processed image with detected text highlighted.

## Repository Contents
- **`main.py`**: Python script for text detection and visualization.
- **`data/`**: Directory containing example images (e.g., `test1.png`).
- **`requirements.txt`**: List of required Python libraries.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ArianDilfanian/Text-Detection-EasyOCR.git
   cd Text-Detection-EasyOCR
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure EasyOCR is properly installed:
   ```bash
   pip install easyocr
   ```

## Usage
1. Run the Python script:
   ```bash
   python main.py
   ```

2. The script processes the image specified in `image_path` (default: `data/test1.png`). Replace `image_path` with the path to your own image if needed.

3. Detected text will be displayed on the console and visualized in a matplotlib window.

## Code Explanation
The core implementation involves:
- Reading the input image using OpenCV.
- Initializing an EasyOCR reader instance for text detection.
- Drawing bounding boxes and overlaying detected text for visual clarity.
- Displaying the processed image using matplotlib.

## Customization
- **Threshold**: Adjust the `threshold` variable to control the confidence score required for displaying detected text.
- **Image Path**: Change `image_path` to specify a different image file.
- **Languages**: Modify the EasyOCR reader initialization (`easyocr.Reader(['en'])`) to include other languages supported by EasyOCR.

## Dependencies
- Python 3.8+
- OpenCV
- EasyOCR
- Matplotlib

Install these using:
```bash
pip install opencv-python easyocr matplotlib
```

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions or improvements.


## Acknowledgments
- [EasyOCR](https://github.com/JaidedAI/EasyOCR) for text detection and recognition.
- [OpenCV](https://opencv.org/) for image processing tools.


## Test

![Screenshot 2024-12-02 234007](https://github.com/user-attachments/assets/3cca812c-2ab3-48a1-a1ed-1b1863fa6530)
![Screenshot 2024-12-02 234046](https://github.com/user-attachments/assets/3afd630f-3b3b-44d0-9ebe-8230744a88e3)
![Screenshot 2024-12-02 234137](https://github.com/user-attachments/assets/a5fc1271-000f-43ed-af07-6229c695bbdc)


# OCR Image Text Extraction

## Overview
This project is a Python-based Optical Character Recognition (OCR) system that extracts text from images using OpenCV and Tesseract OCR. The program fetches images from provided URLs, preprocesses them, and then applies OCR to extract text.

You can find the .ipynb file, download it, and directly run it in a Jupyter notebook environment.

## Features
- **Download Images**: Fetches images from given URLs and ensures they are in a valid format.
- **Preprocessing**: Converts images to grayscale and applies thresholding for improved text recognition.
- **OCR Implementation**: Uses Tesseract OCR to extract text from images.
- **Visualization**: Displays the original and processed images using Matplotlib.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: OpenCV, PIL (Pillow), Requests, NumPy, Matplotlib, Tesseract OCR

## Installation
### Prerequisites
Make sure you have Python installed (preferably Python 3.8 or higher). Then, install the required dependencies:

```bash
pip install opencv-python numpy requests pillow matplotlib pytesseract
```

### Install Tesseract OCR
#### Windows
Download and install Tesseract from [here](https://github.com/UB-Mannheim/tesseract/wiki). After installation, add it to your system's PATH.

#### Linux/Mac
```bash
sudo apt install tesseract-ocr  # For Ubuntu/Debian
brew install tesseract  # For Mac
```

## Usage
Run the script and provide image URLs when prompted:

```bash
python ocr_image_extractor.py
```

### Example Input
```
Enter image URLs (comma-separated): https://example.com/image1.jpg, https://example.com/image2.png
```

### Example Output
```
Extracted Text from Image 1:
Hello, this is an example!
--------------------------------------------------
Extracted Text from Image 2:
Sample OCR output text.
--------------------------------------------------
```

## Code Structure
- `ocr_image_extractor.py`: Main script for downloading images, preprocessing, applying OCR, and displaying results.
- `requirements.txt`: List of required Python dependencies.

## Future Enhancements
- Support for batch processing multiple images simultaneously.
- Integration with a graphical user interface (GUI).
- Support for more advanced image processing techniques.

## License
This project is licensed under the MIT License.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

## Contact
For any inquiries, contact Vigneshwaran at chokkalingamvigneshwaran@gmail.com


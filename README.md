# Barcode Detection and Verification

This project detects barcodes in images and verifies them against predefined barcode data.

## Features
- **Barcode & OCR Processing**: Uses OpenCV, pytesseract, and pyzbar for barcode recognition.
- **Predefined Barcode Matching**: Compares extracted barcodes with a stored list in `data.txt`.
- **Image Processing & Visualization**: Uses OpenCV for image processing and Matplotlib for visualization.
- **Dependency Management**: Installs required packages and system dependencies automatically.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repository
   ```
3. Install dependencies:
   ```sh
   pip install opencv-python-headless pytesseract pyzbar
   ```
4. Install system dependency:
   ```sh
   !apt install libzbar0
   ```

## Usage

1. Place the image file (`.jpg` or `.png`) in the working directory.
2. Place predefined barcode data in `data.txt`.
3. Run the script:
   ```sh
   python barcode_scanner.py
   ```

## Deployment

### Deploying to GitHub

1. Initialize a Git repository (if not already initialized):
   ```sh
   git init
   ```
2. Add all files to the repository:
   ```sh
   git add .
   ```
3. Commit the changes:
   ```sh
   git commit -m "Initial commit"
   ```
4. Add the remote repository:
   ```sh
   git remote add origin https://github.com/your-username/your-repository.git
   ```
5. Push the changes to GitHub:
   ```sh
   git push -u origin main
   ```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
Specify the license for your project.

## Contact
Your Name - [your-email@example.com](mailto:your-email@example.com)

GitHub: [your-username](https://github.com/your-username)



# Smart Vision Technology Quality Control - Flipkart GRID 6.0

**Project Overview:**  
This solution leverages advanced imaging and machine learning techniques to automate product quality and quantity assessment for Flipkart’s e-commerce platform. It integrates cutting-edge computer vision technology to detect freshness, analyze product type, and verify expiry dates.

## Features:
- **Freshness Detection**: Utilizes machine learning to assess the quality of fruits and vegetables.
- **OCR for Expiry Date**: Automatically recognizes and logs expiration dates for products.
- **Product Classification**: Identifies product types using state-of-the-art image analysis models.
- **Mobile-Friendly Website**: Built with HTML, CSS, and JavaScript, the interface allows users to upload images for analysis via both desktop and mobile devices.

## Technology Stack:
- **Frontend**: HTML, CSS, JavaScript (Fully mobile-responsive website)
- **Backend & Processing**: Python, OpenCV, EasyOCR, TensorFlow , YOLOv5
- **Google Colab**: For running ML models and processing images uploaded by the user.
- **Google Sheets Integration**: Results of OCR and analysis are logged into Google Sheets for real-time tracking.

## Repository Contents:
- **`smart_vision.py`**: Core analysis code for freshness prediction, product type detection, and ML-based analysis.
- **`fruit_analysis.py`**: Code handling OCR and expiry date recognition.
- **Frontend Files**: Website files for user interaction (uploading images for analysis).

## How to Use:
1. Clone this repository:
   ```bash
   git clone https://github.com/Anshsingh512/Anshsingh512.github.io
   ```
2. **Google Colab Setup**:  
   - The core analysis code is hosted in Google Colab for efficient computation.  
   - Upload the `client_secret.json` file to authenticate with Google Sheets.
   - Execute the code in `smart_vision.py` for freshness analysis and `fruit_analysis.py` for OCR and expiry date recognition.
   
   > **Note:** This project requires Google Colab to run smoothly. Ensure the images to be analyzed are uploaded to your Google Drive, as mentioned in the code.

3. **Private Usage**:  
   This project has been developed for Flipkart GRID 6.0 and uses confidential components like `client_secret.json` for integration with Google Sheets. The use of APIs has been streamlined, and the solution behaves as an automated process for analyzing product images.

4. **Logging to Google Sheets**:  
   - The analysis results (freshness, product classification, expiry date) are logged into Google Sheets for easy tracking.
   - The sheet ID can be updated within the code as per the user’s requirements.

5. **Deployment**:  
   The website can be run locally or hosted on any web server. The solution is designed to be responsive and fully functional across devices, ensuring a smooth user experience.

🆔 **OCR-Based Aadhaar Card Text Extraction**
A Google Colab project to extract text from Aadhaar card images containing both Telugu and English languages using Optical Character Recognition (OCR) techniques.


**📚 Project Overview**
This project automates the process of reading and extracting relevant text from Aadhaar card images using pytesseract. The solution focuses on processing JPG files and includes essential image preprocessing steps to improve OCR accuracy.
We selected JPG format for this project as it is:
1.Universally supported.
2.Lightweight and optimized for web and cloud processing.
3.Efficient for direct display in Google Colab without format conversion overhead.


⚙️ Project Pipeline

1. 📤 Image Upload & Validation
Accepts JPG format images for streamlined processing.
Images are read and validated to ensure proper loading for OCR tasks.

2. 🛠️ Image Preprocessing
Converts uploaded images to grayscale.
Prepares the image to enhance text clarity and minimize noise.

3. 🔍 OCR Text Extraction
Utilizes pytesseract to detect and extract text from Aadhaar card images.
Filters out unwanted hyperlinks like www.uidaigov.in for clean, structured results.

4. 🧹 Post-Processing
Cleans extracted text for readability.
Supports both Telugu and English scripts seamlessly.

5. 🖼️ Bounding Box Visualization
Optional step to draw bounding boxes around detected text regions for better visual representation.

6. 💾 Display Output and Save Extracted Text
The extracted text is displayed directly in the notebook output.
The information is saved as a .txt file.

7. 🔗 Create a Download Link
A download link is automatically generated inside the Google Colab notebook.
Users can easily click to download the extracted text file.

🚀 **Features**
Supports bilingual Aadhaar cards (Telugu + English).

Focused on JPG image processing to ensure consistency.

Removes embedded URLs and unwanted hyperlinks.

Displays the extracted text directly.

Saves the extracted information automatically.

Provides a download link for user convenience.

Clean and reusable Google Colab notebook.

🔧 **Technologies Used**

Google Colab

Python 3

pytesseract

OpenCV

PIL

io

📁 **Project Files**
OCR_Adharra_Card.ipynb - Main Colab Notebook with the complete pipeline.

Sample Aadhaar JPG image (user-provided for processing).

Extracted text file (auto-generated for download).

✅ **Prerequisites**

Basic Python knowledge.

Google Colab or Jupyter environment.

Required libraries: pytesseract, opencv-python, PIL

📞** Contact**

Developer: Shiva Bekkam

Mobile: 7993322071

GitHub: https://github.com/BEKKAMSHIVA

Email: shivabekkam7@gmail.com








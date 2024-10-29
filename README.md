# Sensor Image Scratch Detection Web Interface
This repository provides a web interface for detecting scratches in sensor images using a UNET-based model. This project is currently hosted by CERN, and some files are confidential due to project sensitivity.

# Author
#### Abhinav Raj Gupta

# Installation
### To install the required dependencies, use the following command:
     pip install -r requirements.txt
### Setup and Usage
Follow these steps to set up and run the web interface:

### 1. Clone the repository or download the ZIP file:
      git clone <repository-url>
### 2. Navigate to the project directory:
      cd <project-directory>
### 3. Run the application:
      flask run
### 4. Access the web interface:
Open your local web browser and navigate to http://127.0.0.1:5000.
### 5. Upload and Analyze Images:
  - Use the Upload button to select and upload images.
  - Uploaded images are saved in instance/upload/, organized by date and time.
  - The UNET model processes the images, and annotated results are stored in static/, also organized by date and time.
### 6. View and Download Results:
  - Annotated images are displayed on the web interface.
  - Use the Download Label Files button to download the labels as a ZIP file.
### 7. Filter Options:
  - A dropdown menu is available to filter images as needed.

## Note: This repository does not include certain project files due to their confidentiality, as this is part of an official CERN project.

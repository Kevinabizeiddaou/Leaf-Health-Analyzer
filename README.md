# Leaf-Health-Analyzer
This project analyzes leaf images to assess their greenness and plant health by calculating a custom Plant Health Index (PHI) using image processing techniques. It utilizes machine learning algorithms, and relies on OpenCV for color and texture analysis.

### Features
Greenness Calculation: Determines the percentage of green pixels in leaf images using the HSV color space.
PHI Calculation: Calculates the Plant Health Index based on the texture contrast of the leaf image (grayscale contrast).
Automatic Image Processing: The project processes leaf images from mobile devices to automatically output greenness and PHI values.

### Project Structure
.
├── images/                    # Directory for leaf images
├── analysis.py                # Main Python script for analyzing images
└── README.md                  # Project documentation

### Installation
1. Clone the Repository

git clone https://github.com/Kevinabizeiddaou/leaf-health-analyzer.git
cd leaf-health-analyzer

2. Install Dependencies
This project requires the following Python libraries:

OpenCV for image processing
Numpy for numerical operations
You can install them using pip:

pip install opencv-python-headless numpy

3. Running the Code in Colab (optional)
If you're using Google Colab, you can upload your images directly and run the analysis. Here's a small snippet to upload files in Colab:

from google.colab import files
uploaded = files.upload()

4. Running the Analysis
Place your leaf images in the images/ directory and run the following command:

python analysis.py

The script will analyze each image and print out:

Greenness Score: Percentage of green pixels in the image.
PHI: Plant Health Index based on contrast.
Usage Example
To analyze leaf images:


### Future Enhancements

1. Add more metrics for leaf health, such as moisture level estimation.
2. Integrate with a mobile app for real-time analysis in the field.
3. Add more metrics to make this model predict when and how much to water the leaves in need.


### Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.


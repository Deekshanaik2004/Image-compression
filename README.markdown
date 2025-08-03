# Image Compression using K-Means Clustering

This repository contains a Python script to compress an image using the K-Means clustering algorithm.

## Description
The script uses the PIL library to load an image, resizes it, and applies K-Means clustering to reduce the number of colors, thereby compressing the image. The original and compressed images are displayed using matplotlib.

## Requirements
- Python 3.x
- PIL (Python Imaging Library)
- NumPy
- Matplotlib
- scikit-learn

Install the required packages using pip:
```
pip install pillow numpy matplotlib scikit-learn
```

## Usage
1. Place your image file (e.g., `image.jpg`) in the same directory as the script.
2. Update the `Image.open("image.jpg")` line in the script with your image filename if different.
3. Run the script:
   ```
   python image_compression.py
   ```
4. The original and compressed images will be displayed.

## Features
- Resizes the image to 128x128 pixels for processing.
- Allows customization of the number of colors (`n_colors`) in the compressed image.
- Visual comparison of original and compressed images.

## Notes
- Ensure the image file is in a supported format (e.g., JPG, PNG).
- The script uses 4 colors by default; adjust `n_colors` as needed.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
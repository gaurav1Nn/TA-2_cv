# ImageProcessingAssignment

This repository implements three image processing algorithms: RANSAC for outlier removal and transformation model fitting, Harris corner detector, and Shi-Tomasi corner detector. The code is written in Jupyter Notebooks, and outputs are saved as images.

## Algorithms
1. **RANSAC**: Removes outliers and fits a transformation model (`ransac_.ipynb`, outputs: `aero1.jpeg`, `aero2.jpeg`).
2. **Harris Corner Detector**: Detects corners in grayscale images (`Harris.ipynb`, output: `building.jpeg`).
3. **Shi-Tomasi Corner Detector**: Identifies corner points (`shi_tomasi.ipynb`, output: `img1_corners.jpeg`).

## Repository Structure
- `Harris.ipynb`, `ransac.ipynb`, `shi_tomasi.ipynb`: Code files.
- `harris_corners.png`, `ransac1.png`, `ransac2.png`, `shi_tomasi_corners.jpg`: Output images.
- `README.md`: This file.

## How to Run
1. Clone: `https://github.com/gaurav1Nn/TA-2_cv.git`
2. Install: `pip install opencv-python numpy matplotlib`
3. Run the notebooks in Jupyter.

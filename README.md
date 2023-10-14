# Image Compression using Principal Component Analysis (PCA)

This script demonstrates how to perform image compression using Principal Component Analysis (PCA) in Python. It uses the scikit-learn library for PCA and OpenCV for image processing.

## Installation

To run the script, you need to have the following dependencies installed:

- Python (version 3 or higher)
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- OpenCV
- 
## Usage

1. Clone the repository: `git clone https://github.com/PassantAdel/Image_Colorization.git`
2. Open the script in a Python environment or Jupyter Notebook.
3. Run the script to see the image compression results.

## Description

The script performs the following operations:

- Loads an image and adds random noise to it.
- Splits the image into its three color channels (Red, Green, Blue).
- Applies PCA on each channel to reduce the dimensions.
- Merges the reduced channels to reconstruct the compressed image.
- Computes and prints the rate of compression achieved.

## Results

The script achieves a compression rate of approximately 89.45%.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

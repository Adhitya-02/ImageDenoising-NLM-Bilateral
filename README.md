# Image Quality Enhancement: NLM and Bilateral Filtering

## Project Overview
This project is focused on enhancing the quality of digital images through advanced denoising techniques. It specifically utilizes Non-Local Means (NLM) and Bilateral Filtering methods to reduce noise and improve the visual clarity of images. Additionally, the project includes functionality to calculate the Peak Signal-to-Noise Ratio (PSNR) to quantitatively assess the enhancement in image quality.

## Features
- **Non-Local Means Denoising**: Applies NLM algorithm to effectively reduce noise while preserving image details.
- **Bilateral Filtering**: Further refines the denoised image by smoothing it and preserving edges.
- **PSNR Calculation**: Computes the PSNR between the original and denoised images to evaluate the improvement in quality.

## Installation
To run this project, you will need to install several Python libraries. You can install these dependencies via pip:
```bash
pip install numpy matplotlib opencv-python scikit-image

## Usage
To use this project:
1. **Load Images**: Start by loading the original and noisy images into the program. Replace `'original.jpg'` and `'noise3.jpg'` with the paths to your images.
2. **Run Denoising Process**: The script will automatically apply Non-Local Means Denoising followed by Bilateral Filtering to the noisy image.
3. **View Results**: After the denoising process, the script will display the original, noisy, and denoised images side by side. It will also print out the PSNR values to compare the quality of the original and denoised images.
Feel free to modify the parameters used in the denoising functions to see how they affect the output.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


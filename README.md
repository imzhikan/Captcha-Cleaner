# Image Processing & Computer Vision Projects

This repository contains a collection of computer vision and image processing projects implemented using Python, OpenCV, and PyTorch.

## 📁 Project Structure

```
├── captcha_main.ipynb           # Main CAPTCHA processing pipeline
├── sample_captchas/             # Sample CAPTCHA images for testing
└── processed_captcha_images/    # Output folder for processed images
```

## 🚀 Features

### CAPTCHA Detection & Processing
- Grayscale conversion
- Gaussian blur filtering
- Adaptive thresholding
- Morphological operations (opening/closing)
- Edge detection using Canny
- Line detection using Hough Transform
- Image segmentation and character extraction

## 📋 Requirements

All required packages are listed in `requirements.txt`. Install them using following command:

```bash
pip install -r requirements.txt
```

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd project3
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:
```bash
jupyter notebook
```

## 💻 Usage

### CAPTCHA Processing
1. Open `captcha_main.ipynb`
2. Place your CAPTCHA images in the `sample_captchas/` folder
3. Run the cells sequentially to process the images

## 🔍 CAPTCHA Processing Pipeline

1. **Load Images**: Read CAPTCHA images from `sample_captchas/` folder
2. **Grayscale Conversion**: Convert RGB images to grayscale
3. **Border Addition**: Add replicated borders to images
4. **Thresholding**: Apply Otsu's binarization
5. **Morphological Operations**: Remove noise using opening and closing
6. **Edge Detection**: Detect edges using Canny edge detector
7. **Line Detection**: Find lines using Hough Line Transform
8. **Visualization**: Display results using Matplotlib

## 📊 Technologies Used

- **Python 3.x**
- **OpenCV**: Image processing and computer vision
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **PyTorch**: Deep learning framework
- **Tkinter**: GUI development
- **imutils**: Convenience functions for OpenCV

## 📝 Notes

- The project uses relative paths for image folders
- Processed images are saved in `processed_captcha_images/` directory
- For driver drowsiness detection, ensure proper lighting conditions
- CAPTCHA processing works best with clear, high-contrast images

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## 📄 License

This project is open source and available under the MIT License.

---

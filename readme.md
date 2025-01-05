# Image Angle Calculator

A Python tool that allows users to measure multiple angles on an image by clicking three points at a time.

## Features
- Measure unlimited angles on a single image
- Each angle measurement is numbered and preserved
- Real-time visualization with lines and angle values
- Easy reset functionality

## Requirements
- Python 3.x
- OpenCV (`opencv-python`)
- NumPy (`numpy`)

## Installation
```bash
pip install opencv-python numpy
```

## Usage
1. Replace `'your_image_path.jpg'` in the code with your image path
2. Run the program:
   ```bash
   python angle_calculator.py
   ```
3. Click any three points to measure an angle
4. Controls:
   - Left click: Place points
   - 'r' key: Reset all measurements
   - 'q' key: Quit program

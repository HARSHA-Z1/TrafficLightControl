# Smart Traffic Light Control System Using Image Processing

## Table of Contents
- [Introduction](#introduction)
- [Project Scope](#project-scope)
- [Project Features](#project-features)
- [System Analysis](#system-analysis)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Results](#results)
- [Contributors](#contributors)
- [Future Scope](#future-scope)

## Introduction
The **Smart Traffic Light Control System** is designed to enhance road traffic management using image processing techniques. By leveraging methods such as **Canny Edge Detection**, this system aims to optimize traffic flow in real-time by analyzing images to dynamically adjust traffic light signals.

## Project Scope
This project seeks to develop a machine learning model that efficiently analyzes traffic patterns through high-resolution camera images. This system overcomes traditional traffic detection challenges such as shadows, obstructions, and lighting variations to provide more accurate traffic management solutions.

## Project Features
- **Image Processing**: Advanced preprocessing techniques to filter noise and prepare images.
- **Edge Detection**: Utilizing Canny Edge Detection for accurate boundary identification.
- **Dynamic Signal Timing**: Calculation of green signal duration based on detected traffic density.
- **Pixel Analysis**: Counting white pixels in preprocessed images to estimate vehicle density.

## System Analysis
### Problem Definition
Traditional traffic management techniques struggle with complex urban conditions, such as varying light, shadows, and physical obstructions. This project integrates machine learning and image processing for robust traffic flow analysis and control.

### Proposed Solution
The proposed system applies Canny Edge Detection combined with contextual image analysis to extract meaningful data from high-resolution traffic images, addressing existing limitations and enhancing prediction accuracy.

## Architecture
### Project Workflow:
1. **Image Upload**: Upload traffic images for analysis.
2. **Preprocessing**: Apply noise reduction and edge detection (e.g., Gaussian filters, Sobel filters).
3. **Analysis**: Extract pixel data and determine traffic density.
4. **Green Signal Calculation**: Allocate green signal time based on pixel count.

![Project Architecture](path/to/architecture-diagram.png)

## Technologies Used
- **Programming Language**: Python (3.7)
- **Libraries/Frameworks**: OpenCV, NumPy, Matplotlib, Scipy
- **Operating System**: Windows 8 or above

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TrafficLightControl.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main program:
   ```bash
   python main.py
   ```

## Usage
1. **Upload Traffic Image**: Load images for traffic analysis.
2. **Preprocess the Image**: Prepare and filter the image for processing.
3. **Run Analysis**: Execute the model to detect edges and count white pixels.
4. **Green Signal Allocation**: View the calculated green signal time based on traffic density.

## Testing
### Types of Testing Performed:
- **Manual Testing**: Verification using various image types (valid and invalid).
- **Functional Testing**: Ensure accurate prediction and error handling.

### Sample Test Cases:
- **Image Upload Test**:
  - **Input**: Valid traffic image.
  - **Expected Output**: Successful upload and processing.
- **Prediction Test**:
  - **Input**: Preprocessed image.
  - **Expected Output**: Accurate green signal duration estimation.

## Results
The system successfully estimates traffic congestion and adjusts signal timing dynamically, optimizing the flow and reducing wait times at intersections.

## Contributors
- **S. Harsha Vardhan** (217R1A05Q9)
- **Joel Emmanuel** (217R1A05N2)

Guided by **Dr. N. Bhaskar**.

## Future Scope
Enhancements may include:
- Integration with IoT devices and smart sensors for real-time data collection.
- Advanced techniques like **Gaussian Smoothing** and **Non-Maximum Suppression** for better edge detection.
- Implementation of **Vehicle-to-Infrastructure (V2I)** communication for improved traffic management.

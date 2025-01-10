YOLOv8: Object Detection and Classification
Overview
This project explores the integration of HSV color space conversion with the YOLOv8 model to enhance apple detection, maturity assessment, and weight estimation in natural environments. By employing advanced image processing and detection techniques, this project aims to address challenges such as shading, lighting variations, and differences in fruit characteristics.
Features
Apple Detection: Identify the number and locations of apples using the YOLOv8 model.
Maturity Assessment: Evaluate apple maturity based on HSV and RGB color values.
Weight Estimation: Estimate apple weight through 3D modeling.
Accuracy Enhancement: Achieve high detection accuracy in complex backgrounds.
Installation
1.Clone the repository: 
git clone <repository-url>
cd yolov8-8.3.49
2.
3.Install required dependencies: 
pip install -r requirements.txt
4.
File Structure
.
├── detect.py         # Main script for object detection
├── data.yaml         # Dataset configuration file
├── yolo8x.pt         # Pretrained model weights
├── data/             # Folder containing training and validation images
├── requirements.txt  # Python dependencies
├── LICENSE           # License file
└── README.md         # Project documentation
Methodology
Data Collection and Preprocessing
Collected apple image data in natural environments.
Applied grayscale conversion and Gaussian filtering for noise reduction.
Edge Detection
Utilized Canny and Sobel algorithms for edge detection.
Detected apple count using the YOLOv8 model.
Maturity Assessment
Assessed apple maturity based on HSV and RGB color values.
Weight Estimation
Estimated weight by constructing 3D models of apples.
Apple Detection
Precisely identified apples among various fruits using color feature extraction and the YOLOv8 model.
Reproducibility
1.Follow the installation steps.
2.Configure the dataset using the data.yaml file.
3.Run the detect.py script.
Keywords
Natural environment
Apple estimation
Apple detection
Color space conversion
YOLOv8

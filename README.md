# Brain-Tumor-Segmentation---UNet
## Overview
This repository contains an implementation of the U-Net architecture for brain tumor segmentation using a dataset of MRI images. The dataset features 3064 pairs of T1-weighted contrast-enhanced images and their corresponding binary masks, indicating the presence of tumors.
## Dataset
Source: Brain Tumor Dataset on Figshare
Size: 838.77 MB
Image Format: MRI images in .mat format, converted to .jpg using provided MATLAB scripts.
Types of Tumors: The dataset includes three different types of brain tumors.
## Requirements
Python 3.x
TensorFlow (>=2.0)
Keras
NumPy
OpenCV
Matplotlib
## Installation
1. Clone this repository:
   git clone https://github.com/yourusername/brain-tumor-segmentation.git
   cd brain-tumor-segmentation
2. Install the required packages:
   pip install -r requirements.txt
## U-Net Model
The U-Net model is defined in model.py. Here’s a brief overview of the architecture:

Encoder: Consists of convolutional layers followed by max pooling to downsample the input.
Bottleneck: The deepest layer where feature extraction is maximized.
Decoder: Upsamples the feature maps and concatenates them with corresponding encoder layers to recover spatial information.
## License
This project is licensed under the CC BY 4.0 License.
## Acknowledgments
Dataset provided by Jun Cheng.
Inspired by the U-Net architecture for biomedical image segmentation.
## Contact
For any inquiries, please reach out to kholoud.anran96@gmail.com





# Advanced Deep Learning Framework for Secure Transmission of Sensitive Images in War Scenarios

## Overview  
This project presents a deep learning-based framework for the **secure transmission of sensitive images** in scenarios related to **national security**, such as war and border protection. The framework ensures the **confidentiality** and **integrity** of transmitted images by using advanced encoding and decoding techniques. It employs **Least Significant Bit (LSB) Steganography** and state-of-the-art deep learning models such as **ResNet50**, **VGG16**, and **Inception_v3** for image encoding and decoding.

The framework is designed to safeguard sensitive image data, minimize data corruption, and ensure lossless decoding, making it a valuable tool for critical national security applications.

---

## Features  
- **Deep Learning-Based Encoding**: Securely encode sensitive images using advanced architectures (e.g., ResNet50, VGG16).  
- **LSB Steganography**: Used for decoding the encoded images with high accuracy.  
- **Data Integrity Validation**: Comparison between original and decoded images to ensure minimal loss or corruption during transmission.  
- **Secure Transmission Pipeline**: Focused on protecting data confidentiality and integrity in national security scenarios.  
- **Experimental Validation**: Extensive experiments demonstrate the framework's effectiveness in secure image transmission.

---

## Dataset  
This project uses the **Ukraine War Images** dataset available on Kaggle. You can access it here:  
[Ukraine War Images Dataset](https://www.kaggle.com/datasets/mathurinache/ukraine-war-images)  

---

## Technologies and Tools  
- **Deep Learning Models**: ResNet50, VGG16, Inception_v3  
- **Programming Language**: Python  
- **Steganography Technique**: Least Significant Bit (LSB)  
- **Libraries and Frameworks**:  
  - TensorFlow / PyTorch  
  - NumPy  
  - OpenCV  
  - Scikit-learn  
  - Matplotlib (for visualizations)  

---

## Getting Started  

### Prerequisites  
Ensure you have the following installed on your system:  
- Python 3.8 or higher  
- pip (Python package manager)  
- A GPU with CUDA support (optional but recommended for training models)  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/secure-image-transmission.git  
   cd secure-image-transmission  
pip install -r requirements.txt  
python encode.py --input <path_to_image> --output <output_encoded_file>  
python decode.py --input <encoded_file> --output <decoded_image_path>  
python validate.py --original <path_to_original_image> --decoded <path_to_decoded_image>  

# Experimental Results  
The framework has been tested extensively, and results indicate:  

- **High Accuracy**: Maintains image integrity with minimal data loss.  
- **Robust Transmission**: Effective even in scenarios with potential data corruption.  
- **Validation Metrics**: Structural Similarity Index (SSIM) and Mean Squared Error (MSE) confirm data quality preservation.  

For detailed results, see the `docs/` folder.  

---

# Folder Structure  
 
secure-image-transmission/  
├── data/                 # Sample datasets and images  
├── models/               # Pre-trained model weights and architectures  
├── src/                  # Source code for encoding, decoding, and validation  
├── docs/                 # Project report and presentation  
├── results/              # Experimental results and analysis  
├── requirements.txt      # Dependencies  
└── README.md             # Project documentation  

# Contributors  
- **Deheem U Deyar** (Primary Author, deheembhat9@gmail.com)  
- **Anirud Ramani**  (Primary Author, anirud25@gmail.com)
- **Dr. Suja P**  

---

# Copyright and Usage Notice
© [2024], [Deheem U Deyar, Anirud Ramani]. All rights reserved.

This repository contains original work created as part of an academic project at [Amrita Vishwa Vidyapeetham, Bengaluru]. The project report, presentation slides, source code, and all associated documents (including the IEEE-style paper) are protected under copyright law.

No part of this repository may be copied, modified, distributed, or published (in whole or in part) without explicit written permission from the original authors. Unauthorized use, including but not limited to re-publication under a different name or affiliation, is strictly prohibited and may lead to legal or disciplinary action.

This repository is shared for academic review and learning purposes only. 

---

# License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

If you have further questions, feel free to contact the authors **Deheem U Deyar** at **deheembhat9@gmail.com**, **Anirud Ramani**  at **anirud25@gmail.com**.  

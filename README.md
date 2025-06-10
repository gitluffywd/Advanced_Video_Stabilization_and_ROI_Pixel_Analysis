# Advanced Video Stabilization and ROI Pixel Analysis

## 📚 Introduction

My name is **Stefano Caramagno**, and I'm pleased to present this repository containing a project on creation of a **advanced video stabilization and ROI pixel analysis** tool. <br>
This project was completed as part of the **Digital Forensics** course during my **Bachelor's Degree in Computer Science and Engineerin** at the **University of Catania**.

## ✨ Features

- **Advanced Video Stabilization**: Reduces unwanted camera movements using motion smoothing techniques to ensure a smoother video output.  
- **Moving Average Smoothing**: Applies a moving average filter to smooth the transformation parameters, improving video stabilization results.  
- **Optical Flow Tracking**: Estimates affine transformations using optical flow to track key points across consecutive video frames.  
- **ROI Selection**: Allows users to define a Region of Interest (ROI) for pixel analysis and further in-depth examination.  
- **Pixel Intensity Analysis**: Computes the average pixel intensity in the selected ROI across multiple frames for accurate evaluation.  
- **Edge Correction**: Corrects video borders automatically after stabilization to prevent unwanted black margins.  
- **Affine Transformation Calculation**: Extracts translation and rotation components for frame alignment and video correction.  
- **Frame Pair Comparison**: Displays side-by-side comparisons of original and stabilized frames for quality assessment.  
- **Automatic ROI Processing**: Detects and processes pixel variations within the user-selected region for deeper insights.  
- **Automated Batch Processing**: Iterates through all video frames to apply transformations efficiently and consistently.  
- **Dynamic Video Adjustment**: Limits frames automatically to ensure optimal analysis without causing artifacts. 
- **Report Generation**: Produces an HTML report showing a comparison between the original and stabilized frames.  
- **Stabilized Video Output**: Saves the stabilized video as a separate file for further analysis and playback.  

## 🛠️ Tech Stack

- **Programming Language**: Python for implementing video processing and computer vision tasks.
- **Relevant Libraries**: 
  - **NumPy** for efficient numerical operations and data manipulation.    
  - **OpenCV** for advanced image processing and computer vision tasks.  
- **Dependency Management**: Pip for installing and managing project dependencies.  
- **IDE**: Visual Studio Code for development and debugging.  
- **Version Control**: Git for tracking changes and managing project versions.  
- **Repository Hosting**: GitHub for storing, sharing, and maintaining the project repository.  

## 🚀 Getting Started

### Prerequisites

Ensure you have the following tools installed on your system before proceeding:

- **Python**: Version 3.9 or later, required to run the script.  
- **Required Libraries**: Install the following libraries using `pip` from the terminal:
  - **NumPy**: Required for numerical operations and data manipulation.
  - **OpenCV** : Required for image processing and computer vision tasks.
- **Pip**: Used to install required dependencies. 
- **IDE**: Required to read and understand code efficiently.  
- **Git**: Used to clone the repository. 

### Installation Steps

1. **Clone the Repository**

   To download the repository and navigate to its directory:

   ```sh
   git clone https://github.com/stefanocaramagno/Advanced_Video_Stabilization_and_ROI_Pixel_Analysis.git
   cd Advanced_Video_Stabilization_and_ROI_Pixel_Analysis
   ```

2. **Install Dependencies**

   To install all required dependencies:

   ```sh
   pip install numpy opencv-python
   ```

3. **Prepare Input Data**

   Place your video file in the project directory and name it `video_originale.mp4`. <br>
   Ensure the video is accessible and properly formatted.

### Running the Application

1. **Run the Script**

   To execute the script:

   ```sh
   python stabilization_and_ROI_pixel_analysis.py
   ```

2. **Follow the On-Screen Instructions**

   During the execution, you will be prompted to select a Region of Interest (ROI) for pixel analysis.

3. **View the Results**

   The outputs will be generated in the same directory:
   - Stabilized video: `video_stabilizzato.mp4`
   - Average pixel image: `foto_media.jpg`
   - HTML report: `report.html`

##  🌐 Connect with Me

Feel free to explore my professional journey, check out my projects, or get in touch through the following platforms:

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:stefano.caramagno@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%2300A36C?style=for-the-badge&logo=buffer&logoColor=white)](https://stefanocaramagno.vercel.app)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stefanocaramagno)
[![Indeed](https://img.shields.io/badge/Indeed-%2300A4CC?style=for-the-badge&logo=indeed&logoColor=white)](https://profile.indeed.com/p/stefanoc-4cl1mmq)
[![GitHub](https://img.shields.io/badge/GitHub-%232F2F2F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/stefanocaramagno)
[![YouTube](https://img.shields.io/badge/YouTube-D14836?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@stefanocaramagno)

## ⚖️ License

© **Stefano Caramagno**

**Personal and Educational Use Only**  
All content in this repository is provided for personal and educational purposes only. <br>
Unauthorized actions without explicit permission from the author are prohibited, including but not limited to:

- **Commercial Use**: Using any part of the content for commercial purposes.
- **Distribution**: Sharing or distributing the content to third parties.
- **Modification**: Altering, transforming, or building upon the content.
- **Resale**: Selling or licensing the content or any derivatives.

For permissions beyond the scope of this license, please contact the author.

**Disclaimer**  
The content is provided "*as is*" without warranty of any kind, express or implied. <br>
The author shall not be liable for any claims, damages, or other liabilities arising from its use.
# Pose Estimation with RTMO

A real-time human pose estimation system using the RTMO (Real-Time Multi-Person Pose Estimation) model. This project processes video input to detect and visualize human poses with high accuracy and performance.

### 📁 Project Structure

RTMO_pose_estimation\
├── src\
│   ├── rtmo_pose.ipynb                  \
├── data/\
│   ├── test.mp4                        \
│   └── test_pose_data.npz               \
├── outputs/\
│   └── test_pose_estimation.mp4         \
├── requirements.txt             \
├── LICENSE                     \
└── README.md                   

# 🚀 Features
+ Real-time multi-person pose estimation

+ High accuracy keypoint detection

+ Efficient video processing pipeline

+ Visualization of pose skeletons and keypoints

+ Export capabilities for processed data

# 🛠️ Installation
### Prerequisites
* Python 3.8 or higher

* pip (Python package manager)

# Setup
## 1. Clone the repository:


git clone https://github.com/zubitech-AI/RTMO_pose_estimation.git \
cd RTMO_pose_estimation
## 2. Create and activate a virtual environment (recommended):


### For Windows
+ python -m venv pose-env 
+ pose-env\Scripts\activate
## 3. Install dependencies:
+ pip install -r requirements.txt
# 📋 Requirements
The project requires the following Python packages:

+ numpy>=1.21.0
+ opencv-python>=4.5.0
+ tensorflow>=2.8.0
+ matplotlib>=3.5.0
+ jupyter>=1.0.0
+ scikit-learn>=1.0.0
+ tqdm>=4.62.0
#  🎯 Usage
## Jupyter Notebook
### 1. Launch Jupyter Notebook:

+ jupyter notebook
### 2. Open and run src/rtmo_pose.ipynb

### 3. The notebook will:

- Process data/test.mp4

- Generate pose estimation data

- Create output video in outputs/test_pose_estimation.mp4

- Save processed data to data/test_pose_data.npz

## Command Line Interface
Alternatively, you can use the Python module:


+ python src/pose_estimator.py --input data/test.mp4 --output outputs/result.mp4
Available command line arguments:

+ --input: Path to input video file

+ --output: Path to save output video

+ --model: Path to model file (default: models/rtmo_model.h5)

+ --confidence: Confidence threshold (default: 0.5)

# 📊 Results
The output includes:

+ Video with visualized pose skeletons

+ Keypoint data stored in NPZ format

+ Performance metrics (FPS, accuracy)

# 🔧 Customization
You can modify the following parameters in the code:

+ Confidence threshold for detection

+ Keypoint connections and visualization colors

+ Output video resolution and quality

+ Processing batch size for optimization

# 🤝 Contributing
We welcome contributions! Please feel free to submit pull requests, report bugs, or suggest new features.

1. Fork the project

2. Create your feature branch (git checkout -b feature/AmazingFeature)

3. Commit your changes (git commit -m 'Add some AmazingFeature')

4. Push to the branch (git push origin feature/AmazingFeature)

5. Open a pull request

# 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

# 🙏 Acknowledgments
+ RTMO model authors and contributors

+ OpenCV community for excellent computer vision tools

+ TensorFlow team for deep learning framework

# 📞 Support
Need Help or Want to Work With Me?
For:

✅ Source code access

✅ Project setup assistance

✅ Custom web apps or websites

✅ Custom mobile applications

✅ AI projects, chatbot solutions, and more

✅ College/university assignments and coding tasks

👉 Contact Me Directly:

📱 WhatsApp: ‪+92 308  4737171‬\
📷 Instagram: @ur_zubi\
📧 Email: zubitech906@gmail.com

💬 I usually respond within a few hours. Let's build something great together!

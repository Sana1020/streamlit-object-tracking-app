# 🎯 Object Tracking Application

A real-time object tracking application built with Streamlit and OpenCV that detects and tracks moving objects in video files using background subtraction techniques.

---

## 📋 Purpose of the Project

This project aims to provide an easy-to-use, interactive web application for detecting and tracking moving objects in video files. It leverages computer vision techniques to identify motion in videos, making it useful for surveillance analysis, motion detection, traffic monitoring, and educational purposes in computer vision.

---

## 🎯 Problem We're Trying to Solve

Traditional object tracking and motion detection often requires:
- Complex setup and configuration
- Technical knowledge of computer vision libraries
- Command-line interfaces that aren't user-friendly
- Lack of real-time visualization

**This project solves these issues by:**
- Providing a simple, intuitive web interface
- Enabling drag-and-drop video uploads
- Displaying original and processed frames side-by-side for easy comparison
- Allowing customization of detection parameters (color, playback speed)
- Making computer vision accessible to non-technical users

---

## 🚀 How to Use This Project

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ahmedaliziada/Oject_tracking.git
   cd Oject_tracking
   ```

2. **Install required dependencies**
   ```bash
   pip install streamlit opencv-python numpy
   ```

### Running the Application

1. **Start the Streamlit app**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser**
   - The app will automatically open at `http://localhost:8501`
   - If it doesn't open automatically, navigate to the URL shown in your terminal

### Using the Application

1. **Upload a video file** (supported formats: mp4, avi, mov)
2. **Customize settings** in the sidebar:
   - Choose detection box color
   - Adjust playback speed (1-60 fps)
3. **View results**:
   - Left panel: Original video frames
   - Right panel: Detected moving objects (foreground mask)
   - Progress bar shows processing status

---

## 🛠️ Used Technologies

### Core Technologies
- **Python** - Primary programming language
- **Streamlit** - Web application framework for creating interactive UI
- **OpenCV (cv2)** - Computer vision library for video processing and object detection
- **NumPy** - Numerical computing for array operations

### Key Techniques
- **Background Subtraction (MOG2)** - Motion detection algorithm that separates moving objects from static background
- **Contour Detection** - Identifies boundaries of detected objects
- **Bounding Box Visualization** - Draws rectangles around tracked objects

### Features
- Real-time video processing
- Side-by-side comparison view
- Customizable detection parameters
- Progress tracking
- Color picker for visualization
- Responsive web interface

---

## 🔮 Future Work

### Planned Enhancements

1. **Advanced Tracking Algorithms**
   - Implement YOLO or SSD for better object detection
   - Add support for specific object class detection (people, cars, animals)
   - Multi-object tracking with unique IDs

2. **Enhanced Features**
   - Real-time webcam support
   - Export processed videos
   - Frame-by-frame analysis mode
   - Object counting and statistics
   - Heat maps for motion density

3. **Performance Improvements**
   - GPU acceleration support
   - Batch processing for multiple videos
   - Optimization for larger video files
   - Caching mechanisms

4. **User Experience**
   - Save and load detection configurations
   - Video trimming before processing
   - Region of Interest (ROI) selection
   - Download detection reports (CSV/JSON)

5. **Advanced Analytics**
   - Object trajectory tracking
   - Speed estimation of moving objects
   - Time-based analytics dashboard
   - Alert system for specific detection patterns

6. **Deployment**
   - Docker containerization
   - Cloud deployment (AWS, Azure, or Heroku)
   - Mobile-responsive design improvements
   - API endpoint for programmatic access

---

## 📝 License

This project is open-source and available for educational and personal use.



## 🙏 Acknowledgments

- OpenCV community for excellent documentation
- Streamlit team for the amazing framework
- Computer vision researchers for background subtraction algorithms

---

<div align="center">
Made with ❤️ using Streamlit & OpenCV | 2025
</div>

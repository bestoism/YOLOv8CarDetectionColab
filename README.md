# YOLOv8-Car-Detection-Colab

A simple Google Colab notebook for detecting cars in videos using YOLOv8 and OpenCV, with automatic video annotation and result export.

🎥 [Watch Demo Video on YouTube](https://youtu.be/K6xsEng2PhU)

## Features
- Upload your own video and detect cars frame by frame
- Annotated video output is automatically saved and downloadable
- Uses YOLOv8 and OpenCV for detection and processing

## How to Use

1. **Open the Notebook**  
   Upload `Cardetection.ipynb` to [Google Colab](https://colab.research.google.com/) or open it from your Google Drive.

2. **Install Dependencies**  
   Run the first cell to install required libraries (`ultralytics`, `opencv-python-headless`, etc).

3. **Load YOLOv8 Model**  
   Run the cell that loads the YOLOv8 model.

4. **Upload Your Video**  
   Run the cell with `files.upload()` and select your video file (e.g., `car-video.mp4`).

5. **Process the Video**  
   Run the cell that processes the video. The notebook will detect cars in each frame and save the annotated video as `hasil_deteksi.mp4`.

6. **Download the Result**  
   After processing, download the result video using the provided download link.  
   👉 If you're viewing the video file in the GitHub repository, click the **"Download"** or **"View raw"** button at the top right to download the `.mp4` file.

## Requirements
- Python 3.x
- ultralytics
- opencv-python-headless
- matplotlib
- numpy

All dependencies are installed automatically in the notebook.



🚗 Car Counter Using YOLO and Computer Vision 🚗

Welcome to my Car Counter project! This repository contains the code for a computer vision project that tracks and counts cars (and other vehicles) using YOLOv8, OpenCV, and cvzone. The project showcases how to use object detection models in real-world scenarios like traffic monitoring.

🎥 Demo Video
Curious to see it in action? Check out the demo video on LinkedIn where I explain how the project works: https://www.linkedin.com/feed/update/urn:li:activity:7230826639268438016/


🚀 Project Overview
This project uses the YOLOv8 model to detect vehicles in a video stream and count them as they cross a predefined line. It’s a simple yet powerful example of applying deep learning and artificial intelligence in computer vision.

Features
Vehicle Detection: Detects cars, buses, trucks, and motorbikes with high accuracy.
Tracking: Uses the SORT algorithm for tracking detected vehicles.
Counting: Counts vehicles as they pass through a defined region in the video.

🛠️ Installation and Setup
Clone this repository.
Install the required Python packages.
Download the YOLOv8 model weights.
Place the mask.png and graphics.png files in the root directory of the project.
🔄 Running the Project
Run the Python script.
The program will process the video (cars.mp4) and display the vehicle detection and counting in real-time.
Press q to stop the program.

🧠 How It Works
Masking: A mask image is used to focus the detection on a specific area of the video frame.
Detection: YOLOv8 detects objects in the masked region.
Tracking: The SORT algorithm tracks detected vehicles across frames.
Counting: Vehicles are counted when they cross a predefined line in the frame.


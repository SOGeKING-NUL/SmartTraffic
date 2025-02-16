# SmartTraffic

SmartTraffic is a cutting-edge machine learning project designed to enhance real-time traffic monitoring and analysis. It leverages advanced object detection and tracking techniques to provide insights into vehicle flow, congestion, and lane usage—all in real time. 🚦🚗

---

## Key Features

- **Real-Time Object Detection** 🔍  
  Utilizes YOLOv8 to accurately detect vehicles like cars, buses, trucks, and motorcycles in each frame.

- **Robust Object Tracking** 🔄  
  Employs BYTETracker to maintain consistent vehicle identities across frames, ensuring smooth and reliable tracking.

- **Dynamic Annotations** ✏️  
  Annotates video streams with bounding boxes, labels, and trace lines to visualize vehicle trajectories and crossing events.

- **Virtual Line Monitoring** 📏  
  Implements a configurable virtual line to count vehicles and analyze traffic patterns as they cross a defined boundary.

- **Flexible Video Input** 🎥  
  Supports both live webcam feeds and recorded video files, making it adaptable to various deployment scenarios.

---


![vehicle_annotated_result](https://github.com/user-attachments/assets/19dab802-94ab-4a57-9201-35ecf5c35180)


## How It Works

1. **Capture Video Frames**  
   Frames are captured either from a live webcam or a video file, enabling real-time analysis. 📸

2. **Vehicle Detection & Tracking**  
   YOLOv8 performs detection on each frame while BYTETracker ensures that vehicles are tracked consistently as they move through the scene. 🚗➡️🚙

3. **Annotation & Analysis**  
   Detected vehicles are annotated with bounding boxes, labels, and movement traces. A virtual line aids in counting vehicles and understanding traffic flow. 📊

4. **Real-Time Visualization**  
   The processed and annotated frames are displayed in real time, providing immediate visual feedback and actionable insights. 👀

---

SmartTraffic is a dynamic, interactive solution for modern traffic management challenges. Dive in, explore its capabilities, and tailor it to meet your specific needs. Happy coding! 😊🚀

**AI POWERED ANNOTATION TOOL FOR ADAS TRAINING**

This project showcases a deep learning powered object detection system built to identify and label vehicles, pedestrians and traffic lights in complex urban traffic environments. Developed using python and hosted on Google Colab, the system supports detection across various media formats like single images, video. With a focus on ease of use , it features a clean and user-friendly interface making it accessible for both practical and experimentation application.

**PROJECT OVERVIEW:**

As cities evolve into smarter and more connected ecosystems, the ability to accurately monitor and interpret traffic in real time has become a key component in managing urban mobility. This project addresses that need by implementing an object detection system for urban traffic analysis.

Built using powerful pre trained models such as YOLOv5 and SSD and trained on the well known COCO dataset, the system can reliably detect and label common elements found in real world traffic scenarios including :

- **CARS -** Identifies standard passenger vehicles on the road
- **BUSES -** Recognizes larger public transport vehicles across lanes
- **PEDESTRIANS -** Detects individuals crossing or walking near traffic zones
- **TRAFFIC LIGHTS -** Spots signal lights

**KEY FEATURES:**

- MULTI FORMAT DETECTION - Easily run on object detection on single image, folder of images or video files. It is very flexible and efficient for any use case.
- ADJUSTABLE CONFIDENCE THRESHOLD – Fine tune the model’s sensitivity with confidence slider , giving full control over detection accuracy versus noise.
- REAL TIME VISUALIZATION – Get instant visual feedback with real time previews and detection results, making the process intuitive and responsive.
- BUILT ON PROVEN ARCHITECTURE – Powered by cutting edge object detection models like YOLOv5 and SSD ensuring fast, accurate and reliable performance.
- INTERACTIVE USER INTERFACE – A user friendly sidebar interface provides toggle options, adjust settings and manage inputs.

**TOOLS & TECHNOLOGIES USED:**

| **TOOLS / LIBRARY** | **PURPOSE** |
| --- | --- |
| Python | Core programming language used to build and tie everything together. |
| OpenCV | Handles images and video processing tasks from reading frames to drawing bounding boxes. |
| PyTorch / TensorFlow | Used to run and fine tune detection models. |
| Streamlit | Adds simple and clean web based interface for interacting with the tool. |
| YOLO / SSD | Used to identify the vehicles, pedestrians and traffic signals. |
| Google Colab | Cloud based environment for writing, testing and running code with GPU support. No local set up needed |

**HOW TO USE ?**

- **STEP 1 – OPEN IN GOOGLE COLAB**

Start by opening the provided notebook link in Google Colab. No installations needed, everything runs in the cloud.

- **STEP 2 – UPLOAD MEDIA**

Use the sidebar to select the input type like single image, folder of images or video file.

- **STEP 3 – SET CONFIDENCE THRESHOLD**

Use the sidebar to adjust how the confident the model should be before labelling the objects. A higher value gives more precise results.

- **STEP 4 – RUN THE DEETCTION**

Hit “_Run All”_ to execute the results the entire notebook or run each cell step by step. The model will process the input and display the results in real-time.

**FUTURE WORK :**

- **REAL TIME WEB CAM DETECTION –** enhance the system to support live object detection using webcam enabling on the fly analysis without needing pre recorded media.
- **MOBILE FRIENDLY VERSION –** Optimize the interface and processing pipeline for mobile devices, making it accessible and functional on the go.
- **INTEGRATION WITH TRAFFIC SYSTEMS –** Connect the detection system with real world traffic management platforms to support smarter signal control and incident monitoring
- **PUBLIC DEPLOYMNET –** Host the entire solution using the streamlit or flask allowing the users to access and interact with the tool through a public web interface

**AUTHOR:**

This project was proudly built by a passionate group of developers , working together under the name **AIVERSE**

**TEAM MEMBERS:**

- **TEAM LEADER :** DHARSHINI R
- **TEAM MEMBER 1:** SUDHIKSHA M K
- **TEAM MEMBER 2:** VIBHOOSHANA K

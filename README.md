<p align="center"><img width=60% src="https://i.imgur.com/ZdcxVrn.png"></p>
<p align="center"><font size="6">Reference Applications</font></p>

### Table of Contents
* [Starter Apps](#starter-apps) 
* [NVIDIA Apps](#nvidia-apps) 
* [Camera Apps](#camera-apps) 
* [Streaming Apps](#streaming-apps) 
* [Example Apps](#example-apps)

## Starter Apps :green_book:

| App | Description |
| --- | ----------- |
| [Detector Tracker](https://github.com/alwaysai/detector-tracker) | Use [Object Detection](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-detection) and [Object Tracking](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-tracking) to follow objects as they move across the frame. Detectors are resource expensive, so this combination reduces stress on the system, increasing the resulting bounding box output rate. |
| [Face Detector](https://github.com/alwaysai/face-detector) | Use [Object Detection](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-detection) to detect human faces in a real-time camera stream. |
| [Image Classifier](https://github.com/alwaysai/image-classifier) | Use [Image Classification](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#image-classification) to classify a batch of images. The classification labels can be changed by selecting different models. |
| [Object Detector](https://github.com/alwaysai/object-detector) | Use [Object Detection](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-detection) to detect objects in a real-time camera stream. The types of objects detected can be changed by selecting different models. |
| [Pose Estimator](https://github.com/alwaysai/pose-estimator) | Use [Pose Estimation](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#pose-estimation) to determine human poses in realtime. Human Pose returns a list of key points indicating joints that can be used for applications such as activity recognition and augmented reality. |
| [Semantic Segmentation VOC](https://github.com/alwaysai/semantic-segmentation-voc) | Perform [Semantic Segmentation](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#semantic-segmentation) on a series of images using a model trained on the [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/) dataset. |

## NVIDIA Apps :rocket:

| App | Description |
| --- | ----------- |
| [CUDA Applications](https://github.com/alwaysai/cuda-applications) | This alwaysAI application set use a CUDA (Compute Unified Device Architecture) interface which allows CNN models to execute on  NVIDIA  GPUs found on Jetson devices.  CUDA APIs give applications executing on the CPU direct access to NVIDIA’s GPU’s virtual instruction set and parallel computational elements. |
| [NVIDIA Real-Time Object Detector](https://github.com/alwaysai/nvidia-realtime-object-detector) | This alwaysAI app performs object detection in real-time on NVIDIA Jetson devices. |
| [NVIDIA Semantic Segmentation](https://github.com/alwaysai/nvidia-semantic-segmentation) | This alwaysAI app performs semantic segmentation on a video clip of a driving scene on NVIDIA Jetson devices. |
| [TensorRT Applications](https://github.com/alwaysai/tensorrt-hacky-hour) | This alwaysAI applications set uses TensorRT binaries to do the local inferencing on a NVIDIA Jetson device, these binaries can be found in the alwaysAI model catalog.  The model will start with TRT and end with the Jetson device name it should be run on, for example nano.  These binaries are the most efficient way to do inferencing on NVIDIA Jetson device.  Currently alwaysAI supports TensorRT binaries for Jetson Nano, TX2 and Xavier NX. |

## Camera Apps :camera_flash:

| App | Description |
| --- | ----------- |
| [Eyecloud Starter App](https://github.com/alwaysai/eyecloud-starter-app) | A basic application to get you started working with Eyecloud Cameras. |
| [oak-cameras-repo](https://github.com/alwaysai/oak-cameras) | The Oak-1 and Oak-D cameras have built-in chips for artificial intelligence, eliminating the security, latency and cost issues found in cloud based inferencing. The cameras can determine where objects are located in the space around them, as well as their trajectory, in real time. The cameras features built-in Intel Myriad X chips for running the machine learning inferencing locally.  This Repo shows you how to use these amazing cameras with the alwaysAI platform providing powerful easy to use option for them to create commercial products. |
| [Oak Starter Apps](https://github.com/alwaysai/oak_starter_apps) | This repository contains a collection of starter apps for using OAK cameras with the alwaysAI platform. |
| [RealSense Object Detector](https://github.com/alwaysai/realsense-object-detector) | Use [Object Detection](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-detection) to detect objects and the [RealSense camera](https://alwaysai.co/docs/edgeiq_api/real_sense.html) to get the distances in meters to those objects in real-time. The types of objects detected can be changed by selecting different models. |

## Streaming Apps :clapper:

| App | Description |
| --- | ----------- |
| [Dash Interactive Streamer](https://github.com/alwaysai/dash-interactive-streamer) | This application provides a base for an interactive streamer using Plotly Dash (https://dash.plotly.com). This app includes a video stream, which depicts object detection results, as well as a table that updates every 5 seconds with object detection results. You can create more complex applications by adding components. |
| [Interactive Image Capture App](https://github.com/alwaysai/image-capture-dashboard) | This alwaysAI app builds off of the app found [here](https://github.com/alwaysai/video-streamer) to provide a customized data collection server that allows the user to take snap shots or record videos and store them for later use. |
| [Multiple Camera Streams](https://github.com/alwaysai/multiple-camera-streams) | This alwaysAI application demonstrates how to incorporate video streams from multiple cameras into a single app. |
| [Simple Video Recorder](https://github.com/alwaysai/video-recorder) | This alwaysAI app records and saves video from a USB webcam or CSI ribbon camera. |
| [Video Streamer](https://github.com/alwaysai/video-streamer) | This alwaysAI app performs realtime object detection and streams video and text data to a Flask-SocketIO server that can be located on another device. |
| [Video Streamer Using Multiple Containers](https://github.com/alwaysai/video-streamer-multi-container) | This alwaysAI app performs realtime object detection and streams video and text data to a Flask-SocketIO server running in another container managed by [Docker Compose](https://docs.docker.com/compose/). |
| [ZMQ Video Streamer](https://github.com/alwaysai/zmq-video-streamer) | This repo has two parts: an alwaysAI computer vision app which performs realtime object detection and streams video via [ZeroMQ](https://zeromq.org/languages/python/) to a Flask server, and the server to display the video stream in a browser. |

## Example Apps :mag_right:

| App | Description |
| --- | ----------- |
| [Age and Gender Classifier](https://github.com/alwaysai/age-gender-classifier) | Use two [image classifiers](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#image-classification) to classify a batch of human face images by age and gender. |
| [Twilio Computer Vision App](https://github.com/alwaysai/alwaysai-twilio-sms) | A simple computer vision app that can detect a chair, and which sends a text message letting the user know when a chair has been detected. |
| [April Tag Detector](https://github.com/alwaysai/apriltag_detector) | This repo contains a basic application that shows you how to detect april tags using the `AprilTagDetector` in edgeIQ. |
| [Capacity Detector](https://github.com/alwaysai/capacity-detector) | This application is meant to detect people from a live or recorded video stream and determine if they are entering or exiting a location. That info is then can be sent via a POST call to a URL endpoint for processing. |
| [Classifier based Image Sorter](https://github.com/alwaysai/classifier-image-sorter) | This app can use an image classifier to detect any number of target labels, then sort those images into 1 of 2 folders. |
| [Contraband Detector App](https://github.com/alwaysai/contraband-detector) | This app uses object detection and employs a correlation tracker to monitor a frame for items deemed 'contraband'. For working or learning at home, these items may be headphones, cell phones, books, etc. We use two object detection models in order to maximize the number of objects we can detect given a set of freely available detection models. You can add or remove models and alter labels to suit your needs! |
| [Crosswalk Object Detection](https://github.com/alwaysai/crosswalk-object-detection) | This app performs object detection on a video of a crosswalk in simulated real-time. The app will automatically perform inference on the CUDA GPU on Jetson devices. |
| [Darts](https://github.com/alwaysai/Darts) | Play darts with alwaysAI and the Intel RealSense depth camera! |
| [Distance Detector](https://github.com/alwaysai/distance-detector) | This app will display the distance between two hands in inches. This app uses a web camera as the video stream and uses reference object metrics to approximate distance between two objects in an image. |
| [Face Counter](https://github.com/alwaysai/face-counter) | Use [Object Detection](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-detection) and [Correlation Tracking](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-tracking) to count unique human faces in the frame on a  real-time camera stream. |
| [Face Swapper](https://github.com/alwaysai/face-swapper) | Swaps the faces of people in a video stream when more than one person is in the frame. |
| [Facial Landmarks with DLIB](https://github.com/alwaysai/facial_landmarks_with_dlib) | Using DLIB to do facial detection and find landmarks. |
| [Gesture Controlled Home Interaction App](https://github.com/alwaysai/gesture-audio-control) | This app is designed to let you use your own custom gesture model to activate voice-activated technology, such as Alexa, Google Home, or Siri, using computer vision. After training your own gesture-detection model, using hand signals of your choice, you can use these signals to play audio files that give commands to smart tech. |
| [Hacky Hour 08/06/2020](https://github.com/alwaysai/hacky-hour-0806202) | Source code for the August 6 2020 Hacky Hour!  Demonstrates how a computer vision application can be used in manufacturing to confirm that a worker has chosen the correct component for assembly of a product.  The CV application finds the roi associated with an illuminated LED on a tray shelve.  It then checks to see if the workers hand has picked up the correct component using a hand detection model and overlapping rectangles algorithm between roi and hand detection bounding box.  The bounding box of hand detector turns green when the correct component is chosen and remains red until that occurs. |
| [Jumping Jacks Counter](https://github.com/alwaysai/jumping-jacks-counter) | This app counts jumping jacks for a single person on a real-time video stream or a video file. The app defaults to the `TensorRT` engine on NVIDIA Jetson devices, and the `DNN` engine elsewhere. |
| [Kalman Tracking Hacky Hour 05/12/2021](https://github.com/alwaysai/kalman_hackyhour) | Source for the May 12th Hacky Hour! This app demonstrates how to use the [Kalman Tracker](https://alwaysai.co/docs/edgeiq_api/object_tracking.html#edgeiq.object_tracking.KalmanTracker) to track objects in motion. |
| [License Plate Tracker App](https://github.com/alwaysai/license-plate-detector) | This app uses object detection and employs a correlation tracker to monitor a frame for license plates and vehicles. Please note that the model used in this app does not detect the content or read the characters from a license plate. Pair this app with an OCR library to do so. |
| [License Plate OCR App](https://github.com/alwaysai/license-plate-ocr) | This app uses object detection and employs a correlation tracker to monitor a frame for license plates and vehicles and then uses an OCR library to read the license plates. This app will work on development machines, such as MacOS and Windows, but not on ARM 64 architectures due to the dependency on PyTorch. |
| [Classifier based Image Sorter](https://github.com/alwaysai/multiple-classifiers-image-sorter) | This app can use any number of image classifiers to detect any number of target labels, then sort those images into 1 of 2 folders if the target label is detected. |
| [Multiple Object Detectors Sample App](https://github.com/alwaysai/multiple-object-detectors) | This app utilizes two object detection models, with the option of adding additional detection models. This may be helpful for including models that comprise very different libraries. In this example, one model detects numerous objects of small to medium size, and the other has a more limited library but detects some larger objects, such as airplanes, trains, and sofas. As there is some overlap between models, for instance they both detect people, you can compare the prediction confidences. Additionally, the output for each model appears in a separate video frame. |
| [Object Detection Server/Client](https://github.com/alwaysai/object-detection-server-client) | Server app sets up an alwaysAI model to run on an device where images can be sent and inferenced. The server returns the marked-up image to the client. |
| [Object Detection & Classifier Sample App](https://github.com/alwaysai/object_detector_and_classifier) | This app enables two alwaysAI models to be used simultaneously: one to detect facial objects, and a second to classify the detected faces in terms of age ranges.  |
| [Package Detection System App](https://github.com/alwaysai/package_detection_system) | This app is designed to let you use your own custom package detection model to detect when packages arrive and when they are removed You'll need an alwaysAI account and to have alwayAI installed: |
| [Pedestrian Segmentation](https://github.com/alwaysai/pedestrian-segmentation) | This app expands on the *semantic_segmentation_cityscape* starter app to build an app that segments pedestrians and bicyclists in each frame of a video, and performs actions based on the results. The full tutorial can be found on the [alwaysAI blog](https://learn.alwaysai.co/how-to-detect-pedestrians-and-bicyclists-in-a-cityscape-video). |
| [People Counter App](https://github.com/alwaysai/people-counter) | This app expands on the alwaysAI face counter starter app to both count the number of non-unique people (same person will be counted multiple times if they exit and re-enter the frame) detected and to display basic time metrics on those appearances. |
| [Classify Poses with Pose Estimation and Support Vector Machines (SVM)](https://github.com/alwaysai/pose-classification-train-svm) | This repo contains an alwaysAI app and Jupyter Notebook to classify poses using [Pose Estimation from alwaysAI](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#pose-estimation) and machine learning tools from [Scikit-Learn](https://scikit-learn.org/stable/). This tutorial will walk through training an SVM to classify a few common yoga poses. |
| [Posture Corrector with Pose Estimation Example App](https://github.com/alwaysai/posture-corrector) | This app uses pose estimation to help users correct their posture by alerting them with a sound when they are slouching, leaning, or tilting their head down, as well as a printed message with specific suggestions for correcting posture. A **scale** variable is used to adjust the keypoints measurements for different individuals, accounting for greater or smaller natural distances between keypoints used to detect poor posture. |
| [Semantic Segmentation Cityscape](https://github.com/alwaysai/semantic-segmentation-cityscape) | Use [Semantic Segmentation](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#semantic-segmentation) to determine a class for each pixel of an image. The classes of objects detected can be changed by selecting different models. This particular starter application uses a model trained on the [Cityscapes Dataset](https://www.cityscapes-dataset.com/). The Cityscapes Dataset focuses on semantic understanding of urban street scenes, and is a favorite dataset for building autonomous driving machine learning models. |
| [Simple Object Counter](https://github.com/alwaysai/simple-object-counter) | Use [Object Detection](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#object-detection) to count the number of each type of object in the frame of a real-time video stream. |
| [Virtual Green Screen with Edge Smoothing Example App](https://github.com/alwaysai/smooth-semantic-segmentation) | This app expands on an app that uses semantic segmentation to segment out a person from background noise in a video stream and replace the background with an image or blur it out. This app demonstrates how to subsequently smooth segmentation boundaries. This app also demonstrates how to separate your app configuration information into a separate JSON file. For more details on this aspect of the app, please see the [original blog post](https://medium.com/@jalakoo_83320/using-a-computer-vision-classifier-to-sort-images-333d5090c0b4). |
| [Snapshot Security Camera App](https://github.com/alwaysai/snapshot-security-camera) | This app expands on the *realtime_object_detector* starter app to build a simple security camera app that takes a picture of each new person who enters the frame. The full tutorial can be found on the [alwaysAI blog](https://alwaysai.co/blog/detect-people-using-alwaysai). |
| [Spatial AI Webinar Apps](https://github.com/alwaysai/spatial-ai-webinar-repo) | Spatial AI is the blending of machine learning inferencing with geometric data from sensors, enabling robots, drones or autonomous vehicles to better understand the world around them. |
| [Temperature Tracker App](https://github.com/alwaysai/temperature-tracker) | This app demonstrates how to use a temperature tracking utility class for the Raspberry Pi.  |
| [Thermal Imaging](https://github.com/alwaysai/thermal-imaging) | This repo contains applications that demonstrate how to use FLiR Lepton thermal camera.  The FLiR sensor uses microbolometer array that changes resistance as its heated up.  By measuring resistance the sensor can determine the temperature of detected objects.  The sensor's firmware creates a colored image that encodes that resistance data into heat map.  The image can be processed using the same techniques as visible light. |
| [Vaccination Center Assistant](https://github.com/alwaysai/vaccination-center-assistant) | A series of applications to help monitor a waiting room, log vaccination events, and monitor a post-vaccination room, and write out event logs to help inform vaccination center logistics. |
| [Virtual Green Screen Example App](https://github.com/alwaysai/virtual-green-screen) | This app uses semantic segmentation to segment out a person from background noise in a video stream and replace the background with an image or blur it out. This app builds off of a methodology for segmenting out areas of interested, which can be found [here](https://alwaysai.co/blog/how-to-detect-pedestrians-and-bicyclists-in-a-cityscape-video). This app also demonstrates how to separate your app configuration information into a separate JSON file. For more details on this aspect of the app, please see the [original blog](https://medium.com/@jalakoo_83320/using-a-computer-vision-classifier-to-sort-images-333d5090c0b4). |
| [YMCA APP](https://github.com/alwaysai/ymca-app) | In this example we'll be using a simple set of cases to determine if someone is doing a Y, M, C, or A in our image then displaying the letter on the screen if they do creating a fun virtual experience. |
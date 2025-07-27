# Traffic-Light-Management-System-
Traffic Light Controller System and Road Congestion Detection using Vehicle Count

This project is a Python-based desktop application that simulates a smart traffic control system using image processing. The system aims to detect the level of road congestion in real-time and allocate green signal timing dynamically based on the number of vehicles present at an intersection. It is implemented using a graphical user interface (GUI) built with Tkinter and uses OpenCV, NumPy, and a custom Canny Edge Detection module to process traffic images.

The main idea is to analyze a traffic image by converting it to grayscale and applying edge detection to highlight vehicles. The white pixels in the processed image represent vehicle edges. These are counted and compared with a pre-defined reference image (with known traffic levels) to estimate traffic density. The program then uses a decision logic to assign a green signal time. Higher congestion results in more green time and vice versa.

The system is easy to use through a user-friendly interface. The user can upload a traffic image, initiate edge detection, and view both the sample and reference images side by side. The white pixel counts are displayed using pop-up messages, and the green signal timing is calculated and shown based on a percentage comparison.

This application can be used as a prototype for intelligent traffic systems, where automation and real-time monitoring are required. It provides an efficient way to improve road traffic management by adapting signal timings according to actual conditions, rather than fixed cycles.

Key Features:

Upload and process real traffic images

Grayscale conversion and edge detection using Canny algorithm

Pixel-based vehicle count estimation

Comparison with a reference image to determine congestion level

Smart allocation of green signal timing

Fully interactive GUI built with Tkinter

This project demonstrates a simple but effective approach to traffic control using computer vision. While it uses static images in its current form, it can be extended to work with live video feeds or integrated into traffic monitoring systems.


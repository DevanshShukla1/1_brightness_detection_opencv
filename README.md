## Visualizing Sunrise and Sunset with OpenCV 🌄(Solution)

Problem Statement:

To detect sunrise, sunset, and transitions between night, morning, and day in a video. The goal was to classify these time periods based on brightness distribution and output real-time visualizations, showcasing how much of the video represents night or day.

Key Concepts:

Color Models: RGB vs. HSV, and why HSV is ideal for brightness-based analysis.

Thresholding and Contour Detection: To identify bright areas representing the sun or illuminated portions.

Frame Classification: Simplified categories for night, morning, and day, ensuring clarity in transitions.

Insights:

🔑 OpenCV's foundational operations like color conversion, thresholding, and contour analysis are powerful tools.

🔑 A strong grasp of color models and their use cases can simplify complex problems in computer vision.

🔑 By focusing on basics, like analyzing brightness distribution, advanced real-time visualizations become achievable.

Here’s the output:
Real-time thermogram alongside the original video.


https://github.com/user-attachments/assets/99bb8426-f924-4659-9118-802cf3818a4a




Classify each frame into night, morning, or day based on brightness distribution.

🌟My takeaway: Sticking to the basics and understanding foundational concepts unlocks the path to building advanced solutions. Solving real-life problems related to the subject you are learning and implementing the concepts learned makes you an expert in that subject.

What’s your favorite OpenCV use case? Let’s discuss this in the comments! 👇

Special thanks to Monal kumar and Krish Naik  for their guidance in understanding color models and core opencv concepts.                                                  





#opencv #computervision #basics #machinelearning


Approach:

1️⃣ Converted video frames to HSV (Hue, Saturation, Value) to focus on the brightness channel (Value).

2️⃣ Applied thresholding techniques to detect bright and dark regions dynamically.

3️⃣ Segmented and classified frames based on the ratio of bright regions to the overall frame area.

4️⃣ Visualized brightness as a thermogram alongside the original video for better insights.
![alt text](https://github.com/DevanshShukla1/1_brightness_detection_opencv/blob/main/output.jpg?raw=true)
![alt text](https://github.com/DevanshShukla1/1_brightness_detection_opencv/blob/main/color_overlay_output.jpg?raw=true)
![image](https://github.com/user-attachments/assets/36340fc6-5501-4345-b601-47a1c7146480)



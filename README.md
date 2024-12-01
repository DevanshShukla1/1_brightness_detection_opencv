## 1_brightness_detection_opencv
The code described in brief:
## 1) Basic imports opencv, numpy
## 2) Thresholds Definition: Brightness ranges for categorizing frames into Day, Evening, Night, and Morning are defined using the Value channel (HSV).
## 3) Video Reading: The video is read using cv2.VideoCapture, and each frame is processed sequentially.
## 4) Brightness Calculation: The brightness of each frame is computed by taking the mean value of the Value channel in HSV color space.
## 5) Frame Classification: Frames are categorized by checking their brightness levels against predefined thresholds. Counters (counts) and representative frames (representative_frames) are updated accordingly.
## 6) Percentage Distribution: The percentage of frames in each category is calculated relative to the total frame count.
## 7) Annotated Images: The representative frames are resized, annotated with percentages using cv2.putText, and concatenated vertically for display.
## 8) Display Annotated Frames: The annotated frames are shown in a window using cv2.imshow.
## 9) Pie Chart Visualization: A pie chart is plotted using Matplotlib to illustrate the percentage distribution of time categories.
![alt text](https://github.com/DevanshShukla1/1_brightness_detection_opencv/blob/main/output.jpg?raw=true)
![alt text](https://github.com/DevanshShukla1/1_brightness_detection_opencv/blob/main/color_overlay_output.jpg?raw=true)


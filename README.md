# opencv-license-plate-detection

This app detects and reads license plates in a video, then stores them in a file.

# Things to keep in mind:

- Make sure CUDA, cudnn and tesseract are configured on your system.

- If you don't get very good results, try changing the width and height in yolov3-custom.cfg to a higher resolution (width and heigt MUST be equal, the default resolution is 416x416, but i use 800x800 in this project).

- Works ONLY with Python 3.8 or above!

# Useful Links:

- https://github.com/AlexeyAB/darknet
- https://www.youtube.com/watch?v=zJDUhGL26iU
- https://gist.github.com/adioshun/779738c3e28151ffbb9dc7d2b13c2c0a
- https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/

# How to run

Using a video file:

> python3 main.py --input video.mp4

If you want to use your camera, just don't specify the input argument:

> python3 main.py
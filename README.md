# opencv-license-plate-detection

This app detects and reads license plate, then stores them in a file.

# Things to keep in mind:

- Make sure CUDA, cudnn and tesseract are configured on your system.

- If you don't get very good results, try changing the width and height in yolov3-custom.cfg to a higher resolution (width and heigt MUST be equal, the default resolution is 416x416, but i use 800x800 in this project).

# Useful Links:

- https://github.com/AlexeyAB/darknet
- https://www.youtube.com/watch?v=zJDUhGL26iU
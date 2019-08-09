# Mask RCNN
 
**Usage Examples :**

**Python**

`python3 mask_rcnn.py --image=image.jpg`
`python3 mask_rcnn.py --video=video.mp4`

It starts the webcam - if no argument provided.

**C++**

Compile using:

```g++ -ggdb `pkg-config --cflags --libs /Users/snayak/opencv/build/unix-install/opencv.pc` mask_rcnn.cpp -o mask_rcnn.out```

Run using:
`./mask_rcnn.out --image=image.jpg`
`./mask_rcnn.out --video=video.mp4`

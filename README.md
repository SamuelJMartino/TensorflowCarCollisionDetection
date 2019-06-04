# YOLO ECON PROJECT
PROGRAMMED BY:SAM MARTINO
A Libtorch implementation of the YOLO v3 object detection algorithm, written with pure C++.  CPU and GPU are both supported.



## Requirements
1. LibTorch v1.0.0
2. Cuda
3. OpenCV (just used in the example)


## To compile
1. cmake3
2. gcc 5.4 +



```

## Running the detector

The first thing you need to do is to get the weights file for v3:

```
cd models
wget https://pjreddie.com/media/files/yolov3.weights 
```

On Single image:
```
./yolo-app ../imgs/person.jpg
```

As I tested, it will take 25 ms on GPU ( 1080 ti ). please run inference job more than once, and calculate the average cost.

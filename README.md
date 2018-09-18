## 

[![Video Label](http://img.youtube.com/vi/LAoADjwoW4Q/0.jpg)/0.jpg)](https://www.youtube.com/watch?v=LAoADjwoW4Q)
[![Video Label](http://img.youtube.com/vi/E5L7IvL8ZNI/0.jpg)](https://www.youtube.com/watch?v=E5L7IvL8ZNI)
[![Video Label](http://img.youtube.com/vi/Ch7XqJ3e_R8/0.jpg)](https://www.youtube.com/watch?v=Ch7XqJ3e_R8)

## installation

1. Dockerfile
 
 (w/o GPU) $ docker build --file Dockerfile --tag yolov3_ubuntu18.04:0.1 .
 (w/  GPU) $ nvidia-docker build --file Dockerfile --tag yolov3_ubuntu18.04:0.1 .

2. build container

 (w/o GPU) $ docker run -it yolov3_ubuntu18.04:0.1
 (w/  GPU) $ nvidia-docker run -it yolov3_ubuntu18.04:0.1

3. build darknet

 $ cd /root/src/darknet
 $ make

4. run

 $ cd /root/src/darknet
 $ python run.py



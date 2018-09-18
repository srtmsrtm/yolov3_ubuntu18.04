

+1. Dockerfile
 
 (w/o GPU) $ docker build --file Dockerfile --tag yolov3_ubuntu18.04:0.1 .
 (w/  GPU) $ nvidia-docker build --file Dockerfile --tag yolov3_ubuntu18.04:0.1 .

+2. 

 (w/o GPU) $ docker run -it yolov3_ubuntu18.04:0.1
 (w/  GPU) $ nvidia-docker run -it yolov3_ubuntu18.04:0.1

+3. build darknet

 $ cd /root/src/darknet
 $ make

+4. run

 $ cd /root/src/darknet
 $ python run.py



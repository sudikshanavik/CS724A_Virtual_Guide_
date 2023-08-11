# Virtual Guide
Other data files are included in the drive:<br>
https://drive.google.com/drive/u/0/folders/1PBgi8m0heZsDgxqBKgIRLxLC6KVTpEqU

## Introduction
We propose a virtual eye tool that utilizes the experience of the CASBlip projects regarding practical requirement of blind people. Our prototype tool consists of a camera mounted on a helmet, its image is processed with a portable computer carried by the user in real time. Earlier research prototypes were limited to 32*32 images and depth maps of similar size which results in heavy information loss making for instance traffic lamp detection impossible. In our work, we use full scale images, and yet process them automatically in real time. Out image pro- cessing algorithms cover the classification of hanging obstacles, road crossings, stairs, traffic lamps, which is much a broader spectrum than in previous virtual eye solutions could provide.

## Block Diagram
<img width="438" alt="image" src="https://github.com/sudikshanavik/CS724A_Virtual_Guide_/assets/100257642/451284b7-6a76-4197-baed-835278f98c8a">

### Working Modules
+ Object Detection:
In this phase we detect the real world objects. Like humans in still images or Videos. Diagram shows the examples of the how to object are detected easily.<br>

+ Obstacle Detection:
In the proposed method, an ultrasonic sensor is used for obstacle detection in front of the users. Another ultrasonic 
sensor is used to detect humps on the ground or on the road. A PIR motion sensor is used for detecting the moving 
objects in front of the user. <br>

The user will be notified if there is an obstacle or a hump or a moving object in front of him/her by speech instructions from buzzer. If the user falls down, the guardian will be instantly notified by the smartphone module<br>

### Result & Evaluation

![image](https://github.com/sudikshanavik/CS724A_Virtual_Guide_/assets/100257642/cfa6a67b-a1ff-4be9-8e4d-c4751f4a5071)

![image](https://github.com/sudikshanavik/CS724A_Virtual_Guide_/assets/100257642/5bc19a1d-557d-44e4-a353-8dcb746a72f9)


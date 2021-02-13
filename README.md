## Wildlife Detector ##



### Description ###

Many national parks and wildlife reserves have installed webcams that stream their grounds, so that viewers from across the world can observe their wildlife remotely. Streaming can enhance the profile of parks, increase engagement with potential visitors, as well as be an alternative source of income. However, for long periods of time, the cameras do not capture any wildlife. This can be frustrating or boring for viewers.
This program can interface with webcams and detect when animals appear on the camera stream. The user can select which animals they are interested in and receive automated email notifications whenever their animals of choice are present and then tune into the stream. The current example alerts to appearance of elephants or giraffes.

The input videos used for this example can be found in the input folder. The analyzed and object detected output videos can be found in the output folder. Below, are example gifs for the output files. Example 1 demonstrates detection of elephants and Example 2 demonstrates detection of giraffes. On the first instance of detection, an image is captured which is emailed to users. The images are displayed below and can be found in the images folder.
This program uses OpenCV with YOLOv3. When implementing it, make sure to download yolo.cfg, yolov3.weights, and coco.names. In the current implementation these files should be placed in the same folder as the code. The reduced quality of the gifs is a function of the conversion from mp4 to gif and is not related to objection detection or the writing of frames to file.


### Example 1: Elephant Detection ###

#### Output ####

![Elephant Detection](/gifs/elephants.gif)


#### Screenshot of First Instance of Detection to be Included as Attachment in the Alert Email ####


![Elephant Detected](/images/Elephant_Detected.jpg)



### Example 2: Giraffe Detection ###

#### Output ####

![Giraffe Detection](/gifs/giraffes.gif)


#### Screenshot of First Instance of Detection to be Included as Attachment in the Alert Email ####


![Giraffe Detected](/images/Giraffe_Detected.jpg)

Important Notice:
You must install the latest version of Opencv through Opencv or through 
(PIP INSTALL OPENCV-CONTRIB PYTHON).
 Its advicable to user -TERMINAL OR COMMAND LINE TO RUN THE PROGRAM.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
YOU CAN RUN THE PROGRAM AS FOLLOWS:
----------------------------------
1 -  python mask_rcnn.py --mask-rcnn mask-rcnn-coco --image images/example_02.jpg(use can use any pictures)  --confidence 0.6
 
2-  python mask_rcnn.py --mask-rcnn mask-rcnn-coco --image images/example_02.jpg(use can use any pictures) --confidence 0.6

3- You can put your cusor to the any picture and press to see the confidence of any images



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

# ObjectDetectingOpencv
How to Locate image and detection
There are many ways in locating and detecting Images but we would base our first method in Deep Learing and using OpenCV frame work
Mask R-CNN with OpenCV
i'll discuss the difference between image classification, object detection, instance segmentation, and semantic segmentation.
I’ll then show you how to apply Mask R-CNN with OpenCV to in  images 

Instance segmentation vs. Semantic segmentation.

//****************//
When performing traditional image classification our goal is to predict a set of labels to characterize the contents of an input image (top-left).

//*********//
Object detection builds on image classification, but this time allows us to localize each object in an image. The image is now characterized by:

Bounding box (x, y)-coordinates for each object
An associated class label for each bounding box
//*********************//

semantic segmentation can be seen in bottom-left. Semantic segmentation algorithms require us to associate every pixel in an input image with a class label (including a class label for the background).


What is Mask R-CNN?

The Mask R-CNN algorithm was introduced by He et al. in their 2017 paper, Mask R-CNN.(Detailed can be found in the paper stated)

Mask R-CNN builds on the previous object detection work of R-CNN (2013), Fast R-CNN (2015), and Faster R-CNN (2015), all by Girshick et al.(Detailed can be found in the paper stated)

NOTE-If there is any information that is lacking please kindly contact or add more

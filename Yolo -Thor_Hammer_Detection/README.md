## Yolov3 Object detection on THOR Hammer.  

![Predicted image](https://github.com/LokeshJatangi/Computer-vision/blob/master/Yolo%20-Thor_Hammer_Detection/Prediction%20Image.png)

Custom tiny-yolo-v3 training using your own dataset and testing the results on a video using the google colaboratory.
Object detection using yolo algorithms and training your own model and obtaining the weights file using google colab platform.

The Process:
 1) Collection of Data 
 2) Annotation of Data
       The annotation of objects(Bounding box) from the image is carried according to Yolo.Bounding boxes can be created by 
       running the main.py file present in Annotations Folder on the Training Images.The output of Bounding box is saved in YOLO format.
 3) Calculation of Anchors from anchors.py.
 4) Load the Data to Google Colab
 5) [Training the YOLO on custom dataset.](https://github.com/LokeshJatangi/Computer-vision/blob/master/Yolo%20-Thor_Hammer_Detection/YOLO%20Training.ipynb)
 6) Testing on image and Videos
 
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

Source for Training on Google Colab:
 1) (https://medium.com/@today.rafi/train-your-own-tiny-yolo-v3-on-google-colaboratory-with-the-custom-dataset-2e35db02bf8f)
 2) (https://github.com/rafiuddinkhan/Yolo-Training-GoogleColab)
 
Source for Darknet YOLO : 
      (https://github.com/AlexeyAB/darknet/)

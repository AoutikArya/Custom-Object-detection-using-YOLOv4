# Custom-Object-detection-using-YOLOv4

Dataset
For training the model i have used  the dataset from kaggle https://www.kaggle.com/brendan45774/bike-helmets-detection?select=images
which has two classes:
1.with helmet
2.without helmet
along with their annotations, but as annotation were in Pascal VOC xml format i converted it into yolo format(https://gist.github.com/Amir22010/a99f18ca19112bc7db0872a36a03a1ec) and then trained these images with the YOLOv4 object detection algo with gave me quite impressive mAP.I have used the pre trained weight yolov4.conv.137 and further trained my model on this for around 2000 iterations and got an avg mAP pf around 88% for the model.

# Counting object detected
https://github.com/theAIGuysCode/yolov4-custom-functions.git
Used this repo to get the count of object detected.
 

![ezgif-1-10271d9fe3](https://user-images.githubusercontent.com/90469048/195347162-6296b74f-9bc0-4deb-8c59-31970683144f.gif)
# Custom-Object-detection-using-YOLOv4

Dataset
For training the model i have used  the dataset from kaggle https://www.kaggle.com/brendan45774/bike-helmets-detection?select=images
which has two classes:<br />
1.with helmet<br />
2.without helmet<br />
along with their annotations, but as annotation were in Pascal VOC xml format i converted it into yolo format(https://gist.github.com/Amir22010/a99f18ca19112bc7db0872a36a03a1ec) and then trained these images with the YOLOv4 object detection algo with gave me quite impressive mAP.I have used the pre trained weight yolov4.conv.137 and further trained my model on this for around 2000 iterations and got an avg mAP pf around 88% for the model.

# Counting object detected
https://github.com/theAIGuysCode/yolov4-custom-functions.git <br />
 Used this repo to get the count of object detected. <br />
orginal video https://www.youtube.com/watch?v=9WNzIDEcNP4 <br />
detected video https://drive.google.com/file/d/1HjHJj6YuNptJM1ClI6MSEAoaH4kuNS9t/view?usp=sharing
 

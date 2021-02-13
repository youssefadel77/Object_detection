1-first download the git 
	https://github.com/tensorflow/models
2-download the protoc 
3-extract all to folder 
4-on the  cmd on model-master/research/object_detection 
5- write :
	"C:/username/download/protoc/bin/protoc" object_detection/protos/*.proto --python_out=.
6-put the .pb file and the .pbtxt to the "model-master/research/object_detection"
7-put the image in the "models-master\research\object_detection\test_images"
8-rename the image to "image3.png"
9-put the visual script to "models-master\research\object_detection\utils" replace
10-put the object_detection_2 to "models-master\research\object_detection"
11-run the script :
	python object_detection_2.py
and the image  will created to you with name dnaa0.jpg

# YOLOv3 
object detection using YOLOV3 
This code loads the YOLOv3 model, performs object detection on an image, and draws bounding boxes around detected objects with their labels and confidence scores.

## Here are the steps to perform object detection using YOLOv3:

1. Install Required Libraries: </br>
	      pip install opencv-python numpy matplotlib
   
2. Download YOLOv3 Weights and Configuration: </br>
	You'll need the YOLOv3 pre-trained weights and configuration file. You can download them from the official YOLO website or use pre-trained weights available in various repositories.
	links:</br>
		yolov3 weights: "https://pjreddie.com/darknet/yolo/" </br>
		yolov3 cfg: "https://github.com/AlexeyAB/darknet" </br>
  
3. Load YOLOv3 Model: </br>
	You'll need to load the YOLOv3 model using the weights and configuration files.

4. Perform Object Detection:</br>
    Use the loaded model to perform object detection on an image.

Make sure to replace 'yolov3.weights', 'yolov3.cfg', 'coco.names' and give proper url(remove inverted commas from url).
	url format: C:/Users/Welcome/Internship/Project/image.jpg
 

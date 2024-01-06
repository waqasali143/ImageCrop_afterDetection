# ImageCrop_afterDetection
# Computer Vision Object Detection and Image Crop Project
The provided Python script leverages YOLOv5, a state-of-the-art object detection model, to identify and crop the most confident object in a given image. The main function orchestrates the process by loading the model, displaying the detection results, and extracting relevant information. Subsequently, the objectCrop function crops the identified object and saves it to a specified directory. The script showcases the use of computer vision libraries, such as OpenCV and PyTorch.
### Need the mandatory library we install for the "Object Detection and Image Crop" such as
* PyTorch <br>
* OpenCV <br>
* Pandas <br>
* os <br>

### *Pandas*
<p> df = modalResult.pandas().xyxy[0]</p>
library we use here for  Converts the result from the YOLOv5 model to a pandas DataFrame (df) containing bounding box coordinates and other information about detected objects.<br>
When we provide an image then program detects the objects in the image and Crops the one with a higher confidence value and stores it in another directory. Such as<br>
<br>
![download](https://github.com/waqasali143/ImageCrop_afterDetection/assets/82609521/ab6e8589-8341-4676-ad14-3fcdfde81f5b)


### After Crop<br>

![stop sign](https://github.com/waqasali143/ImageCrop_afterDetection/assets/82609521/e94bbdba-bd6f-40e8-a6a8-42f201e956f7)

# Traffic-Sign-Detection
* Detect The Traffic Sign Using YoloV5

# DATA COLLECTION:
**Data Collected from Roboflow website.**

# TASK: Object Detection

# DATA INFORMATION:
* Total 3708 traffic sign images are present in 43 classes .
* Create bounding boxes with the help of makesense.ai website.
  # Traffic Sign
  
![image](https://github.com/Tanwar-12/Traffic-Sign-Detection-/assets/110081008/f4f4be99-cad2-4ac9-aa77-8d8082d90900)
# DATA PREPRATION:
*	Prepare folder structure that can be accept by YoloV5.
* Total 3708 images for training and 352 images for validation present in 39 classes.
* Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  # STEPS TO USE YOLOV5
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights

## STEPS BEFORE TRAINING CUSTOM DATASET:
1. Go to yolov5/data/
2. Open coco128.yaml
3. Edit the following inside it:


     A. Training and Validation file path

     B. Number of classes and Class names.

# TRAINING YOLOV5 MODEL
* Set images size 408 with batch of 8
* Train model on 1000 epochs 
* Gives the data file path as well as give pre-trained weights path.

***VISUALISE THE TRAINING METRICS WITH THE HELP OF TENSORBOARD**
# PREDICTED IMAGES: 
![image](https://github.com/Tanwar-12/Traffic-Sign-Detection-/assets/110081008/377ad1ec-b2f2-44ff-9e27-e876ea0dbac3)





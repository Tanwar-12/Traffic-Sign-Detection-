# 𝐓𝐑𝐀𝐅𝐅𝐈𝐂 𝐒𝐈𝐆𝐍 𝐃𝐄𝐓𝐄𝐂𝐓𝐈𝐎𝐍 𝐘𝐎𝐋𝐎𝐕5
* Detect The Traffic Sign Using YoloV5

# 𝐃𝐀𝐓𝐀 𝐂𝐎𝐋𝐋𝐄𝐂𝐓𝐈𝐎𝐍:
**Data Collected from Roboflow website.**

# 𝐓𝐀𝐒𝐊: 𝐎𝐛𝐣𝐞𝐜𝐭 𝐃𝐞𝐭𝐞𝐜𝐭𝐢𝐨𝐧

# 𝐃𝐀𝐓𝐀 𝐈𝐍𝐅𝐎𝐑𝐌𝐀𝐓𝐈𝐎𝐍:
* Total 3708 traffic sign images are present in 43 classes .
* Total 2538 images for training and 701 images for validation present in 2 classes.
* Create bounding boxes with the help of makesense.ai website.
  # 𝐓𝐑𝐀𝐅𝐅𝐈𝐂 𝐒𝐈𝐆𝐍
  
![image](https://github.com/Tanwar-12/Traffic-Sign-Detection-/assets/110081008/f4f4be99-cad2-4ac9-aa77-8d8082d90900)
# 𝐃𝐀𝐓𝐀 𝐏𝐑𝐄𝐏𝐑𝐀𝐓𝐈𝐎𝐍:
*	Prepare folder structure that can be accept by YoloV5.
* Total 3708 images for training and 352 images for validation present in 43 classes.
* Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
 
  # 𝐒𝐓𝐄𝐏𝐒 𝐓𝐎 𝐔𝐒𝐄 𝐘𝐎𝐋𝐎𝐕5
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights

# 𝐒𝐓𝐄𝐏𝐒 𝐁𝐄𝐅𝐎𝐑𝐄 𝐓𝐑𝐀𝐈𝐍𝐈𝐍𝐆 𝐂𝐔𝐒𝐓𝐎𝐌 𝐃𝐀𝐓𝐀𝐒𝐄𝐓:
1. Go to yolov5/data/
2. Open coco128.yaml
3. Edit the following inside it:


     A. Training and Validation file path

     B. Number of classes and Class names.

# 𝐓𝐑𝐀𝐈𝐍𝐈𝐍𝐆 𝐘𝐎𝐋𝐎𝐕5 𝐌𝐎𝐃𝐄𝐋:
* Set images size 408 with batch of 8
* Train model on 1000 epochs 
* Gives the data file path as well as give pre-trained weights path.

**VISUALISE THE TRAINING METRICS WITH THE HELP OF TENSORBOARD**
# 𝐏𝐑𝐄𝐃𝐈𝐂𝐓𝐄𝐃 𝐈𝐌𝐀𝐆𝐄𝐒: 
![image](https://github.com/Tanwar-12/Traffic-Sign-Detection-/assets/110081008/377ad1ec-b2f2-44ff-9e27-e876ea0dbac3)
#  𝐓𝐄𝐒𝐓 𝐕𝐈𝐃𝐄𝐎
https://github.com/Tanwar-12/Traffic-Sign-Detection-/assets/110081008/0dcb0ed0-869c-4b89-983b-b6a21ed0c7c5







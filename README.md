# Object Detection with YOLO
YOLO (You Only Look Once) is a state-of-the-art object detection algorithm that is incredibly fast and accurate. Copy this git hub and follow the given steps to detect different images and videos. 
## How to Setup YOLO
Make sure to download the pretrained weights using the link bellow:
https://drive.google.com/file/d/111qp0mcuuQvu34f7a1YJ08AzNd1DNKuw/view?usp=sharing
<br />
**Put weights file into *yolo-coco* folder**
<br />Make sure to *git clone* this repo as well, so you can get all the libraries needed to continue.
Open up your command prompt and use the following code(s) depending on you want to detect.

### Image Detection: 
```
 python yolo.py --image "PATH OF YOUR IMAGE" --yolo yolo-coco
```
### Video Detection: 
```
 python yolo_video.py --input "PATH OF YOUR VIDEO" --output "OUTPUT PATH" --yolo yolo-coco
```


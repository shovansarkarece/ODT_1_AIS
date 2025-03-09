# YOLOv11 for Real-Time Class-Wise Vehicle Counting and Tracking
## Abstract
Effective vehicle detection is a top priority in the field of real-time applications like surveillance and autonomous driving. This environment has changed due to the You Only Look Once (YOLO) framework, which is well-known for its quick object detection. This study explores the integration of Yolo v11 and real-time vehicle recognition, refining its architecture for quick and accurate identification. The model's exceptional accuracy of 97.9% on mAP50 and 91.3% on mAP50-95, as demonstrated by empirical validation, highlights its strength. This accomplishment confirms the model's real-time processing capabilities in addition to attesting to its accuracy. The consequences have the potential to revolutionize urban planning and transportation safety. This study highlights YOLO v11's strength in intelligent object recognition, which has the potential to transform and improve a number of fields.
Keywords—YOLO Framework, mAp50-95, Vehicle Detection, Object Detection.
# YOLO v11 Framework
- **In order to efficiently detect objects, the YOLO (You Only Look Once-) Framework divides a picture into a grid and uses the network output to directly forecast bounding boxes and item classes (see Fig. 3).**

 ![image](https://github.com/user-attachments/assets/cfe1c0cb-351d-42a5-a877-010b60845d50)

Fig. 3. Bounding box prediction with the YOLO Framework


- **YOLO is well suited for real-time activities like video analysis and autonomous driving since it can quickly identify objects in a single network run. By approaching object detection as a regression problem, it effectively predicts attributes and classes, which accounts for its speed and accuracy.**

- **The architecture can be divided into several levels, such as detection, pooling, and convolutional layers. Through the acquisition of significant patterns from the input image, the convolutional layers carry out feature extraction. While maintaining key features, pooling layers minimize spatial dimensions. Bounding box predictions and class probabilities are produced by the detection layers.**
- **Two completely connected layers come after 24 convolution layers in the network architecture of the YOLO framework. According to Fig. 4, changing 1x1 convolution layers shrinks the features space from earlier layers.**

 ![image](https://github.com/user-attachments/assets/06783deb-3ac2-4861-881d-011df2562453)
- **The central coordinates (x, y) and the bounding box's dimensions (width w, height h) are used to calculate the modified bounding box coordinates (xmin, ymin, xmax, ymax):**

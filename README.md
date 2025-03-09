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

![image](https://github.com/user-attachments/assets/51b1ee80-c9ce-43a3-945c-c3b85f1b031f)

IV. EXPERIMENTAL RESULT
- **Here, we provide the experimental results and talk about them using the YOLO v11 framework. We can learn more about the efficacy and performance of our technique in this setting by analyzing these outcomes.**

![image](https://github.com/user-attachments/assets/4a2a917b-55b9-40f1-b5c0-fae4b6e7f313)

Fig. 5. Performance in training

- **The training procedure used the SGD optimizer with a learning rate of 0.01 and comprised 25 epochs with a batch size of 16. Separate parameter groups (57 for 0.0 weight decay, 64 for 0.0005 weight decay, and 63 for biases) were set up for weight decay and biases. The flexibility of the model was improved by augmentation approaches such blur, median blur, greyscale conversion, and CLAHE with a 0.01 probability. The YOLO model’s object detection ability was enhanced by this through training process , guaranteeing accuracy and resilience in real-world situations. (See Figure 5).**

![image](https://github.com/user-attachments/assets/9990f217-3c5c-4747-aee1-b926dc3d52b5)
- **Table 1. YOLO v11 model performance across all classes**

![image](https://github.com/user-attachments/assets/ff66954e-830a-4ca6-83e7-aa1b18a43eec)
- **Fig. 6. Confusion Matrix**
- **Important metrics and curves are used to assess object detection models. The model's sensitivity at various thresholds is illustrated by the Recall-Confidence Curve, which clarifies the relationship between recall and confidence thresholds (see Fig. 7). By balancing precision and recall, the Precision-Recall Curve illustrates how they interact at different confidence levels (see Fig. 8). Referring to Fig. 9, the Precision-Confidence Curve clearly illustrates how consistent precision is over a range of confidence levels. In the meanwhile, the F1-Confidence Curve captures the trade-off between recall and precision by connecting the F1-score to confidence thresholds (see Fig. 10). We provide a comprehensive evaluation of the model's performance over a range of thresholds and indicators by incorporating these curves into our presentation.**

![image](https://github.com/user-attachments/assets/51333f3f-a85c-4b5f-9131-79f724c850bd)

- **Fig. 7. Recall-Confidence Curve**

![image](https://github.com/user-attachments/assets/2432c97c-7f1f-4659-8bc2-83104e343cdb)

- **Fig. 8. Precision-Recall Curve**
- **The model had very impressive performance, attaining a recall rate of 93.5% and a precision rate of 96.6%. Additionally, the model's ability to handle a range of item sizes and placements was demonstrated by the strong result of 97.9% for the average precision across several categories (mAP) at IoU 0.50. Further confirming the model's resilience in object detection and localization tasks, the mAP computed across IoU thresholds from 0.50 to 0.95 produced a respectable 91.3%.**

![image](https://github.com/user-attachments/assets/b406363e-44c4-447d-9cd9-913e26701e9f)

- **Fig. 9. Precision-Confidence Curve**

![image](https://github.com/user-attachments/assets/97537762-8b6a-4edb-bfdd-f138ce16f5b5)

- **Fig. 10. F1-Confidence Curve**
# CONCLUSION

- **In summary, significant discoveries and developments have resulted from the investigation into effective vehicle detection and categorization utilizing the YOLO v5 framework. Particularly noteworthy is the YOLO v11 invention, which has shown remarkable accuracy of 97.9% on mAP50 and 91.3% on mAP50-95. This accomplishment highlights YOLO v11's revolutionary potential in real-time applications and establishes it as a key instrument in the transformation of vehicle detection systems.**
- **In the future, these methods will have an impact on more than only vehicle identification; they will influence the development of several technologies. YOLO v11's accuracy and real-time capabilities serve as an example of a larger trend in technical improvement. These methods provide the basis of advancements in self-driving car technology, which makes transportation networks safer. Additionally, their influence is felt in areas like as smart cities, which allow for effective traffic control and real-time surveillance for better urban living. These developments go beyond transportation and have an impact on industries like robotics and healthcare, highlighting the revolutionary potential of these methods in fostering a more connected and effective future.**

This project implements a real-time face mask detection system using the YOLOv5 (You Only Look Once) object detection model. It identifies whether a person is wearing a face mask or not, making it useful for monitoring public health compliance, especially in public places.

Features: 
Real-time Detection: Detects people wearing or not wearing masks in real-time through video feeds or images.
YOLOv5 Accuracy: Utilizes the YOLOv5 model for fast and accurate object detection.
Scalable: Can be used for individual applications or deployed in public spaces with multiple cameras.
Easy to Integrate: Can be easily integrated into existing security or monitoring systems.

Technologies Used: 
Framework: PyTorch
Model: YOLOv5 (pre-trained and fine-tuned for face mask detection)
Programming Language: Python
Libraries: OpenCV, Numpy, Pandas, PyTorch

Dataset: 
The model is trained on a custom dataset consisting of labeled images with and without face masks. click here to get dataset of with mask and without mask: https://drive.google.com/drive/folders/1H04Dw59A_7W-KVQes3XnXrQ3PIXiwmvX?usp=sharing

Future Enhancements: 
Improve detection accuracy by adding more diverse data to the training set.
Implement multi-class detection to identify face masks, incorrect mask-wearing, and no masks.
Deploy on edge devices like Raspberry Pi for low-cost real-time detection.

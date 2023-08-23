# smart-refrigerator

Leftover food wasted through spoilage is an important resource issue. Leftover food or food loss is food that is thrown away or not eaten. After a food product is purchased and put in the fridge, users are not aware of the expiration information unless they check it manually. Especially for food products that are not labeled with an expiration date, it will increase the risk of food spoilage and additional expenses for the user. Therefore, in this research, the author carries out an object and quality detection system for vegetables, fruit and meat. This system consists of a Raspberry Pi 3 and a Web Camera (Webcam). You Only Look Once (YOLO) is an algorithm that uses a Convolutional Neural Network (CNN) to detect objects and applies a Single Neural Network to the input image. The system will be used to determine the quality of the detected object. Collection of sample images of various foodstuffs in good and bad condition for training and testing datasets. This aims to determine the performance of the system in recognizing food ingredients and their quality. The images used have variations in position and distance differences, this is done to determine the accuracy of the system in recognizing objects in the image. After that the data will be sent to the cloud database. Using YOLOv5 object detection and quality has an accuracy value of 89.98% and an F1-Score value of 82.45%.

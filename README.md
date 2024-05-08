# License_Plate_Blur

In this project, I will show you a model able to recognize license plates and blur the area to keep privacy. The goal of this project is to keep learning about YOLO and OpenCV. 

This model could be useful if you want to show a video of any car on social media and you want to preserve the privacy of the car owner, generally de license plate gives information about the owner and not always is good to share it with everyone. 

The model used to train license plate detector: yolov8n.pt.
Library used in image processing and blurred: OpenCV.

FILES:

•  License_Plate_Detector_Model_Train.ipynb : License plate detector model training.

•  L_P_D_M_Predictor.ipynb : License plate detector model predictior.

•  License_Plate_Blur.opynb : Blured code with OpenCV. 

•  output_1.mp4 and output_3.mp4 : Result of test videos. 


**Conclusion:**

**•  The model works very well, detecting all the license plates.**

**•  For recognizing plates the model needs images or videos with the best quality as be possible, otherwise, distant or not focused cars, don't are recognized.**

**•  I could understand how to obtain boxes information from YOLO, and how to apply it in images trought OpenCV.**


Images:
![FOTO_1](https://github.com/Santi-H-98/License_Plate_Blur/assets/147663147/181b65a1-4600-40cc-a438-6fb73a688c28)
![FOTO_2](https://github.com/Santi-H-98/License_Plate_Blur/assets/147663147/fc977b1d-563b-4a32-b8b0-bd2c1fbfec69)

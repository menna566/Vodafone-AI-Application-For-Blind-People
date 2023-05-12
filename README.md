# Vodafone-Application-For-Blind-People-
## Description :
Our project aims to improve the working environment for blind employeesas as we seek to address the unique challenges that faced them by enabling them to have equal opportunities in the workplace with implementing smart solutions we aim to create an inclusive workspace where blind employees feel valued, supported, and empowered.

## Objective :
The primary challenge is the difficulty of working as a visually impaired or blind individual in Egypt, particularly in the workplace. It becomes challenging to navigate materials, identify people, and locate facilities such as the restroom. Even if one has knowledge of their surroundings, the constant reminders of their disability contribute to a persistent feeling of not belonging in that environment.


## Approach:
Our solution Consists of 4 main things :
1-Object Detection 
2-OCR
3-QR code Detector 
4-Cash Reader

##### -Object Detection :
Our goal is to develop detection Feature in our Application that enables blind individuals to effortlessly navigate their workplace by receiving real-time notifications about their surroundings. 

implementation: We have implemented a real-time object detection that utilizes the MobileNet SSD (Single Shot MultiBox Detector) architecture which incorporates voice feedback to help blind individuals in their workplace. 

and we can see this Feature in our demo below :

https://github.com/menna566/Vodafone-Application-For-Blind-People-/assets/73045024/cdd0950f-d797-4dbe-8526-18c33fd69ff2


##### -OCR :

We have integrated Synapse Analytics OCR (Optical Character Recognition) technology into our implementation. This powerful OCR solution enables our Application to accurately recognize and convert text from various sources and displayes it with voice feedback

this implementation enables Blind individuals to easily extract text, images, and other content from PDF files and convert them into formats that are more compatible with assistive technologies and screen readers. 

and we can see this Feature in our demo below :


https://github.com/menna566/Vodafone-Application-For-Blind-People-/assets/73045024/f943ae68-c94d-4f81-b985-23eb901af4e5


##### -QR Code Detector : 
As part of our implementation, we have incorporated a QR code detection into our solution by utilizing QR code recognition using qr_code_scanner library so the Application can identify and interpret QR code with voice feedback  

This implementation enables Blind individuals to retrieve important data, such as room locations, equipment details, or instructions 

and we can see this Feature in our demo below :

https://github.com/menna566/Vodafone-Application-For-Blind-People-/assets/73045024/0c5493a5-b350-45a9-8f2d-16fd024a255c


##### -Cash Reader :
To train the cash reader model I manually collected a dataset of Egyptian currency and used the Roboflow tool to annotate the labels of the dataset and since the YOLO domain did not include Egyptian currency I added the annotated dataset to the YOLO Domain then I used YOLOv5s to detect the egyptaion currency so that the blind indivduale can know which bancknote they are holding 

and we can see this Feature in our demo below :

![Screenshot 2023-01-29 025509 (1)](https://github.com/menna566/Vodafone-Application-For-Blind-People-/assets/73045024/39dfb497-946f-4a6c-acf0-840eeadbcc9a)

### Future work :
we will provide :
GPS to make the movement easier
currancy detection to all foreign currency
storing customer's data on cloud to help us increase the preformance of our application 

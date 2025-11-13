# Data-Enhancement-to-Improve-CNN-Accuracy-for-Early-Detection-of-Colorectal-Cancer
## APPENDIX
***

## 1. Model Performance Comparison Using VGG 16

![image](https://github.com/user-attachments/assets/ed0958bd-17fa-4450-9894-ef8584d42b99)
***
*Table 1. Comparison With Various Methods Using an Enhanced Dataset*
| Metric                | Class   | VGG 16 | CNN    | MobileNetV2  | Resnet50   | 
|-----------------------|---------|--------|--------|--------------|------------|
| Accuracy              |         | 0.86   | 0.84   |     0.78     |   0.49     | 
| Precision             | Normal  | 0.87   | 0.87   |     0.9      |   0.52     | 
|                       | Polyp   | 0.94   | 0.88   |     0.65     |   0.41     | 
|                       | Cancer  | 0.77   | 0.77   |     0.8      |   0.62     | 
| Recall                | Normal  | 0.84   | 0.74   |     0.87     |   0.48     | 
|                       | Polyp   | 0.89   | 0.97   |     0.78     |   0.54     | 
|                       | Cancer  | 0.84   | 0.8    |     0.67     |   0.47     | 
| F1-Score              | Normal  | 0.85   | 0.8    |     0.89     |   0.5      | 
|                       | Polyp   | 0.91   | 0.92   |     0.70     |   0.46     | 
|                       | Cancer  | 0.8    | 0.78   |     0.73     |   0.53     | 
| AUC (ROC)             | Normal  | 0.97   | 0.95   |     0.98     |   0.72     | 
|                       | Polyp   | 0.99   | 0.99   |     0.79     |   0.57     | 
|                       | Cancer  | 0.94   | 0.93   |     0.89     |   0.76     | 

***

## The results of modeling using the Convolutional Neural Network (CNN) method : 

![image](https://github.com/user-attachments/assets/b8fe8706-3a96-4c75-b819-27e80c0ee2e4)

Training and Validation Accuracy Graph; Training and Validation Loss in the Enhanced Dataset

![image](https://github.com/user-attachments/assets/b7530c41-c939-4d27-a2b3-3d9fe4c13f13)

ROC Curve for Multi-Class from Enhanced Dataset

![image](https://github.com/user-attachments/assets/f0a6500c-d0fa-4c51-a1c3-e73d8fb69711)

Evaluation Matrix of the Enhanced Dataset Models

***
## The results of modeling using the MobileNetV2 method : 

![image](https://github.com/user-attachments/assets/051e6f50-08f1-4fd3-bdaf-701e06862ba1)

Training and Validation Accuracy Graph; Training and Validation Loss in the Enhanced Dataset

![image](https://github.com/user-attachments/assets/60059919-cd85-4aa7-8095-40720ce87f73)

ROC Curve for Multi-Class from Enhanced Dataset

![image](https://github.com/user-attachments/assets/9c20679d-365b-4493-a4e3-4e30452609bc)

Evaluation Matrix of the Enhanced Dataset Models

***
## The results of modeling using Resnet50 method : 

![image](https://github.com/user-attachments/assets/3cbc9df0-5fff-439d-b2a8-4342dac01acd)

Training and Validation Accuracy Graph; Training and Validation Loss in the Enhanced Dataset




![image](https://github.com/user-attachments/assets/d6cac0d2-10a4-44fc-b65a-f0ac5d31031d)

ROC Curve for Multi-Class from Enhanced Dataset

![image](https://github.com/user-attachments/assets/0f1be15a-9b20-42e7-94f9-89e8836b2fc6)

Evaluation Matrix of the Enhanced Dataset Models











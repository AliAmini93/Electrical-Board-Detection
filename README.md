# Electrical-Board-Detection
The Automated Electrical Board Recognition project is initiated by creating an integrated image from overlapping patches of images captured in the first step. This image is then processed by our model to detect and isolate the electrical board.
The main objective of this phase is to generate an image that predominantly features the electrical board, while significantly reducing the presence of the background. This refined image, which primarily features the electrical board with minimal background interference, is then forwarded for further analysis in the subsequent stages of the project.
To enhance the performance of our pre-trained YOLOv8n model, we employ various data augmentation techniques. Data augmentation is a range of techniques used to generate additional training samples by slightly modifying the existing training data. It helps prevent overfitting and enables the model to generalize better.
The dataset used in this phase is composed of 742 images of various boards. These images cover a range of color types, sizes, and perspectives, and often feature multiple, rotated, and overlapped boards. However, we're still in the process of expanding this dataset with additional images, and as such, it's not currently publicly available.
The performance of the trained model is exhibited below. 
![FinalIMG](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/5df89c13-7c16-4460-8e1c-663c260b0f06)
![FinalIMG](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/fe0343b8-4d4a-4263-9646-15f79818a79c)
![93](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/10a8fff3-951b-4c2c-87c2-531d2782a742)
![97](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/65ddc1ea-4327-4433-ba03-b3ea180c6f2f)
![545](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/3f4c0f31-991e-4630-ace5-37c575fba67a)
![val_batch1_pred](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/1d495115-1045-42b1-9a52-c81a8e803161)
![val_batch0_pred](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/dde8edbb-6434-4cbe-8d77-96c21c546d4a)
![val_batch2_pred](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/84c80a2b-4643-4de3-9ac9-77488bd81aa8)
![results](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/775b56be-0ecb-407d-83bb-e6f84cc31607)
![confusion_matrix](https://github.com/AliAmini93/Electrical-Board-detection/assets/96921261/f75fdfec-67e9-485b-b96a-32c62fc709c5)


This project focuses on developing a robust mask detection system utilizing the YOLO (You Only Look Once) object detection algorithm. The primary aim is to accurately identify whether individuals in real-time images or video streams are wearing masks, thereby enhancing public health safety measures, especially in environments where face coverings are mandatory.

The system leverages the YOLO algorithm, renowned for its speed and accuracy in object detection. By analyzing video feeds from security cameras or mobile devices, the model can swiftly detect faces and determine if they are covered by masks. This capability is particularly crucial in crowded settings like public transport, shopping centers, and hospitals, where mask compliance is essential for reducing the spread of infectious diseases.

For this project, a custom dataset was created, consisting of a diverse range of images depicting individuals with and without masks. This dataset was gathered from various sources to ensure a wide representation of different ethnicities, ages, and environments. The images were annotated meticulously to train the YOLO model effectively. The training process involved fine-tuning the model parameters to optimize its detection accuracy, considering various factors such as lighting conditions and angles.

Furthermore, advanced data augmentation techniques were employed to enhance the robustness of the model. These techniques included rotation, scaling, and flipping of images, which helped simulate different real-world scenarios. By doing so, the model became more resilient to variations in the input data, ultimately leading to improved detection performance.

Upon completion, the mask detection system can provide real-time feedback, alerting individuals in cases of non-compliance. This feature can be integrated into existing surveillance systems or used as a standalone application on mobile devices. The project not only emphasizes technological advancement but also contributes to public health efforts by promoting mask-wearing behavior in social settings.

In conclusion, this mask detection project utilizing YOLO represents a significant step forward in leveraging artificial intelligence for health and safety. Its real-time capabilities and high accuracy make it a valuable tool for organizations and communities aiming to ensure compliance with health regulations and protect public health.
---
Here is a Test output prediction of this project :
	 
1.  No wearing mask :
![Screenshot 2024-10-04 231648](https://github.com/user-attachments/assets/0c982c4d-9a0d-421e-99e1-f2e728ea6b67)

2.  Wearing mask :
![Screenshot 2024-10-04 231654](https://github.com/user-attachments/assets/a3acab9a-d162-47d9-bf43-a3647b90884e)

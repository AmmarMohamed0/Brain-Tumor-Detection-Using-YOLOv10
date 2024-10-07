# Brain-Tumor-Detection-Using-YOLOv10

![image alt](https://github.com/AmmarMohamed0/Brain-Tumor-Detection-Using-YOLOv10/blob/18229098f4f6d0ddf2390c1bc8fa885a019c4f48/Screenshot.png)

## Overview
This project demonstrates the use of **YOLOv10** to detect brain tumors in MRI scans. By leveraging the power of the **YOLOv10n** model, the system is capable of accurately identifying and localizing brain tumors in medical images. The model was trained using a custom dataset from **Roboflow**, which contains annotated MRI scans. This project also includes an easy-to-use **Gradio** interface, allowing users to upload MRI images and visualize detection results in real time.

The main goal of this project is to assist in early tumor detection, potentially aiding medical professionals in diagnosing brain tumors more efficiently.

## Features
- **Model**: YOLOv10n (lightweight and efficient version of YOLOv10, optimized for speed and accuracy).
- **Dataset**: High-quality brain MRI images with tumor annotations.
- **Interactive UI**: Includes a **Gradio** interface for uploading images and receiving real-time tumor detection results.
- **Customization**: The model and UI can be adapted to handle different image sizes and confidence thresholds.
- **Results Visualization**: Automatically saves annotated images showing detected tumors.

## Future Improvements
- **Model Fine-Tuning**: Further training on more diverse datasets to improve detection accuracy.
- **Expanded Use**: Integrating additional types of brain scans or other medical imaging modalities.

## Resources
- **YOLOv10 GitHub**: [YOLOv10](https://github.com/THU-MIG/yolov10)
- **Brain Tumor Dataset**: [Roboflow Dataset](https://universe.roboflow.com/brain-mri/mri-rskcu/dataset/3)

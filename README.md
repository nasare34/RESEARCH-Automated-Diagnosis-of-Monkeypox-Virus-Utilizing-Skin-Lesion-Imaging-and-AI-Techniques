# RESEARCH-Automated-Diagnosis-of-Monkeypox-Virus-Utilizing-Skin-Lesion-Imaging-and-AI-Techniques


This repository presents a comprehensive analysis and implementation of deep learning models for Monkeypox classification. The study evaluates the performance of ResNet-50, MobileNetV2, EfficientNetB0, and an ensemble of these models to classify Monkeypox cases accurately. Each model's performance is assessed based on training, validation, and testing metrics, as well as computational complexity, making this work particularly valuable for researchers and practitioners in medical AI.

Models and Results
ResNet-50:

Achieved the highest testing accuracy (94.30%), demonstrating robust performance.
Computationally intensive with 38.77 GFLOPs and ~93.99 MB memory usage, making it ideal for high-resource environments.
MobileNetV2:

Delivered efficient performance with a testing accuracy of 90.35% and only 3.07 GFLOPs.
Best suited for mobile or embedded applications due to its lightweight architecture and fast inference time.
EfficientNetB0:

Balanced model with a testing accuracy of 88.60% and moderate computational complexity (4.01 GFLOPs).
Suitable for environments requiring a trade-off between accuracy and efficiency.
Ensemble Model:

Combined the strengths of individual models, achieving a testing accuracy of 92.98% and a validation accuracy of 88.89%.
Although computationally more demanding, the ensemble approach ensures consistent and superior performance.
Computational Complexity
The models are evaluated for FLOPs, memory usage, and inference times to guide deployment decisions. ResNet-50 offers high accuracy but at a significant computational cost, whereas MobileNetV2 excels in efficiency, making it ideal for real-time applications.
Applications and Future Work
The classification models are designed to aid early detection and monitoring of Monkeypox, particularly in resource-limited settings. Future work will explore further optimization techniques, including quantization and pruning, to enhance deployment feasibility on edge devices.

This repository provides both the codebase and results for reproducibility, fostering collaboration to advance AI for public health challenges.

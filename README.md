# Neural Style Transfer: Transferring Painting Styles

This repository contains an implementation of **Neural Style Transfer**, allowing users to apply the stylistic elements of famous paintings to photographic images while retaining the original color palette of the content images. The project is based on **Gatys et al.**'s algorithm with key modifications to improve color retention and flexibility.

![image](https://github.com/user-attachments/assets/b475fd45-ae66-4db5-89be-3709df3f4325)



## Project Overview

This project uses **Convolutional Neural Networks (CNNs)**(VGG architecture) to merge the content of one image with the style of another. We extend traditional methods by introducing a pre-transfer color alignment process to retain the color integrity of the content image, enabling robust and artistic image transformations.

### Key Features:
- **Style Transfer:** Transforms a content image into a new image by applying the style of a famous painting.
- **New method of Color Retention:** Preserves the original color palette of the content image using a color alignment process trough a linear transformation.
- **Customizable Style and Content Weights:** Fine-tune the balance between style and content using adjustable hyperparameters.


### Final Report:
[Final Report Link](https://github.com/AlejandroUN/Neural-Style-Transfer-project-IMA206/blob/main/final_report.pdf)

### Technologies:
- PyTorch 2.3.0 (for neural network implementation)
- VGGNet-19 (pre-trained on ImageNet)
- Python 3.10
- NumPy 1.26.0
- PyTorch 2.3.0
- PyTorch-cuda 11.8
- Pillow 10.4.0
- TorchVision 0.18.0
- OpenCV 4.8.1



## Contributors

Giovanni Benedetti da Rosa(me)
Paulo Roberto de Moura Júnior
Juan Esteban Rios Gallego
Cristian Alejandro Chávez Becerra

[Original repo](https://github.com/AlejandroUN/Neural-Style-Transfer-project-IMA206)
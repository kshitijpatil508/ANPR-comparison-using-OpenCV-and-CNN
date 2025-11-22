# ANPR Comparison: Classic Image Processing vs. Deep Learning (CNN)

## 🎯 Project Goal

This project provides a direct performance comparison between two distinct approaches for **Automatic Number Plate Recognition (ANPR)**:

1.  **Classic Computer Vision:** Using traditional OpenCV functions (e.g., edge detection, contour finding, morphological operations) for license plate detection.
2.  **Deep Learning:** Utilizing a pre-trained Convolutional Neural Network (CNN) model for more robust, image-contextual detection.

The core objective is to showcase and benchmark the **accuracy**, **robustness**, and **implementation complexity** of both methods on real-world vehicle images.

**Paper Link:** [A Comparative Study of ResNet and U-Net Generator in CycleGAN for Unpaired Image-to-Image Translation](https://www.jetir.org/view?paper=JETIR2105686)

## 🖼️ Results & Comparison

The application is designed to display the detection outputs side-by-side, clearly demonstrating the superior localization and boundary detection capability of the CNN approach under various conditions.

| Description | Output Image |
| :--- | :--- |
| **OpenCV vs. CNN Side-by-Side Comparison** | ![Comparison 1](https://user-images.githubusercontent.com/46442320/122423093-4a6dd000-cfab-11eb-8fa9-55660a1ea694.png) |
| **Detection Accuracy and Bounding Boxes** | ![Comparison 2](https://user-images.githubusercontent.com/46442320/122423119-4fcb1a80-cfab-11eb-9c83-18bf4e77699d.png) |

## ✅ Conclusion

The pre-trained CNN model consistently detects the number plate region more **accurately** and **reliably** compared to the cascade of traditional OpenCV image processing functions. This confirms the advantage of deep learning for complex pattern recognition tasks like ANPR, especially in dealing with variations in lighting, angle, and plate design.

## 🛠️ Technology Stack

### Core Dependencies

  * **Python 3:** Primary development language.
  * **OpenCV:** Used for traditional image processing, feature extraction, and implementing the classical ANPR pipeline.
  * **Deep Learning Framework:** (e.g., **TensorFlow / PyTorch** - *Please specify the exact framework used for the CNN model in your final version*).
  * **Tkinter:** Used to build the graphical user interface (GUI) for displaying the side-by-side results clearly.

### Setup

To set up the project locally, please ensure you have Python 3 installed. All necessary libraries and dependencies can be installed using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt

## 🎓 Related Academic Work (Computer Vision Context)

This project builds upon a strong foundation in deep learning and image translation. For a deeper understanding of related research in GAN architectures, please refer to my published work:
```

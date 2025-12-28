# Automated Face Detection and Extraction System

This project implements an end-to-end computer vision pipeline to detect, crop, and save individual faces from high-density group photos. It leverages the **RetinaFace** architecture for robust detection and **DeepFace** for potential downstream facial recognition tasks.

##  Key Features
* **High-Accuracy Detection:** Utilizes `RetinaFace`, a state-of-the-art sub-pixel face detector, to identify multiple faces in varied lighting and orientations.
* **Automated Extraction:** Automatically crops detected faces and saves them as individual high-quality `.jpg` files for dataset preparation.
* **Visual Validation:** Generates a visualized output with bounding boxes drawn around every detected person in the original image.
* **Recognition Ready:** Includes a modular framework for integration with `DeepFace` models (like ArcFace) for 1:1 or 1:N face verification.

## Tech Stack
* **Language:** Python
* **Libraries:** * `RetinaFace` (Detection)
    * `DeepFace` (Verification Framework)
    * `OpenCV` (Image processing)
    * `Matplotlib` (Visualization)
    * `NumPy` (Data manipulation)

##  Installation
To run this project, you need to install the following dependencies:

```bash
pip install deepface retina-face opencv-python numpy matplotlib

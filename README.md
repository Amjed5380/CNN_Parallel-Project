# Weapon Detection Using YOLO

A computer vision project exploring object detection for identifying the target classes defined in the project dataset using YOLO (You Only Look Once).

> **Project note:** Confirm the exact YOLO version, dataset source, class names, scripts, and commands against the implementation in this repository before publishing. Only describe features that have been implemented and tested.

## 1. Project Overview

The objective of this project is to develop and evaluate an object-detection model using YOLO. The project workflow includes collecting and preparing image data, annotating objects, training the model, validating its performance, running predictions on images and videos, and documenting the results.

## 2. Project Workflow

The work is arranged in the order the project is carried out:

1. Dataset collection and organization
2. Image annotation and dataset preparation
3. Data preprocessing and augmentation
4. YOLO model configuration and training
5. Model testing and validation
6. Performance evaluation
7. Image and video detection
8. Results analysis and documentation

## 3. Team Members and Responsibilities

| No. | Team member | Responsibility |
|---:|---|---|
| 1 | Amjed | Dataset collection and organization |
| 2 | Jisha | Image annotation and dataset preparation |
| 3 | Gouri | Data preprocessing and augmentation |
| 4 | Shahin | YOLO model configuration and training |
| 5 | Chris | Model testing and validation |
| 6 | Arya | Performance evaluation and metrics |
| 7 | Meenakshi | Image and video detection implementation |
| 8 | Adil | Results analysis and project documentation |


## 4. Technologies Used

- Python
- YOLO / Ultralytics (specify the version used)
- OpenCV
- NumPy
- Matplotlib
- Google Colab or a local Python environment
- Git and GitHub

## 5. Installation

Clone the repository:

```bash
git clone https://github.com/Subh775/WeaponDetection.git
cd WeaponDetection
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

Install project dependencies:

```bash
pip install -r requirements.txt
```

Make sure `requirements.txt` lists the packages and versions actually used by the project.

## 6. Dataset Preparation

1. Identify and record the dataset source, licence, and access conditions.
2. Organize images and their corresponding annotation files.
3. Check that annotations use the format expected by the selected YOLO implementation.
4. Split the dataset into training, validation, and test sets.
5. Verify the class names and dataset configuration before training.

Only publish datasets that are permitted to be redistributed. If the dataset cannot be shared, document how authorized users can obtain it.

## 7. Model Training and Prediction

The exact commands depend on the YOLO version and scripts used in this repository. Add the tested commands here once the implementation is confirmed.

The intended stages are:

- Train the selected YOLO model using the prepared dataset.
- Validate the model using the validation split.
- Evaluate the final model on held-out test data.
- Run inference on sample images and videos.
- Save representative outputs for the results section.

## 8. Model Evaluation

Where supported by the selected framework, report:

- Precision
- Recall
- mAP@0.5
- mAP@0.5:0.95
- Confusion matrix
- Inference speed, including the hardware used

## 11. Limitations and Responsible Use

This project is an educational computer-vision demonstration. Model predictions can be incorrect and may vary with image quality, lighting, camera angle, and dataset coverage. The system should not be treated as a reliable basis for real-world enforcement or other high-stakes decisions. Use images and videos in ways that respect privacy, consent, and applicable laws.

## 12. Acknowledgements

We thank all team members for their contributions to dataset preparation, model development, testing, evaluation, and documentation.


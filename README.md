# Brain Tumor Segmentation using U-Net

## Project Description

This project focuses on segmenting brain tumors from medical images using the U-Net architecture, which is widely used for image segmentation tasks.

## Data Processing

- **Input Data**: Training and validation datasets are provided in COCO format (`_annotations.coco.json`), including image info, annotations, and categories.
- **Data Loading**: JSON files are parsed to extract image paths and annotation details.
- **Image Preprocessing**:
  - Load images and corresponding masks.
  - Resize both images and masks to a fixed size (e.g., 128x128).
  - Normalize pixel values to the range [0, 1].

## Model

- **U-Net Architecture**:
  - Built using `Conv2D`, `MaxPooling2D`, `Conv2DTranspose`, and `concatenate` layers to form an encoder–decoder structure.
  - Uses ReLU activation and Binary Crossentropy or Dice Loss as the loss function.

## Result
![image](https://github.com/user-attachments/assets/86bc5036-3c66-4664-a2b1-c6174cf2630a)



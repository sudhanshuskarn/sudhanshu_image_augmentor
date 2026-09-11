# Image Augmentor

A lightweight Python tool for applying image augmentation techniques to datasets used in machine learning and computer vision.

Image Augmentor helps generate variations of existing images through transformations such as rotation, flipping, resizing, cropping, and color adjustments. This can be useful for increasing dataset diversity and preparing image data for machine learning workflows.

## Features

- Resize images
- Rotate images
- Flip images
- Randomly crop images
- Adjust brightness
- Adjust contrast
- Adjust color
- Adjust sharpness
- Support multiple image formats such as JPG and PNG
- Command-line interface for easy usage
- Available as a Python package on PyPI

## Installation

Install the package from PyPI:

```bash
pip install sudhanshu-image-augmentor
```

Python 3.12 or later is required.

## Why Image Augmentation?

Machine learning models, particularly computer vision models, can benefit from diverse training data.

Image augmentation creates modified versions of existing images while preserving their underlying content. These transformations can help expand a dataset and expose a model to greater visual variation during training.

For example, a single image can be transformed using:

```text
Original Image
      │
      ├── Rotation
      ├── Horizontal / Vertical Flip
      ├── Random Crop
      ├── Resize
      ├── Brightness Adjustment
      ├── Contrast Adjustment
      ├── Color Adjustment
      └── Sharpness Adjustment
```

## Use Cases

Image Augmentor can be useful for:

- Preparing image datasets for machine learning
- Computer vision experiments
- Increasing training-data diversity
- Image preprocessing workflows
- Rapid dataset augmentation from the command line

## Package

The project is published on PyPI as:

**sudhanshu-image-augmentor**

Install it using:

```bash
pip install sudhanshu-image-augmentor
```

## Tech Stack

- Python
- Pillow
- PyPI packaging

## Project Status

The current published version is **0.2**.

This project was created as a lightweight implementation of common image augmentation operations and packaged for distribution through PyPI.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

**Sudhanshu Shekhar Karn**

- GitHub: [@sudhanshuskarn](https://github.com/sudhanshuskarn)
- PyPI: [sudhanshu-image-augmentor](https://pypi.org/project/sudhanshu-image-augmentor/)

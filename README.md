# Flower Segmentation

This project focuses on image segmentation using the Oxford Flower102 dataset.

## Overview

The project includes the following main components:

1. **Dataset Download**:
    - Running the initial cells of the `Flower_segmentation.ipynb` notebook will download the Oxford Flower102 dataset. 
    - Note: An internet connection is required for downloading the dataset.

2. **Exploratory Data Analysis (EDA)**:
    - The `eda.ipynb` notebook provides an in-depth exploratory data analysis of the downloaded dataset.

3. **Model Training and Fine-Tuning**:
    - The training and fine-tuning of the model are performed in the `Flower_segmentation.ipynb` notebook.

## Dataset

The dataset used is the Flowers102 dataset provided by Oxford.

## Dependencies

All required dependencies are listed in the `requirements.txt` file. Ensure you have these installed to run the notebooks successfully.

Notebooks use the FastAI/PyTorch framework

## References

[1] Oxford Flowers102 dataset
```@InProceedings{Nilsback08,
  author       = "Maria-Elena Nilsback and Andrew Zisserman",
  title        = "Automated Flower Classification over a Large Number of Classes",
  booktitle    = "Indian Conference on Computer Vision, Graphics and Image Processing",
  month        = "Dec",
  year         = "2008",
}```

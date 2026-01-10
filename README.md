# 2D Cell Segmentation and Morphology Analysis

This project implements a Python-based pipeline to analyze 2D brightfield
microscopy images of cardiac cells. The pipeline automatically segments
individual cells, counts cells per image, and extracts interpretable
single-cell morphology features (e.g., area, circularity, aspect ratio).

## Project Structure
- data/raw/        Raw microscopy images (JPG)
- notebooks/       Jupyter notebooks for exploration and development
- src/             Reusable Python functions for segmentation and analysis
- outputs/         CSV outputs and quality-control images

## Environment Setup
This project uses a conda environment named `organoid`.

To recreate the environment:
```bash
conda env create -f environment.yml
conda activate organoid

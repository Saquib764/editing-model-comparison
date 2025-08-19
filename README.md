# Editing Model Comparison

This repository contains a Python notebook script to compare the performance and capabilities of different image editing models, specifically **Flux Kontext** and **Qwen Image Edit**.

## Overview

The notebook `character_insert.ipynb` provides a comprehensive comparison framework for evaluating image editing models, allowing users to:
- Test and compare image editing capabilities
- Analyze model performance on various editing tasks
- Evaluate output quality and consistency
- Benchmark different approaches to image manipulation

## Repository Structure

```
editing-model-comparison/
├── character_insert.ipynb      # Main comparison notebook
├── example_data/               # Sample images and text for testing
│   ├── coffee.png             # Example image file
│   ├── coffee.txt             # Example text file
│   └── scene_01.png           # Example scene image
├── outputs/                    # Generated outputs and results
└── README.md                   # This file
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd editing-model-comparison
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook character_insert.ipynb
   ```

## Models Compared

### Flux Kontext
- Advanced image editing capabilities
- Context-aware image manipulation
- High-quality output generation

### Qwen Image Edit
- State-of-the-art image editing performance
- Efficient processing and generation
- Robust editing algorithms

## Usage

The notebook is structured to:
1. Load and prepare example data
2. Apply editing operations using both models
3. Save the outputs in the `outputs/` directory

## Example Data

The `example_data/` directory contains sample images and text files that can be used to test the models' capabilities. Feel free to add your own test data for custom comparisons.

## Outputs

Results and generated images are saved in the `outputs/` directory, allowing for easy comparison and analysis of model performance.


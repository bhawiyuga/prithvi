# Prithvi 2.0 100M Model Inference

This project demonstrates how to run inference using the Prithvi 2.0 100M model with raster TIF files.

## Setup

This project uses `uv` for environment management. To set up the environment:

```bash
# Create a virtual environment
uv venv

# Install dependencies
uv sync

```

## Contents
- `inference.py`: Python script for running inference using the Prithvi 2.0 100M model
- `prithvi_inference.ipynb`: Jupyter notebook for exploring the Prithvi 2.0 100M model
- `requirements.txt`: Dependencies required for the project

## Usage

1. Set up the environment as described above
2. Run the inference script: `uv run python inference.py --rgb_outputs`
3. Follow the instructions in the script to run inference on sample TIF files

## About Prithvi 2.0

Prithvi 2.0 is a foundation model for geospatial AI developed by IBM and NASA. The 100M version is a smaller variant that can be used for various geospatial tasks including classification and feature extraction from satellite imagery.

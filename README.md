# AdaIN-Style-Transfer

A real-time Neural Style Transfer web application built using PyTorch and Flask.  
This project uses Adaptive Instance Normalization (AdaIN) to blend the artistic style of one image with the content of another while preserving structural details.

## Features

- Real-time Neural Style Transfer
- Adjustable style strength slider
- Interactive modern UI
- Image preview before transfer
- GPU/CPU inference support
- Custom trained decoder model
- Multiple artistic style examples
- Flask-based web deployment

## Tech Stack

- Python
- PyTorch
- Flask
- HTML/CSS/JavaScript
- Bootstrap

## Model Architecture

The project is based on:
- Encoder: VGG19 feature extractor
- AdaIN layer for feature alignment
- Decoder network trained for image reconstruction

## How It Works

1. Extract content features
2. Extract style features
3. Apply Adaptive Instance Normalization (AdaIN)
4. Blend features using alpha control
5. Generate stylized image through decoder
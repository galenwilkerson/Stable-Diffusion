# Stable Diffusion in Google Colab

This repository contains a Google Colab notebook for generating images using the Stable Diffusion model. The notebook leverages the `diffusers` library from Hugging Face to create images based on textual descriptions.

## Repository Location

[https://github.com/galenwilkerson/Stable-Diffusion](https://github.com/galenwilkerson/Stable-Diffusion)

## Features

- Generate images from text descriptions using a pre-trained Stable Diffusion model.
- Customize image size and number of diffusion steps for faster inference.
- Display generated images directly in the notebook.

## Getting Started

To get started with the notebook, follow these steps:

### 1. Open the Notebook in Google Colab

Click the link below to open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/galenwilkerson/Stable-Diffusion/blob/main/Stable_Diffusion_2.ipynb)

### 2. Install Necessary Libraries

The notebook will guide you through installing the required libraries. The following libraries are needed:
- `diffusers`
- `transformers`
- `torch`
- `accelerate`
- `pillow`

You can install them by running the following cell in the notebook:

```python
!pip install diffusers transformers torch accelerate pillow
```

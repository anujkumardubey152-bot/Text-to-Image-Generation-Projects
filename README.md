# Text-to-Image-Generation-Projects
# Text-to-Image Generation Internship

## Overview
This repository contains my internship project on Text-to-Image Generation. The project builds on the training tasks by implementing multiple deep learning models and techniques for image generation, text preprocessing, and dataset analysis.

## Problem Statement
The objective of this project is to develop and evaluate different deep learning approaches for generating images from text descriptions and understanding the complete text-to-image generation pipeline.

## Dataset
- Oxford 102 Flowers Dataset
- Custom geometric shapes dataset (for Conditional GAN)
- Text data processed using Hugging Face tokenizers

## Methodology

### Task 1: Stable Diffusion Fine-Tuning
- Fine-tuned a Stable Diffusion model.
- Generated flower images from text prompts.

### Task 2: Conditional GAN
- Implemented a Conditional GAN for generating geometric shapes.
- Generated circle, square, and triangle images.

### Task 3: Text Preprocessing using Hugging Face
- Tokenized and encoded text using Hugging Face Transformers.
- Saved encoded tensors for model input.

### Task 4: Dataset Analysis
- Performed exploratory analysis on the Oxford 102 Flowers dataset.
- Visualized dataset characteristics.

### Task 5: Self-Attention GAN
- Implemented a Self-Attention GAN architecture.
- Trained the generator and discriminator models.

### Task 6: Text-to-Image Pipeline
- Combined text preprocessing and image generation into a complete pipeline.
- Generated multiple images from text prompts.

## Repository Structure

```
01_Stable_Diffusion_Fine_Tuning.zip
02_Conditional_GAN.zip
03_Text_Preprocessing_HuggingFace.zip
04_Dataset_Analysis.zip
05_Self_Attention_GAN.zip
06_Text_to_Image_Pipeline.zip

README.md
```

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Stable Diffusion
- GAN
- Self-Attention GAN
- NumPy
- Matplotlib
- Google Colab

## Results
- Successfully fine-tuned Stable Diffusion.
- Generated images using Conditional GAN.
- Implemented text preprocessing with Hugging Face.
- Completed dataset analysis.
- Built a Self-Attention GAN.
- Developed a complete Text-to-Image generation pipeline.

## How to Run
1. Extract the required task ZIP file.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the corresponding Jupyter Notebook (`.ipynb`) in Google Colab or Jupyter Notebook.
4. Run the notebook cells sequentially.

## Author
**Anuj Kumar Dubey**
B.Tech CSE
IERT Prayagraj

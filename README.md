# 🧠 Image Generation with Pre-trained Models

This project demonstrates the use of pre-trained generative models like **Stable Diffusion** to generate images from natural language text prompts. It was completed as part of my internship at **Prodigy InfoTech**.

## 🚀 Task Overview

**Task-02: Image Generation with Pre-trained Models**

- Utilized HuggingFace's 🤗 `diffusers` library to access the `StableDiffusionPipeline`.
- Executed the model within a Google Colab environment for smooth computation.
- Generated images based on custom user input prompts.
- Focused on ease of use, reproducibility, and learning through experimentation.

## 📌 Technologies Used

- Python 🐍
- Google Colab 📓
- HuggingFace Transformers 🤗
- Stable Diffusion (`CompVis/stable-diffusion-v1-4`)
- PyTorch + PIL + Matplotlib

## 📷 How It Works

1. Load the pre-trained Stable Diffusion pipeline from HuggingFace.
2. Accept text input from the user.
3. Generate an image based on the input prompt.
4. Display the generated image using Matplotlib.

## 📥 User Input Example

```python
prompt = input("Enter your prompt: ")

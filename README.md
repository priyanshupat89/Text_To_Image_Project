

# 🖼️ Text-to-Image Generator using Stable Diffusion (Google Colab)

This project is a **Text-to-Image Generator** built with the **Stable Diffusion v1-4** model from Hugging Face. It takes a natural language prompt and generates a high-quality image that matches the description. Designed to run on **Google Colab**, the project requires no local setup and utilizes GPU acceleration for efficient image generation.

---

## 🚀 Try it on Google Colab

Click the badge below to open and run the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/text-to-image-colab/blob/main/text_to_image.ipynb)

> **Note:** Replace the URL above with your actual GitHub notebook link after uploading.

---

## 📌 Features

- ✔️ Generate stunning images from text prompts
- ⚡ Fast inference using GPU on Google Colab
- 🎨 Uses the `StableDiffusionPipeline` from 🤗 Hugging Face
- 🧠 Leverages pretrained models (`CompVis/stable-diffusion-v1-4`)

---

## 🛠️ Tech Stack

- **Platform:** Google Colab
- **Language:** Python
- **Core Libraries:**
  - `diffusers`
  - `transformers`
  - `torch`
  - `accelerate`
  - `safetensors`
  - `Pillow` (`PIL`)

---

## 🔧 Setup Instructions

1. **Open the notebook in Google Colab**
2. **Enable GPU:**
   - Go to `Runtime` > `Change runtime type`
   - Set **Hardware accelerator** to `GPU`
3. **Run all cells**

> All necessary packages will be installed automatically using pip.

---

## 🧪 Sample Prompt

```python
prompt = "sunset over ocean with mountains"



# 🖼️ Text-to-Image Generator using Stable Diffusion (Google Colab)

This project is a **Text-to-Image Generator** built with the **Stable Diffusion v1-4** model from Hugging Face. It takes a natural language prompt and generates a high-quality image that matches the description. Designed to run on **Google Colab**, the project requires no local setup and utilizes GPU acceleration for efficient image generation.

---

## 🚀 Try it on Google Colab

Click the badge below to open and run the notebook in Google Colab:

https://github.com/priyanshupat89/Text_To_Image_Project/blob/main/text_to_image.ipynb


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

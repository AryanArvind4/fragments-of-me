# 🎨 Fragments of Me

**Fragments of Me** is an AI-powered art generation project that transforms emotions into visual art. Users describe how they're feeling, choose from five assistant styles, and receive AI-generated artwork using GPT-4 for prompt enhancement and Stable Diffusion for image generation.

## 🧠 How it Works

1. The user provides a short emotional reflection (e.g., dreams, feelings).
2. A style persona (e.g., *Dream Translator* or *Visual Storyteller*) is selected.
3. GPT-4 enhances the raw input into a symbolic, artistic prompt.
4. Stable Diffusion (via `diffusers`) generates the corresponding image.
5. Everything is served through a Gradio interface.

## 🚀 Demo

Run the notebook using **Google Colab**:
> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

Or clone and run locally:
```bash
git clone https://github.com/your-username/fragments-of-me.git
cd fragments-of-me
pip install -r requirements.txt
python fragments-of-me-final.ipynb

# Comprehensive_AI
An end-to-end AI system integrating a conversational chatbot, image recognition, speech processing, and image generation using Hugging Face models and Gradio interface.

<h1 align="center">
  <img src="https://tenor.com/view/cats-cat-computer-gif-15556901.gif" alt="Coding GIF">
</h1>

---

## AI Multimodal System with Chatbot, Vision, Speech, and Image Generation

This project is a comprehensive, multimodal AI system that combines several state-of-the-art deep learning models to deliver a seamless and intelligent user interaction experience. At its core, the system features a powerful conversational agent based on **Llama-3.2-3B-Instruct**, a fine-tuned large language model (LLM) developed by Meta and hosted on Hugging Face. 

The system further incorporates:

- 🖼️ **Object Detection and Recognition** using pretrained vision models
- 🗣️ **Text-to-Speech (TTS)** for human-like audio responses
- 🎙️ **Automatic Speech Recognition (ASR)** for speech-to-text conversion
- 🎨 **Image Generation** (bonus feature) through natural language prompts
- 🖥️ **Interactive Graphical Interface** built with Gradio for intuitive use

All components are integrated into a single user-friendly interface, allowing users to chat via text or voice, upload images for analysis, listen to AI responses, and even generate AI art—all in one place.

### Features

- Chat in real time with the AI assistant powered by **Llama-3.2-3B-Instruct**
- Upload an image and get labeled object predictions
- Hear the AI's responses through speech synthesis
- Speak to the AI system via voice input using ASR
- Generate creative images from text prompts (optional feature)

### Tools & Frameworks

- Hugging Face Transformers (LLM, ViT, Wav2Vec2, SpeechT5)
- Gradio for GUI and interactivity
- Python, PyTorch
- Google Colab (for cloud execution)

### Project Structure


#### Main notebook with code implementation 

📁 /Model.ipynb

#### Image generation LLM

📁 /bot

## How to Run

> You can run the system directly in Google Colab.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/your_colab_link_here)

## References

- [Hugging Face](https://huggingface.co/)
- [Llama-3.2-3B-Instruct](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct)
- [Gradio](https://gradio.app/)
- [Transformers Documentation](https://huggingface.co/docs/transformers/index)

---

> Created as part of an academic project on multimodal deep learning systems.

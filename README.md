# Image-Captioning-Model
This project implements an advanced image captioning model using the BLIP (Bootstrapping Language-Image Pretraining) processor, enhanced with text-to-speech capabilities. The model generates descriptive captions for images and provides an audio summary of the output, creating a multimodal interaction experience.

🚀 Features
🔍 Image Captioning using the BLIP Processor from Hugging Face

🧠 Vision-Language Pretrained Model for high-quality caption generation

🗣️ Text-to-Speech Conversion of captions and summaries

📦 Easy-to-use interface for image input and output

🧪 Jupyter Notebook and script-based demo options

🧰 Tech Stack
Python 3.8+

Transformers and BLIP Processor (Salesforce/blip-image-captioning-base)

PyTorch

Text-to-Speech (TTS libraries such as pyttsx3, gTTS, or TTS by coqui-ai)

Gradio (optional) for UI deployment

📸 How It Works
Load an image through a simple UI or script.

The image is processed through the BLIP model to generate a textual description.

The generated caption is converted to speech.

The result includes:

Raw caption text

Spoken audio output of the caption

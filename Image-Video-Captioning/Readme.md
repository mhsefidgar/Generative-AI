# 🧠 Image-Video-Captioning

Welcome to **Image-Video-Captioning**, an open-source project that brings powerful vision-language models to your fingertips! This repo allows you to generate **descriptive, context-aware captions** for both **images and videos**, leveraging the latest advancements in multimodal AI.

## 🚀 Key Features

- 🔍 **Image & Video Captioning**: Generate accurate and detailed captions for both static and dynamic visual content.
- 🤖 **State-of-the-Art Models**: Plug and play with top-tier vision-language models like:
  - **Qwen-VL-Max 2.5 (3B)** – Alibaba's powerful vision-language model for image understanding and captioning.
  - **BLIP / BLIP-2** – Pretrained models that combine vision and language pretraining with fine-tuning for captioning.
  - More models coming soon!
- 🧩 Modular & Extensible: Easily swap in different models and backends.
- 📦 Lightweight Setup: Minimal dependencies and optimized runtime, even on modest hardware.

## ✨ Demo Previews

| Image Input | Caption Output |
|-------------|----------------|
| 🏞️ Nature Scene | "A peaceful forest landscape with trees turning golden under the afternoon sun." |
| 🎥 Short Video Clip | "A child playing with a dog in a sunny park while birds fly overhead." |

## 🏗️ Model Overview

| Model        | Type        | Parameters | Strengths                           |
|--------------|-------------|------------|-------------------------------------|
| Qwen-VL 2.5  | Vision-Language | 3B         | Multi-modal, multilingual, detailed captions |
| BLIP         | Vision-Language | ~1B       | Fast and lightweight, great on single images |
| BLIP-2       | Vision-Language | Varies    | More fluent and reasoning-aware descriptions |

## 🧠 How It Works

1. **Preprocess** your image or video frames.
2. **Select** a model (e.g., Qwen-VL 2.5, BLIP).
3. **Run inference** to generate one or more natural language captions.
4. Optionally, **refine** or **post-process** the output for your use-case (e.g., accessibility, metadata, storytelling).

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/image-video-captioning.git
cd image-video-captioning
pip install -r requirements.txt

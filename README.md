# MFA-Image_generation-
# 🎨 Multi-Agent Image Generation System using CrewAI & Stability AI

This project showcases a **multi-agent autonomous system** designed to generate high-quality images from text prompts. It leverages the power of [**CrewAI**](https://crewai.com) for multi-agent orchestration and [**Stability AI**](https://platform.stability.ai/) for realistic image generation via Stable Diffusion.

> 🤖 Prompt Engineers + Art Directors + Image Generators = Smarter Image Creation Pipeline

---

## 📌 Features

- 🤖 Multi-agent architecture using CrewAI
- 🎨 Text-to-image generation with Stability AI API
- 🛠️ Modular design (add/remove agents easily)
- 🔁 Iterative feedback loop between agents
- 📂 Auto-save outputs and conversation logs

---

## 🚀 Use Case

This system simulates how collaborative AI agents can take a vague user prompt, refine it through prompt engineering, and generate visual outputs. It's useful for:
- Designers and content creators
- Rapid concept art generation
- AI agent orchestration demonstrations
- Educational purposes

---

## 📦 Tech Stack

- **Python 3.10+**
- [CrewAI](https://github.com/joaomdmoura/crewAI)
- Stability AI API
- OpenAI or other LLMs (optional)
- dotenv for environment management

---

## 🧠 How It Works

1. **User Input Agent**  
   Receives a natural language prompt from the user.

2. **Prompt Engineer Agent**  
   Refines and optimizes the prompt for image generation.

3. **Art Director Agent (optional)**  
   Reviews and improves prompt creativity or coherence.

4. **Image Generator Agent**  
   Calls the Stability AI API with the refined prompt and returns the generated image.

5. **Critic Agent (optional)**  
   Evaluates output quality and triggers feedback loops if needed.

---

## 📸 Demo

![example-output](./outputs/sample_image.png)

> Prompt: _“A futuristic city skyline at dusk, in cyberpunk style”_

---

## 🧪 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/multi-agent-image-generator.git
cd multi-agent-image-generator
pip install -r requirements.txt

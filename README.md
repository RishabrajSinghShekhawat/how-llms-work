# 🧠 How Large Language Models (LLMs) Work — Interactive Visual Masterclass

An interactive, visual, beginner-to-advanced deep dive into how Large Language Models (ChatGPT, Claude, Gemini, Llama) understand, process, and generate human thought.

![LLM Masterclass Preview](https://img.shields.io/badge/Status-Live%20Ready-emerald?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🚀 Live Interactive Features

1. **Subword Tokenization (BPE)**: Live interactive input converting natural language into tokens and model vocabulary IDs.
2. **2D Semantic Embedding Space**: Interactive coordinate map with draggable vectors and vector arithmetic ($\text{King} - \text{Man} + \text{Woman} \approx \text{Queen}$).
3. **Self-Attention Heatmap**: Interactive matrix demonstrating how the Transformer disambiguates pronouns and polysemous words.
4. **Softmax Sampling & Temperature Sandbox**: Live simulation of logit distribution and temperature tuning with autoregressive next-token prediction.
5. **The 3 Stages of Training**: Visual explanation of Pre-training, Supervised Fine-Tuning (SFT), and RLHF / DPO alignment.
6. **Concept Glossary & Interactive Quiz**: 4-question interactive assessment with dynamic feedback and score certification.

---

## 🛠️ Local Development

Clone the repository and launch the app in any browser or with any static server:

```bash
# Clone the repository
git clone https://github.com/<your-username>/how-llms-work.git
cd how-llms-work

# Open directly in browser
open index.html

# Or run via Python local server
python3 -m http.server 3000
```

Visit `http://localhost:3000` to interact.

---

## ⚡ Deployment to Vercel

This repository is pre-configured with `vercel.json` for zero-configuration deployment:

1. Import this repository into [Vercel](https://vercel.com).
2. Leave the build settings as default (Static).
3. Click **Deploy**.

---

## 📄 License
MIT License. Open for educational and community use.

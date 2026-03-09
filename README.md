# Generative AI Overview

**A high-level, living overview of how modern Generative AI is built — from pretraining to post-training.**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lion-of-naples/Generative-AI-Overview/blob/main/Public_Facing_GenerativeAI.ipynb)

---

## Summary

This repository contains a **living document** maintained by a committee of experts. The goal is to provide a clear, digestible overview of the current state of Generative AI and how LLMs are built end to end.

- **Three-part framework:** Pre-training → Post-training (SFT) → Post-training (RL)
- **Research tool:** [Perplexity.ai](https://perplexity.ai) is used as a primary research and reference tool
- **Focus groups:** Each major section has an associated focus group where members can go deeper, discuss breakthroughs, and contribute back to this overview
- **Breakouts:** As the field evolves, we document breakthroughs and link to more detailed notebooks and resources

Whether you're new to GenAI, preparing talks or courses, or aligning with engineering teams, this overview gives you the structure and vocabulary to understand how models are trained and deployed.

---

## What's Covered

| Section | Description |
|--------|-------------|
| **Generative AI in three parts** | Pre-training, Supervised Fine Tuning (SFT), and Reinforcement Learning (RL) — with simple analogies |
| **Pretraining** | Datasets (e.g. Fineweb, Common Crawl), encoding & tokenization, transformer architecture, and inference |
| **Post-training: SFT** | Supervised fine tuning with human (and LLM) feedback; conversation data and ideal responses |
| **Post-training: RL** | Human-based RL (e.g. RLHF) and full reinforcement learning (e.g. DeepSeek-style “thinking” and chain-of-thought) |
| **Glossary** | Definitions for AI, GenAI, LLM, tokenization, transformer, inference, context window, base model, SFT, RLHF, epoch, loss — with Perplexity links for more context |

---

## Quick Start

### Run in the browser (no install)

**[Open the notebook in Google Colab](https://colab.research.google.com/github/lion-of-naples/Generative-AI-Overview/blob/main/Public_Facing_GenerativeAI.ipynb)** — no clone or setup required.

### Run locally

```bash
# Clone the repository
git clone https://github.com/lion-of-naples/Generative-AI-Overview.git
cd Generative-AI-Overview

# Open the notebook in Jupyter, VS Code, or Cursor
# e.g.:
jupyter notebook Public_Facing_GenerativeAI.ipynb
```

No Python dependencies are required to read the notebook; it is markdown and images. Optional: install [Jupyter](https://jupyter.org/) or open the `.ipynb` in an editor that supports notebooks.

---

## Project Structure

```
Generative-AI-Overview/
├── README.md                      # This file
├── Public_Facing_GenerativeAI.ipynb   # Main overview notebook
└── (focus-group signup and breakout links are inside the notebook)
```

The notebook includes signup links for focus groups (Pretraining, Encoding, Transformer, Base Model, SFT, Post-training RL). Use the table of contents inside the notebook to jump to each section and glossary.

---

## Contributing

We welcome contributions and new focus-group members:

- **Focus groups:** Each section in the notebook has an associated focus group. Signup links are in the notebook; join a group to go deeper and contribute.
- **Breakouts:** As we add or reference more detailed notebooks and resources, we link them from this overview.
- **Suggestions:** Open an issue or pull request to propose changes to the overview or the README.

---

## References & Tools

- **Perplexity.ai** — [Sign up](https://perplexity.ai) — used as a primary research and reference tool in this overview
- **Fineweb** — [Hugging Face](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1) — open pretraining dataset discussed in the notebook
- **Common Crawl** — [commoncrawl.org](https://commoncrawl.org) — open web data used by many pretraining pipelines
- **Attention is all you need** — [arXiv:1706.03762](https://arxiv.org/pdf/1706.03762) — seminal transformer paper

---

## License

Content in this repository is maintained for educational and community use. See the repository and notebook for any specific license or attribution requirements.

---

*From pretraining to post-training — a shared overview of how Generative AI is built.*

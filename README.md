# Deep Learning (M.Sc.) — SRH

Slides and lab notebooks for the course. Material for each day is added on that day; solutions are released after the lab.

**Lecturer:** Annika Stiehl, Hochschule Ansbach — [annika.stiehl@hs-ansbach.de](mailto:annika.stiehl@hs-ansbach.de)

| Day | Topic | Slides | Lab | Solutions |
|---|---|---|---|---|
| 1 | Foundations & linear networks | [PDF](slides/day1.pdf) | Lab 1 [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/annikastiehl/srh-deep-learning/blob/main/notebooks/day1_linear_networks.ipynb)<br>Lab 1b [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/annikastiehl/srh-deep-learning/blob/main/notebooks/day1b_eeg_pipeline.ipynb) | Lab 1 [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/annikastiehl/srh-deep-learning/blob/main/solutions/day1_linear_networks_solution.ipynb) |

## Group project

[Project guidelines (PDF)](project/project_guidelines.pdf) — task, datasets, evaluation, deliverables, milestones and rules (incl. use of AI assistants). Submission of short paper + code: **10 November 2026** · poster session (portrait format): **11 November 2026**.

## Working in Google Colab

1. Click **Open in Colab** next to the lab.
2. **File → Save a copy in Drive** — otherwise your changes are lost when the session ends.
3. **Runtime → Change runtime type → T4 GPU.**
4. The free tier limits GPU time per day: debug on small data or on CPU first, then switch to the GPU.

## Try it in your browser (no GPU, no install)

**Day 1**
- [TensorFlow Playground](https://playground.tensorflow.org) — watch a small network learn (XOR, hidden layers, learning rate)
- [Teachable Machine](https://teachablemachine.withgoogle.com) — train an image or audio classifier with your webcam / microphone
- [3Blue1Brown: Neural networks](https://www.3blue1brown.com/topics/neural-networks) — visual intuition for networks, gradient descent and backpropagation
- [Seeing Theory](https://seeing-theory.brown.edu) — probability and regression, interactive

**Later in the course**
- [Why Momentum Really Works](https://distill.pub/2017/momentum/) (Distill) — gradient descent with momentum, interactive (day 3)
- [CNN Explainer](https://poloclub.github.io/cnn-explainer/) — convolutions, feature maps, pooling (day 4)
- [Transformer Explainer](https://poloclub.github.io/transformer-explainer/), [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/), [LLM Visualization](https://bbycroft.net/llm) — attention and transformers (outlook, day 6)
- [GAN Lab](https://poloclub.github.io/ganlab/) — train a GAN on 2D data and watch it evolve (day 7)
- [Diffusion Explainer](https://poloclub.github.io/diffusion-explainer/) — Stable Diffusion step by step (day 7)
- [Embedding Atlas](https://apple.github.io/embedding-atlas/) — explore clusters and outliers in embedding spaces (day 7)
- [PAIR AI Explorables](https://pair.withgoogle.com/explorables/), [Neuronpedia](https://www.neuronpedia.org/) — generalisation, interpretability, model behaviour (day 8)
- [Distill](https://distill.pub/) — visual essays on ML and interpretability

**Beyond this course: LLMs**
- [Transformer concepts](https://www.abhik.ai/concepts/transformers) (Abhik Sarkar) — RoPE, KV cache, FlashAttention, MQA/GQA
- [A Visual Guide to Attention Variants in Modern LLMs](https://magazine.sebastianraschka.com/p/visual-attention-variants) (Sebastian Raschka) — MHA, MQA, GQA, MLA
- [A Visual Guide to Mixture of Experts](https://www.maartengrootendorst.com/blog/moe/) (Maarten Grootendorst)
- [LLM Inference Handbook](https://handbook.modular.com/) (Modular) — prefill, decode, KV cache, batching, quantisation

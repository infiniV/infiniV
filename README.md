# Raahim Arbaz

I teach computers to watch surgery.

My day job is at [GrayScrubsAI](https://www.grayscrubsai.com/), where I lead the computer vision work for a clinical monitoring product. Training YOLO11 and SAM, running the annotation team that feeds those models, and shipping the whole thing to Jetsons sitting in ICUs. On the side I write full-stack code for Arantic Digital out of Munich.

[infiniv.dev](https://www.infiniv.dev) · [linkedin](https://www.linkedin.com/in/raahim-arbaz) · [raahim.arbaz22@gmail.com](mailto:raahim.arbaz22@gmail.com)

## Things I've put on the internet

**[VoiceFlow](https://github.com/infiniV/VoiceFlow)** · 345 stars
Local-first dictation on faster-whisper. Runs on your GPU. Nothing leaves the machine.

**[Vision-Dissect](https://github.com/infiniV/Vision-Dissect)**
Cracks open computer vision models. Layer activations, attention maps, side-by-side runs across YOLO11, SAM, and DepthPro. I built it to figure out what our production models were actually looking at.

**[ultra-instinct-claude-code](https://github.com/infiniV/ultra-instinct-claude-code)** · 15 stars
I read 17 Claude Code repos (500k+ stars between them) so you don't have to. 176 tips, tagged by difficulty, nothing to install.

## Research

**Mapping Air Pollution Sources with Sequential Transformer Chaining**
*NeurIPS 2024 Climate Change AI Workshop* · [paper](https://www.climatechange.ai/papers/neurips2024/6/paper.pdf) · [arXiv](https://arxiv.org/abs/2410.19629)

We chained a Vision Transformer with Remote CLIP to find factory and brick-kiln chimneys in South Asian satellite imagery. Filtered a 600K-image dataset down to the 1% that actually had pollution sources, then lined that 1% up against respiratory-illness data.

## One thing I keep relearning

Most of ML isn't the model. The model is the easy part. It's the annotation protocol, the pipeline that doesn't break on Thursday, and whether the hardware a customer already paid for can actually hit 30fps. Fix those and the architecture is swappable. Mess up the labels and you're still cleaning it up next quarter.

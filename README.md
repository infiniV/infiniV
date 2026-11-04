# Raahim Arbaz

Computer vision engineer, based in Lahore. I do some research on the side and build the tooling I end up using.

[![Portfolio](https://img.shields.io/badge/infiniv.dev-000000?style=flat-square)](https://www.infiniv.dev/)
[![LinkedIn](https://img.shields.io/badge/linkedin-000000?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/raahim-arbaz)
[![Email](https://img.shields.io/badge/contact-000000?style=flat-square&logo=gmail)](mailto:raahim.arbaz22@gmail.com)

## What I'm up to

CV founding engineer at a clinical computer vision startup. I lead the annotation team, research new architectures, and run deployment and testing on edge hardware.

## Projects

| Project | About | Stack |
|---------|-------|-------|
| **[VoiceFlow](https://github.com/infiniV/VoiceFlow)** | Local voice dictation on faster-whisper. Runs on your GPU, nothing leaves your machine. | `Python` `faster-whisper` `Pyloid` |
| **[Vision-Dissect](https://github.com/infiniV/Vision-Dissect)** | Cracks open CV models to compare layer activations and attention maps across YOLO11, SAM, and DepthPro. | `PyTorch` `ONNX` `Transformers` |
| **[Android-Ui-MCP](https://github.com/infiniV/Android-Ui-MCP)** | MCP server for Android UI automation and testing workflows. | `TypeScript` `MCP` |
| **[ultra-instinct-claude-code](https://github.com/infiniV/ultra-instinct-claude-code)** | 176 Claude Code tips distilled from 17 repos and 500k+ stars. Tagged by difficulty, nothing to install. | `Research` `Docs` |

## Research

**Why does π₀ forget to speak? Model stitching locates different captioning failures in π₀ and π₀.₅**  
UniReps 2026 (NeurIPS workshop). Accepted. Lead author.

Robot VLAs fine-tuned from PaliGemma stop captioning images. Swapping layers between each VLA and its parent, stitching their hidden states together with linear maps, and probing the image tokens showed the loss sits in different places: π₀'s image tokens lose object content, while π₀.₅ keeps usable representations but its output head and prompt no longer read them. Key tests pre-registered on sealed COCO sets.

**Mapping Air Pollution Sources with Sequential Transformer Chaining**  
NeurIPS 2024 Climate Change AI Workshop. Second author.

Chained Vision Transformers with Remote CLIP to find factory and brick-kiln chimneys in South Asian satellite imagery. Filtered a 600K+ image dataset down to the ~1% that actually contained pollution sources. [Paper](https://www.climatechange.ai/papers/neurips2024/6).

# Stable Diffusion 2 Image Generation

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Hugging Face](https://img.shields.io/badge/🤗-Hugging%20Face-yellow.svg)](https://huggingface.co/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org/)

A streamlined implementation for generating high-quality images using Stable Diffusion 2 with optimized inference settings.

## Overview

This project demonstrates the implementation of Stable Diffusion 2 for image generation using the Hugging Face Diffusers library. It utilizes the EulerDiscrete scheduler for optimal image generation and supports CUDA acceleration for faster inference.

## Generated Examples

Here are some examples of images generated using our implementation:

| Prompt | Generated Image |
|--------|----------------|
| "blue colored butterflies near a written letter" | ![Generated Image](https://github.com/tanush-em/diff-model-test/blob/master/sita-ramam.png) |

## Prerequisites

- Python 3.8+
- CUDA-capable GPU
- PyTorch with CUDA support

## Requirements

```txt
diffusers>=0.21.0
torch>=2.0.0
transformers>=4.31.0
accelerate>=0.21.0
```

## Acknowledgments

- Stability AI for the Stable Diffusion 2 model
- Hugging Face for the Diffusers library
- The open-source AI community

## Contact

For questions and feedback:
- Create an issue in this repository
- Contact the maintainers directly through their GitHub profiles

---

<div align="center">
Exploring the possibilities of AI-powered image generation
</div>

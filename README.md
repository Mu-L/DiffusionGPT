# DiffusionAgent: Navigating Expert Models for Agentic Image Generation

This repository contains the pytorch codes of our paper "[DiffusionAgent: Navigating Expert Models for Agentic Image Generation]()".

## Overview
DiffusionAgent leverages Large Language Models (LLM) to offer a unified generation agent capable of seamlessly accommodating various types of prompts and integrating domain-expert models.
![framework](imgs/framework.pdf)

## Demo
* [Spaces Demo 1](https://huggingface.co/spaces/DiffusionGPT/DiffusionGPT-XL)
* [Spaces Demo 2](https://huggingface.co/spaces/DiffusionGPT/DiffusionGPT)

## Environment

```bash
pip install -r requirements.txt
```

## Model Weights
All the checkpoints can get from [link](https://huggingface.co/spaces/DiffusionGPT/DiffusionGPT-XL/tree/main/checkpoints).

## Get Started

```bash
python DiffusionAgent-sdxl-app.py
```
or
```bash
python DiffusionAgent-sd15-app.py
```

## Bibtex
```
@article{qin2024diffusionagent,
  title={DiffusionAgent: Navigating Expert Models for Agentic Image Generation},
  author={Qin, Jie and Wu, Jie and Chen, Weifeng and Yueming Lyu},
  journal={arXiv preprint arXiv:2401.10061v2
},
  year={2024}
}
```

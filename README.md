# Type-specified Pokemon Image Generation

## Overview

Course project for ECE 285 SP25 Deep Generative Models. We have fine-tuned Stable Diffusion 1.5 with a 2-stage LoRA fine-tuning strategy. In stage 1, we let model learn general Pokemon features. In stage 2, we let model learn a certain type's Pokemon features.

## Samples before and after stage 1

| Vanilla SD 1.5                               | After 4 epochs fine-tuning       | After 8 epochs fine-tuning       |
| -------------------------------------------- | -------------------------------- | -------------------------------- |
| ![R4_Vanilla](figures/stage1/R4_Vanilla.png) | ![R4E4](figures/stage1/R4E4.png) | ![R4E8](figures/stage1/R4E8.png) |



## Samples before and after stage 2

| Prompt           | Before stage 2 fine-tuning             | After 8 epochs fine-tuning             |
| ---------------- | -------------------------------------- | -------------------------------------- |
| A fish Pokemon   | ![fish0](figures/stage2/fish0.png)     | ![fish0](figures/stage2/fish8.png)     |
| A flower Pokemon | ![flower0](figures/stage2/flower0.png) | ![flower8](figures/stage2/flower8.png) |

## Usage

Both jupyter notebooks can run directly in Google Colab environment.

We also provide trained lora weights of stage 1 in one folder. You may directly load them. 

# 2025_SCPC_AI-Challenge

2025 Samsung Collegiate Programming Challenge 4등상 수상
: 사용자의 일상 사진을 이해하는 on device multi-modal AI 개발

## 📌 Project Overview

본 프로젝트는 모바일 환경(≤3B 파라미터)에서 동작하는 Multi-Modal AI 모델(VLM)을 구현하기 위해, 기존 pruning 연구에서 관찰되는 accuracy 상승 현상을 단순한 성능 개선이 아닌 모델의 확신도 부족으로 인한 현상으로 재해석하여 **확신도 기반 동적 추론 전략 결정 구조**를 설계한 프로젝트입니다. 이러한 전략을 통해 단일 모델 대비 Accuracy 성능(66% → 78%)을 향상시키는 동시에, 모델의 확신도에 따라 문제 풀이 전략을 동적으로 선택하여 추론 비용과 응답 속도를 동시에 개선했습니다.

## 📚 References

본 프로젝트는 다음 연구들을 기반으로 설계되었습니다.

- **LoRA: Low-Rank Adaptation of Large Language Models**  
  → Full Fine-tuning 없이 파라미터 효율적으로 성능을 복구하기 위한 방법으로 활용

- **LLM-Pruner: On the Structural Pruning of Large Language Models**  
  → 구조적 pruning 및 LoRA 기반 빠른 성능 복구 아이디어 참고

- **LLM-Streamline: Streamlining Redundant Layers to Compress Large Language Models**  
  → layer 중요도 기반 pruning 및 Pruning 이후 Accuracy 증가 현상 참고


## ⚙️ Execution Environment

### 🖥️ System
* Platform: Google Colab (Linux)
* Python: 3.12.13
* OS: Linux 6.6.113+ (glibc 2.35)

### 🚀 Hardware
* GPU: NVIDIA H100 (Hopper Architecture)
* CUDA: 12.8

### 🧠 Deep Learning Framework
* PyTorch: 2.10.0 (cu128)
* torchvision: 0.25.0 (cu128)

### 🤖 Libraries
* transformers: 4.44.2

![Presentation](https://github.com/olchan/2025_SCPC_AI-Challenge/blob/main/Presentation1.png?raw=true)
![Presentation](https://github.com/olchan/2025_SCPC_AI-Challenge/blob/main/Presentation2.png?raw=true)
![Presentation](https://github.com/olchan/2025_SCPC_AI-Challenge/blob/main/Presentation3.png?raw=true)
![Presentation](https://github.com/olchan/2025_SCPC_AI-Challenge/blob/main/Presentation4.png?raw=true)
![Presentation](https://github.com/olchan/2025_SCPC_AI-Challenge/blob/main/Presentation5.png?raw=true)
![Presentation](https://github.com/olchan/2025_SCPC_AI-Challenge/blob/main/Presentation6.png?raw=true)

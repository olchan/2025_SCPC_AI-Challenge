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

<img width="1920" height="1080" alt="Presentation1" src="https://github.com/user-attachments/assets/1e1356e1-a402-4913-9243-aec553d92c12" />
<img width="1920" height="1080" alt="Presentation2" src="https://github.com/user-attachments/assets/d3f466d7-81ab-4579-a9c2-a9c547679443" />
<img width="1920" height="1080" alt="Presentation3" src="https://github.com/user-attachments/assets/5977ed1c-3d55-4f02-a0e5-df06010a8691" />
<img width="1920" height="1080" alt="Presentation4" src="https://github.com/user-attachments/assets/4b4a5c78-e02d-411a-b0f8-fcf70f9f2a9d" />
<img width="1920" height="1080" alt="Presentation5" src="https://github.com/user-attachments/assets/b2c25f6a-f6a0-4a09-8ce0-fcb33bbad2a2" />
<img width="1920" height="1080" alt="Presentation6" src="https://github.com/user-attachments/assets/6258a00b-ba2f-4dd6-84e6-52d4fc293309" />



# AI 입문 교육

🇰🇷 한국어 | 🇺🇸 [English](README.md)

머신러닝 기초부터 최신 LLM 추론 최적화 기술까지 실습 중심으로 학습하는 교육 과정입니다.

## 교육 목표

- AI 기본 개념 이해
- Transformer 구조 이해
- GPT부터 DeepSeek까지 발전 과정 이해
- Foundation Model 이해
- LLM 추론 최적화 기술 이해

## 교육 과정

| 세션 | 주제 |
|--------|--------|
| Session 1 | AI / ML / DL 기초 |
| Session 2 | Transformer |
| Session 3 | LLM 발전 과정 |
| Session 4 | Foundation Model 확장 |
| Session 5 | Efficient LLM Inference |

---

### Session 1. AI / ML / DL 기초

#### 목표
- Loss가 무엇인지 이해한다.
- Weight가 왜 학습되는지 이해한다.
- Gradient Descent가 왜 동작하는지 이해한다.

#### 주요 내용
- 지도학습 / 비지도학습
- 분류 / 회귀
- 퍼셉트론
- 다층 퍼셉트론
- Loss Function
- Backpropagation
- Gradient Descent
- Overfitting

📒 Notebook: [GitHub](sessions/session1.ipynb) | [Open in Colab](https://colab.research.google.com/github/yesredpig/ai_study/blob/main/sessions/session1.ipynb)
---

### Session 2. Transformer

#### 목표
- GPT 논문을 읽고 이해할 수 있다.

#### 주요 내용
- Why RNN Failed
- Attention
- Query / Key / Value
- Multi-Head Attention
- Positional Encoding
- RoPE
- Transformer Block
- KV Cache
- Prefill / Decode

---

### Session 3. LLM 발전 과정

#### 목표
- GPT부터 DeepSeek까지의 발전 과정을 이해한다.

#### 주요 내용
- GPT-1 ~ GPT-3
- OPT
- LLaMA
- Gemma
- Qwen
- DeepSeek
- SFT
- RLHF
- DPO
- Chain of Thought
- Self Consistency

---

### Session 4. Foundation Model 확장

#### 목표
- 언어 모델을 넘어 Foundation Model을 이해한다.

#### 주요 내용
- Transfer Learning
- Pretraining
- Fine-tuning
- JEPA
- Vision Transformer
- CLIP
- SigLIP
- Gemma3
- Multimodal Fusion

---

### Session 5. Efficient LLM Inference

#### 목표
- 왜 LLM이 느린지 이해한다.
- 최신 추론 최적화 기술을 이해한다.

#### 주요 내용
- Prefill / Decode
- KV Cache
- PagedAttention
- vLLM
- Continuous Batching
- FlashAttention
- FlashInfer
- Quantization
- Speculative Decoding
- MoE
- Mixtral
- DeepSeek-V3

## 추천 논문

- Attention Is All You Need
- RoFormer
- Language Models are Few-Shot Learners
- LLaMA
- DeepSeek-R1
- CLIP
- FlashAttention
- vLLM

## 작성자

전은주

관심 연구 분야
- LLM Systems
- Speculative Decoding
- KV Cache Optimization
- Foundation Models
- Healthcare

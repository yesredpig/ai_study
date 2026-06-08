[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yesredpig/study/blob/main/ai_intro/session1.ipynb)

# AI Introduction Course

Hands-on introduction to modern AI systems, from Machine Learning fundamentals to Large Language Model (LLM) inference optimization.

---

## Course Overview

| Session   | Topic                     | Objective                                              |
| --------- | ------------------------- | ------------------------------------------------------ |
| Session 1 | AI / ML / DL Fundamentals | Understand Loss, Backpropagation, and Gradient Descent |
| Session 2 | Transformer               | Understand the architecture behind GPT-style models    |
| Session 3 | LLM Evolution             | Learn how LLMs evolved from GPT to DeepSeek            |
| Session 4 | Foundation Models         | Explore Multimodal AI and Representation Learning      |
| Session 5 | Efficient LLM Inference   | Understand how modern LLM serving systems work         |

---

# Session 1. AI / ML / DL Fundamentals

### Objective

* What is Loss?
* Why are weights learned?
* Why does Gradient Descent work?

### Topics

* Supervised Learning
* Unsupervised Learning
* Classification vs Regression
* Perceptron
* Multi-Layer Perceptron
* Loss Function
* Backpropagation
* Gradient Descent
* Learning Rate
* Regularization
* Dropout
* Early Stopping

### Notebook

[Open in Colab](https://colab.research.google.com/github/yesredpig/study/blob/main/ai_intro/session1.ipynb)
---

# Session 2. Transformer

### Objective

* Read and understand GPT-related papers

### Topics

* Why RNN Failed
* Attention
* Query / Key / Value
* Multi-Head Attention
* Positional Encoding
* Sinusoidal Encoding
* RoPE
* Transformer Block
* Residual Connection
* LayerNorm
* KV Cache
* Prefill & Decode

### Papers

* Attention Is All You Need
* RoFormer

### Notebook

[Open Notebook](session2_transformer.ipynb)

---

# Session 3. LLM Evolution

### Objective

* Understand the evolution of modern LLMs

### Topics

* GPT-1
* GPT-2
* GPT-3
* OPT
* LLaMA
* Gemma
* Qwen
* DeepSeek

### Advanced Topics

* Context Extension
* RoPE
* NTK Scaling
* YaRN
* SFT
* RLHF
* DPO
* Chain of Thought
* Self Consistency
* Test Time Scaling

### Papers

* Language Models are Few-Shot Learners
* LLaMA
* DeepSeek-R1

### Notebook

[Open Notebook](session3_llm_evolution.ipynb)

---

# Session 4. Foundation Models & Multimodal AI

### Objective

* Understand Foundation Models beyond language

### Topics

* Transfer Learning
* Pretraining
* Fine-tuning
* Representation Learning
* JEPA
* Predictive World Models
* Vision Transformer
* CLIP
* SigLIP
* Gemma3
* Multimodal Fusion

### Papers

* A Path Towards Autonomous Machine Intelligence
* CLIP

### Notebook

[Open Notebook](session4_foundation_model_expansion.ipynb)

---

# Session 5. Efficient LLM Inference

### Objective

* Understand why LLMs are slow and how they are optimized

### Topics

#### Inference Pipeline

* Prefill
* Decode
* KV Cache

#### LLM Serving

* PagedAttention
* vLLM
* Block Manager
* Continuous Batching

#### Attention Optimization

* FlashAttention
* FlashAttention-2
* FlashInfer

#### Quantization

* GPTQ
* AWQ
* SmoothQuant
* FP8
* INT4

#### Advanced Inference

* Speculative Decoding

#### Mixture of Experts (MoE)

* Mixtral
* DeepSeek-V3
* Kimchi
* Expert Routing
* Shared Expert
* Load Balancing

### Papers

* vLLM
* FlashAttention
* Speculative Decoding
* Mixtral of Experts

### Notebook

[Open Notebook](session5_efficient_llm_inference.ipynb)

---

## Repository Structure

```text
ai_intro/
├── README.md
├── session1_ai_ml_dl_fundamentals.ipynb
├── session2_transformer.ipynb
├── session3_llm_evolution.ipynb
├── session4_foundation_model_expansion.ipynb
└── session5_efficient_llm_inference.ipynb
```

---

## Recommended Reading

* Attention Is All You Need
* RoFormer
* Language Models are Few-Shot Learners
* LLaMA
* DeepSeek-R1
* CLIP
* JEPA
* FlashAttention
* vLLM
* Mixtral

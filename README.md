# Jupyter

---

## 📘 소개 (Overview)

이 저장소는 다양한 AI 및 LLM 관련 실험을 Jupyter Notebook 환경에서 수행하고 정리한 결과를 기록한 저장소입니다.  
PyTorch, Transformers, Tokenizer, Fine-Tuning, Pretraining, Embedding 등 AI 연구 및 구현에 필요한 다양한 주제를 포함하며,  
직접 구현 및 실험한 내용을 reproducible 형태로 관리합니다.

---

## 🧪 실험 주제 (Experiments)

- [x] GPT 계열 모델 직접 구현 및 학습 (예: smolGPT, nanoGPT 스타일)
- [x] Tokenizer 실습 (BPE, tiktoken, AutoTokenizer)
- [x] Transformer 구조 직접 구현 (Attention, FeedForward 등)
- [x] Fine-tuning / Prompt Tuning 실험
- [x] 학습 loss 시각화 및 generation 결과 평가

---

## 🛠 사용 기술 (Tech Stack)

| 영역 | 도구/프레임워크 |
|------|-----------------|
| 언어 | Python 3.9+     |
| DL 프레임워크 | PyTorch |
| 토크나이저 | tiktoken, Huggingface Transformers |
| 실행 환경 | Jupyter Notebook (.ipynb) |
| 기타 | CUDA 12.6 (선택), matplotlib 등 |
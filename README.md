# Synapse-Talk 소개

**Synapse-Talk**는 Transformer 기반 **대화형 언어 모델(LLM)을 처음부터 구축하는 1인 R&D 프로젝트**입니다.

이 프로젝트는 단순히 AI API를 사용하는 것이 아니라  
**데이터 수집 → 모델 학습 → 정렬 → 추론 → 제품화**까지  
대화형 AI 시스템의 전체 구조를 직접 설계하고 구현하는 것을 목표로 합니다.

Data Pipeline
→ Tokenizer
→ Pretraining
→ SFT / DPO Alignment
→ Inference Server
→ Chat API
→ Chat UI

Synapse-Talk는 **대화형 AI 시스템이 실제로 어떻게 설계되고 운영되는지**를  
엔지니어링 관점에서 재현하고 이해하기 위한 프로젝트입니다.

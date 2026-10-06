# Codex research skills

This repository contains a curated **project-local** skill bundle under `.codex/skills/`.

## Orchestra Research

- `autoresearch` — end-to-end research orchestration
- `brainstorming-research-ideas` — research ideation and gap finding
- `creative-thinking-for-research` — alternative hypotheses and method design
- `peft` — LoRA / QLoRA / PEFT
- `trl-fine-tuning` — SFT, reward modeling, DPO variants, online RL
- `grpo-rl-training` — GRPO workflows
- `simpo` — preference-optimization baseline
- `lm-evaluation-harness` — reproducible LLM evaluation
- `weights-and-biases` — experiment tracking and sweeps
- `academic-plotting` — publication-quality plots
- `ml-paper-writing` — ML paper writing and review workflow

Source: https://github.com/Orchestra-Research/AI-Research-SKILLs

## Hugging Face complements

- `huggingface-datasets` — dataset inspection and processing
- `huggingface-community-evals` — evaluation workflows
- `hf-mem` — GPU / model memory estimation
- `huggingface-papers` — paper/model/dataset discovery
- `train-sentence-transformers` — rankers, CrossEncoders, hard-negative mining

Source: https://github.com/huggingface/skills

## Recommended workflow for this project

1. **autoresearch / ideation** for research questions and experiment decomposition.
2. **peft + trl-fine-tuning** for SFT and DPO.
3. **train-sentence-transformers** for personalized rankers, pair similarity, and hard-negative mining.
4. **weights-and-biases** for run tracking, artifacts, and sweeps.
5. **lm-evaluation-harness / community-evals** for standardized evaluation when applicable.
6. **academic-plotting + ml-paper-writing** when turning experiments into a paper.
7. Use **GRPO** only after the reward signal is validated.

## Notes

This is a deliberately curated subset rather than all Orchestra skills, so Codex routing stays focused on the current LLM-personalization research workflow.

Upstream license texts are in `.codex/skills/_licenses/`.

# 06 - Responsible Fine-Tuning

> Status: coming soon. This is a draft outline, not the official TLIP guide yet.

Fine-tuning is phase two, not the default first step.

Use fine-tuning only when:

- prompts are not enough,
- a knowledge pack/RAG is not enough,
- you have clean consented examples,
- and you have a way to evaluate whether the fine-tune helped.

## Beginner Terms

- LoRA: a smaller adapter trained on top of a base model.
- PEFT: parameter-efficient fine-tuning methods, including LoRA.
- Dataset: the examples used to train or adapt the model.
- Eval: a test set used to check whether behavior improved or got worse.
- Model card: a document describing the model, data, limits, and intended use.

## Required Before Fine-Tuning

- consented data,
- private data removed or explicitly approved,
- source notes,
- train/test split,
- eval prompts,
- model card draft,
- rollback plan,
- and a reason RAG cannot solve the problem.

## Reference

Hugging Face PEFT docs: https://huggingface.co/docs/peft/index

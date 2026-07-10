# 02 - Living Model Matrix

Updated on our last model-list pass: July 10, 2026.

*We do our best to keep the models updated, but please always double check the
official model page, license, and runner docs before downloading or recommending
a model.*

This is a starter matrix. Exact requirements depend on quantization, context
length, runner, GPU support, operating system, and the model itself.

## Size Tiers

| Tier | Model size | Practical floor | Notes |
| --- | --- | --- | --- |
| Tiny | 1B to 3B | 4-8 GB RAM, 10+ GB free storage | Good first test for old laptops and edge devices. |
| Starter | 3B to 4B | 8 GB RAM, 20+ GB free storage | Good first everyday local chat tier. |
| Everyday | 7B to 8B | 16 GB RAM, SSD preferred, GPU helpful | Common local-AI target. |
| Strong | 12B to 14B | 24-32 GB RAM or suitable GPU/Apple unified memory | Better quality, heavier pressure. |
| Large / branch host | 20B to 30B+ | 64 GB+ memory class or strong GPU setup | Better for shared machines. |
| Research / heavy host | 70B+ and MoE | High-memory workstation or multi-GPU class | Not a normal beginner setup. |

## Starter Families

| Family | Links | Local starting point | Notes |
| --- | --- | --- | --- |
| Llama | [Official access](https://www.llama.com/llama-downloads/), [Hugging Face](https://huggingface.co/meta-llama) | 1B-8B tier | Common local path. Check Meta license/access terms. |
| Gemma | [Official page](https://deepmind.google/models/gemma/), [Hugging Face collection](https://huggingface.co/collections/Gemmaverse/google-variants) | 1B-4B tier | Good beginner family. Check the specific Gemma terms. |
| OpenAI gpt-oss | [Official page](https://openai.com/index/introducing-gpt-oss/), [Hugging Face](https://huggingface.co/openai/gpt-oss-120b), [Ollama](https://ollama.com/library/gpt-oss) | 20B tier | Open-weight reasoning family. 120B is high-end hardware territory. |
| Qwen | [Qwen on Hugging Face](https://huggingface.co/Qwen), [Qwen docs](https://qwenlm.github.io/) | 0.6B-8B tier | Broad family with chat, coder, embedding, vision-language, and reasoning variants. |
| Mistral / Mixtral | [Mistral on Hugging Face](https://huggingface.co/mistralai), [Mistral docs](https://docs.mistral.ai/) | 7B-12B tier | Useful family, but hardware needs vary by model and quantization. |
| DeepSeek | [DeepSeek on Hugging Face](https://huggingface.co/deepseek-ai) | 1.5B-8B tier | Track small distilled models separately from very large MoE releases. |
| GLM-5.2 / Z.ai | [Official release](https://z.ai/blog/glm-5.2), [Hugging Face](https://huggingface.co/zai-org/GLM-5.2), [GitHub](https://github.com/zai-org/GLM-5) | Research cluster / API | MIT-licensed 744B-total, 40B-active MoE model with a 1M-token context. The official BF16 checkpoint is about 1.51 TB, so this is not a normal laptop or single-GPU model. |
| Grok / xAI | [Official open release](https://x.ai/news/grok-os), [Grok-1 GitHub](https://github.com/xai-org/grok-1), [Grok-2 on Hugging Face](https://huggingface.co/xai-org/grok-2) | Branch host / research | Important open-weight lineage, not beginner laptop hardware. |
| Phi / small models | [Microsoft models on Hugging Face](https://huggingface.co/microsoft) | 2B-4B tier | Useful for older hardware and teaching the workflow before scaling. |

## Matrix Fields To Maintain

Use `templates/model-matrix.csv` or a GitHub issue to track:

- model family,
- exact model name,
- parameter size,
- quantization,
- runner,
- official source link,
- license/access notes,
- open-weight vs fully open-source status,
- tested device specs,
- rough minimum hardware,
- recommended hardware,
- and beginner fit.

# 01 - First Local Model

Goal: install one runner, download one small model, and run one local chat.

## Option A: LM Studio

Best for: first-time users who want a graphical app.

1. Install LM Studio: https://lmstudio.ai/
2. Use the model search/download flow:
   https://lmstudio.ai/docs/app/basics/download-model
3. Choose a small model first.
4. Start a chat.
5. Record the result in the model test report template.

## Option B: Ollama

Best for: simple local command line and local API use.

1. Install Ollama: https://ollama.com/download
2. Browse model families: https://ollama.com/library
3. Start with a small model that fits your machine.
4. Run the model.
5. Record the result in the model test report template.

## Option C: llama.cpp

Best for: advanced users who want GGUF files and lower-level control.

1. Open llama.cpp: https://github.com/ggml-org/llama.cpp
2. Read the current build/run instructions.
3. Use a GGUF model that matches your hardware.
4. Record exact commands and settings.

## First Test Prompt

Use a simple practical prompt:

```text
Explain what you are, what machine you are running on, and what kinds of local
tasks you are good for. Keep it short.
```

Then test one task you actually care about, such as:

- summarize a short document,
- draft a local resource note,
- explain a technical term,
- rewrite a short message,
- or compare two setup options.


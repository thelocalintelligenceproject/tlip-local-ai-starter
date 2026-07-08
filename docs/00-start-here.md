# 00 - Start Here

This starter pack is for people who already know their basic device specs and
want to run a local model.

## The Flow

1. Check the device.
   - RAM
   - free storage
   - GPU/VRAM if present
   - operating system
   - device role: laptop, branch host, storage node, edge device, etc.

2. Pick one runner.
   - LM Studio if you want a beginner GUI.
   - Ollama if you want a simple local CLI/API service.
   - llama.cpp if you want lower-level GGUF control.

3. Pick one starter model.
   - Start smaller than the machine can theoretically handle.
   - A fast small model teaches more than a huge model that freezes.

4. Run a first local chat.
   - Ask simple questions.
   - Watch speed, heat, fan noise, and memory pressure.
   - Decide whether this machine is good for chat, documents, storage, or a
     support role.

5. Add documents.
   - Use a knowledge pack or local RAG/search first.
   - Do not jump straight to fine-tuning.

6. Build slowly.
   - Companion
   - agent
   - tools
   - memory
   - fine-tuning

Each layer should be tested by itself before being combined.


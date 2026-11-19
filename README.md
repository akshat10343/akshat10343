### Hi, I'm Akshat 👋

**I build ML systems from scratch, then prove they're correct.**

I study computer science at the University of Washington. This summer I was an AI/ML research intern at Nokia Bell Labs, auditing intrusion-detection benchmarks for label leakage. On my own time I wrote an LLM inference engine in raw PyTorch, with a correctness test behind every speedup.

#### 🔧 Featured: [mini-llm-engine](https://github.com/akshat10343/mini-llm-engine)

TinyLlama-1.1B served from raw PyTorch: a hand-written Llama forward pass, a slot-based KV cache, continuous batching, INT8 quantization, and a FastAPI server. No vLLM, no llama.cpp.

- **0.0** max logit error against the Hugging Face reference
- **11.3×** faster decode with the KV cache, within 3.1% of HF `generate()`
- **4.63×** the batch-1 throughput with continuous batching on a 17-request workload
- **46.9%** smaller model tensors with INT8 weights, at 100% top-1 agreement

All numbers come from checked-in benchmark runs on an Apple M2 CPU.

#### Also here

- [personal-ai-portfolio](https://github.com/akshat10343/personal-ai-portfolio): the code behind [akshat-kansal.vercel.app](https://akshat-kansal.vercel.app)
- [NLP-for-Finance](https://github.com/akshat10343/NLP-for-Finance): bag-of-words vs. LSTM vs. fine-tuned BERT on financial news sentiment (96.9% test accuracy)
- [SolarSave](https://github.com/akshat10343/SolarSave): full-stack React + Express app that charts a location's solar potential from NREL data

**Stack:** Python · PyTorch · FastAPI · TypeScript · React · Node.js

**Find me:** [Portfolio](https://akshat-kansal.vercel.app) · [LinkedIn](https://linkedin.com/in/akshatUW)

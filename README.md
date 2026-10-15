# Hey, I'm Ankit 👋

CS + ML at the University of Maryland, building high-performance systems at the intersection of machine learning, GPUs, and markets.

### Currently exploring

- ML infrastructure and efficient inference
- CUDA, rendering, and performance engineering
- Quantitative systems and market infrastructure

### Selected work

| Project | What it does |
|---|---|
| [Chroma](https://github.com/AnkitNakhawa/Chroma) | Native C++ render graph for agent-generated video |
| [cuda-profiling](https://github.com/AnkitNakhawa/cuda-profiling) | CUDA profiling experiments, performance notes, and reproducible GPU benchmarks |
| [signalforge](https://github.com/AnkitNakhawa/signalforge) | High-performance execution and order-book core |
| [img2tok](https://github.com/AnkitNakhawa/img2tok) | Reduces image-token costs for vision-language models |

### Some examples of my work

- **[Triton — Fix large tensor descriptor shapes in pointer fallback](https://github.com/triton-lang/triton/pull/12278)** — Fixed an integer-extension bug that broke bounds checks for tensor dimensions between `2^31` and `2^32`, with a focused MLIR regression test.
- **[Burn — Optimize `fold4d` fallback with grouped transposed convolution](https://github.com/tracel-ai/burn/pull/5811)** — Reduced generated weights and convolution work by a factor of the input channel count while preserving a backend-agnostic fallback.
- **[vLLM — Fix encoder round-robin fan-out](https://github.com/vllm-project/vllm/pull/52491)** — Corrected multimodal request routing so traffic rotates across every configured encoder, with concurrency-safe state and regression coverage.

[LinkedIn](https://www.linkedin.com/in/ankit-nakhawa/) · [ORCID](https://orcid.org/0009-0000-5498-9393)

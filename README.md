# Hey, I'm Ankit 👋

CS + ML at the University of Maryland, exploring ML, Inference, and Markets.
Full-time Engineer @ IMC Trading.

### Open source contributions

- **[Triton — Fix large tensor descriptor shapes in pointer fallback](https://github.com/triton-lang/triton/pull/12278)** — Fixed an integer-extension bug that broke bounds checks for tensor dimensions between `2^31` and `2^32`, with a focused MLIR regression test.
- **[Burn — Optimize `fold4d` fallback with grouped transposed convolution](https://github.com/tracel-ai/burn/pull/5811)** — Reduced generated weights and convolution work by a factor of the input channel count while preserving a backend-agnostic fallback.
- **[vLLM — Fix encoder round-robin fan-out](https://github.com/vllm-project/vllm/pull/52491)** — Corrected multimodal request routing so traffic rotates across every configured encoder, with concurrency-safe state and regression coverage.

- **[PyTorch — Preserve input placeholders during Inductor graph cleanup](https://github.com/pytorch/pytorch/pull/193708)** — Prevented graph cleanup from erasing input placeholders and changing compiled function signatures, fixing argument-count crashes.
- **[PyTorch — Exclude Python function events from profiler summaries by default](https://github.com/pytorch/pytorch/pull/188631)** — Kept Python-internal frames out of `key_averages()` by default while adding an explicit opt-in.

[LinkedIn](https://www.linkedin.com/in/ankit-nakhawa/) · [ORCID](https://orcid.org/0009-0000-5498-9393)

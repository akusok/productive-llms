# productive-llms
A course that investigates best ways of getting value out of LLMs for a software developer

## Local LLMs

`llama.cpp` repo is a way of installing and running LLMs locally on an M2 Macbook with GPU acceleration out-of-the-box. 

Models can be downloaded from the Huggingface. Grab the GGUF format models with some quantization level already.

Memory requirements:
- nothing for 7B model
- 20G for 13B model at q6_K quantization

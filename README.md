---
license: apache-2.0
language:
- en
base_model:
- HuggingFaceTB/SmolLM2-135M-Instruct
pipeline_tag: text-generation
library_name: transformers
tags:
- safetensors
- onnx
- transformers.js
---

# amd/SmolLM2-135M-Instruct-onnx-ryzenai-1.7-hybrid
- ## Introduction
  This model was prepared using the AMD Quark Quantization tool, followed by necessary post-processing.    

- ## Quantization Strategy
  - AWQ / Group 128 / Asymmetric / UINT4 Weights / BFP16 activations
  - Excluded Layers: None
 
- ## Quick Start
For quickstart, refer to [Ryzen AI documentation](https://ryzenai.docs.amd.com/en/latest/hybrid_oga.html)

#### Evaluation scores
The MMLU scores are astronomy: , philosophy: , and management: .

#### License
Modifications copyright(c) 2026 Advanced Micro Devices,Inc. All rights reserved.

MIT License

Copyright (c) 2026 Advanced Micro Devices, Inc 

[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)